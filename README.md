# CxAlloy ATL11 Sync

Initial ATL11 data-discovery repository.

## Required GitHub Actions configuration

Repository secrets:
- `CXALLOY_IDENTIFIER`
- `CXALLOY_SECRET`

Repository variable:
- `CXALLOY_PROJECT_ID` (one or more numeric project IDs, comma-separated)

Run **ATL11 CxAlloy Equipment Discovery** manually from the Actions tab. The workflow writes the extracted equipment data to `data/equipment_status.csv`.

The first run is manual only. Scheduled synchronization should be enabled after the ATL11 fields and status stages have been reviewed.
