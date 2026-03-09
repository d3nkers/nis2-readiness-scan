# NIS2 Readiness Scan
Interactieve zelfevaluatietool voor Nederlandse MKB-organisaties op basis van NIS2 artikel 21.

**Live tool:** https://d3nkers.github.io/nis2-readiness-scan

## Wat doet het
25 vragen verdeeld over zes beveiligingsdomeinen. Na invullen genereert de tool direct:

- Een **Security Maturity score** (volwassenheid van securityprocessen)
- Een **NIS2 Readiness score** (conformiteit aan artikel 21-vereisten)
- Een **geprioriteerde Security Roadmap** met concrete acties
- Een **downloadbaar PDF-rapport** op naam van het bedrijf

## Categorieën
- Governance
- Risicobeheer
- Incidentrespons
- Systeembeveiliging
- Toegangsbeheer
- Leveranciersbeveiliging

## Technisch
- Puur statisch: één HTML-bestand, geen backend, geen data-opslag
- PDF-export via jsPDF (CDN)
- Draait volledig client-side — geen gegevens worden verstuurd of opgeslagen
- Gehost via GitHub Pages

## Achtergrond
Gebouwd als onderdeel van [SafeMKB](https://safemkb.nl) — cybersecuritydienstverlening 
voor het Nederlandse MKB. De tool is bedoeld als eerste stap in een NIS2-traject, 
geen vervanging voor een formele audit.

## Licentie
MIT — vrij te gebruiken en aan te passen met bronvermelding.
