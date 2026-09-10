# Lawn Mower Card

Et selvstændigt, tema-kompatibelt Lovelace-kort til Home Assistant. Kortet er flyttet fra en aktiv installation til et separat repository, så kildekode og versionshistorik kan vedligeholdes sikkert.

## Installation

Kopiér `ha-lawn-mower-card.js` til `/config/www/ha-lawn-mower-card/` og registrér ressourcen som et JavaScript-modul:

```text
/local/ha-lawn-mower-card/ha-lawn-mower-card.js?v=0.3.0
```

Tilføj derefter korttypen `custom:ha-lawn-mower-card` i Lovelace. De nødvendige entities angives i kortets konfiguration; repositoryet indeholder ingen installationens dashboardkonfiguration eller personlige data.

## Udvikling

```bash
npm run check
```

## Licens

MIT
