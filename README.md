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

Laatste cleanup: 13-9-2025, 23:24:45
