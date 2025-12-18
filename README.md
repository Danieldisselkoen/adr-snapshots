# ADR Snapshots Repository

Deze repository bevat automatische snapshots van ADR nieuwssites.

## Structuur
- Domain directories (ad.nl, bd.nl, etc.) worden automatisch aangemaakt
- `domain-indexes/`: Index bestanden per domain
- `latest.json`: Laatste snapshot status
- `global-index.json`: Globale index
- `snapshots-index.json`: Snapshot manifest

## Automatische Updates
Deze repository wordt automatisch geüpdatet door GitHub Actions workflow in adr-brandguide.

## Timestamp Synchronisatie Fix
Alle snapshots binnen één run gebruiken nu exact dezelfde timestamp voor perfecte consistentie tussen:
- Directory namen (bijv. `ad.nl/2025-09-13/23-42/`)
- Manifest tijden (`"time": "23-42"`)
- Wayback interface loading

Laatste cleanup: 13-9-2025, 23:48 - Voorbereiding voor gefixxe timestamp workflow
