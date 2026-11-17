# Salsa Figuren Lab

Een lichtgewicht web-app om salsa-combinaties te genereren (voor Leider en Volger), op te slaan met notities en te synchroniseren via GitHub Gist.

## Functies

- **Dobbelsteen-generator**: Genereer willekeurige combinaties voor Leider en Volger, met de mogelijkheid om één van beide vast te zetten (slotje).
- **Handmatige keuze**: Kies zelf bewegingen uit de dropdowns.
- **Opslaan & Notities**: Bewaar combinaties met een persoonlijke notitie, bewerk notities, filter via de zoekbalk of kopieer je hele lijst naar het klembord.
- **Local Storage**: Alle opgeslagen figuren worden automatisch lokaal in je browser bewaard (`salsa_figuren_collectie_v1`).
- **GitHub Gist Synchronisatie**:
  - Sla je lijst op in een (privé of openbare) GitHub Gist via een Personal Access Token met `gist`-rechten.
  - Laad een Gist vanaf een ander apparaat (samenvoegen of vervangen), of deel een verzameling via `?gist=<GIST_ID>`.
  - Optionele auto-sync bij wijzigingen.
