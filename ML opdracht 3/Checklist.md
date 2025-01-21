Checklist

# Stappen om de Opdracht te Voltooien

## 1. Inleiding
- [X] Introduceer het project en de doelstellingen.
- [ ] Leg het belang van unsupervised learning uit bij het bepalen van muziekgenres.

## 2. Data
- [ ] Beschrijf de verstrekte datasets:
    - `labeled`: Bevat audiobestanden met bekende genres.
    - `Labels_new.csv`: Bevat de genres van de bestanden in `labeled`.
    - `unlabeled`: Bevat audiobestanden met onbekende genres.

## 3. Opdrachtbeschrijving
- [ ] Omschrijf de vereisten voor het notebook:
    - [ ] Structureer het notebook met markdown cellen en nummer de hoofdstukken en paragrafen.
    - [ ] Gebruik markdown cellen voor tekst en code cellen voor code.
    - [ ] Gebruik zelf-gedefinieerde functies en bij voorkeur OOP.
    - [ ] Zorg ervoor dat de code voldoet aan PEP8-standaarden, inclusief commentaar.
    - [ ] Alle teamleden moeten de code en tekst begrijpen.
    - [ ] Verwijs op de juiste manier naar alle gebruikte bronnen.

## Opdracht 1: Feature Engineering (35 punten)
- [X] Maak een Kaggle-account aan en vorm een team voor de competitie.
- [X] Noteer je teamnaam, leden en Kaggle-gebruikersnamen in het notebook.
- [X] Maak een dataframe met audiofeatures voor elk bestand:
    - [X] Spectrale bandbreedte
    - [X] Spectraal zwaartepunt
    - [X] Voeg minimaal 8 audiofeatures toe.
- [X] Leg de betekenis en berekening van elke feature uit.

## Opdracht 2: Unsupervised Learning (55 punten)
- [X] Bepaal het aantal clusters in de `unlabeled` dataset:
    - [X] Leg de methode uit die je hebt gebruikt om het aantal clusters te bepalen.
- [X] Voer clustering uit en ken clusternummers toe aan elk audiobestand in de `unlabeled` dataset.
    - [X] Leg de wiskundige werking van het clustering algoritme uit met een voorbeeld.
- [ ] Vergelijk de clusters met de gelabelde dataset met behulp van visualisaties.
    - [X] Bepaal het genre voor elke cluster.
    - [X] Vervang clusternummers door genres voor de indiening.
- [ ] Voer dimensionality reduction uit met PCA en NMF:
    - [X] Leg de wiskundige werking van PCA en NMF uit met voorbeelden.
    - [!] Toon hoe het aantal dimensies is bepaald.
    - [X] Voer clustering uit met de nieuwe features en analyseer verbeteringen.
- [X] Maak een eenvoudige app om vergelijkbare audiobestanden voor te stellen.

## Opdracht 3: Bevindingen en Conclusie (5 punten)
- [ ] Vat je bevindingen samen:
    - [X] Identificeer de belangrijkste features voor clustering.
    - [X] Beschrijf het effect en nut van dimensionality reduction.
    - [ ] Stel aanvullende gegevens voor die aanbevelingen kunnen verbeteren.

## Bijlage 1: Bronvermelding en Regels Gebruik Generative AI (GAI)
- [ ] Verwijs op de juiste manier naar alle gebruikte bronnen voor tekst en code.