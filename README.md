# MachineLearning

# Project: Voorspel Verhuuraantallen 2024 - Kaggle Competitie

## Opdracht 1: Exploratieve Data Analyse (EDA)
- [X] **Maak een account aan op Kaggle** en vorm een team.
- [X] **Noteer de teamnaam, namen van teamleden, en Kaggle-gebruikersnamen** in het notebook. Joes
- [X] **Laad de dataset in en inspecteer de datatypes** van iedere kolom.
- [X] **Genereer basisstatistieken** voor iedere kolom (mean, std, min, max, etc.).
- [X] **Voeg tijdserie-elementen toe** (zoals maand, kwartaal, jaar) en visualiseer relevante patronen. Joes
- [X] **Visualiseer de relaties tussen de onafhankelijke variabelen** en de afhankelijke variabele met geschikte visualisaties (bijv. scatter plots, boxplots). Joes
- [X] **Analyseer en beschrijf de belangrijkste bevindingen** van de EDA. Joes
- [X] **Maak de dataset schoon** door onjuiste, irrelevante of missende data te verwijderen of te corrigeren. Joes

## Opdracht 2: Time Series Feature Engineering
- [X] **Voeg tijdserie-gerelateerde features toe**: Joes
  - Trend -Klaar
  - Seizoenspatronen -Klaar
  - Cycli -Klaar
- [X] **Voer Fourier-analyse uit** om seizoenspatronen te onderzoeken. Tijn
- [X] **Onderzoek de trends** in de data (bijv. stijgende of dalende patronen over de tijd). Joes
- [ ] **Onderzoek de cycli en autocorrelatie** (gebruik autocorrelation plots om correlaties over de tijd te visualiseren). Tijn
- [X] **Voeg andere tijdsgebaseerde features toe** (bijv. dag van de week, maand, feestdagen). Joes
- [ ] **Onderzoek de invloed van de tijdseriefeatures** op de voorspellingen, samen met andere features. Jim

## Opdracht 3: Modelleren
- [] **Selecteer minimaal 5 modellen** om te evalueren, inclusief: Jip
  - Lineaire regressie
  - Een ensemble model (bijv. Random Forest, XGBoost)
  - Twee tijdseriemodellen (minstens één SARIMA(X) en één ander tijdserie model).
  - Een hybride model (eerste model voorspelt, tweede model voorspelt de residuals).
- [ ] **Pas lineaire regressie toe** en geef een duidelijke uitleg van de: Jip
  - Loss function
  - Regularisatie
- [ ] **Leg de werking van het ensemble model** uit. Jip + Jim
- [ ] **Pas cross-validation toe** op ieder model om overfitting te voorkomen. Jip + Jim
- [ ] **Voer hyperparameter tuning uit** voor elk model om de prestaties te optimaliseren. Jip+ Jim
- [ ] **Pas ieder model toe op de testset** en upload de resultaten naar Kaggle. Jip + Jim

## Opdracht 3: Bevindingen
- [ ] **Geef een samenvatting van de modelresultaten**: Jim
  - Welk model presteert het beste en bij welke parameters?
  - Toon de scores op Kaggle en geef inzicht in verbeteringen door tuning.

## Opdracht 4: Conclusie en Aanbevelingen Iedereen
- [ ] **Analyseer welke features het meeste invloed hebben** op de voorspellingen.
- [ ] **Beschrijf de overeenkomsten tussen de EDA en de belangrijkste features**.
- [ ] **Geef advies aan de verhuurder** op basis van de belangrijkste features:
  - Welk model zou je adviseren en waarom?
  - Is het model met de beste voorspellingen altijd het beste voor de verhuurder, of zijn er andere overwegingen (complexiteit, uitleg, etc.)?

