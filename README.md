# MachineLearning

# Project: Voorspel Verhuuraantallen 2024 - Kaggle Competitie

## Opdracht 1: Exploratieve Data Analyse (EDA)
- [X] **Maak een account aan op Kaggle** en vorm een team.
- [X] **Noteer de teamnaam, namen van teamleden, en Kaggle-gebruikersnamen** in het notebook.
- [X] **Laad de dataset in en inspecteer de datatypes** van iedere kolom.
- [X] **Genereer basisstatistieken** voor iedere kolom (mean, std, min, max, etc.).
- [ ] **Voeg tijdserie-elementen toe** (zoals maand, kwartaal, jaar) en visualiseer relevante patronen.
- [ ] **Visualiseer de relaties tussen de onafhankelijke variabelen** en de afhankelijke variabele met geschikte visualisaties (bijv. scatter plots, boxplots).
- [ ] **Analyseer en beschrijf de belangrijkste bevindingen** van de EDA.
- [ ] **Maak de dataset schoon** door onjuiste, irrelevante of missende data te verwijderen of te corrigeren.

## Opdracht 2: Time Series Feature Engineering
- [ ] **Voeg tijdserie-gerelateerde features toe**:
  - Trend
  - Seizoenspatronen
  - Cycli
- [ ] **Voer Fourier-analyse uit** om seizoenspatronen te onderzoeken.
- [ ] **Onderzoek de trends** in de data (bijv. stijgende of dalende patronen over de tijd).
- [ ] **Onderzoek de cycli en autocorrelatie** (gebruik autocorrelation plots om correlaties over de tijd te visualiseren).
- [ ] **Voeg andere tijdsgebaseerde features toe** (bijv. dag van de week, maand, feestdagen).
- [ ] **Onderzoek de invloed van de tijdseriefeatures** op de voorspellingen, samen met andere features.

## Opdracht 3: Modelleren
- [ ] **Selecteer minimaal 5 modellen** om te evalueren, inclusief:
  - Lineaire regressie
  - Een ensemble model (bijv. Random Forest, XGBoost)
  - Twee tijdseriemodellen (minstens één SARIMA(X) en één ander tijdserie model).
  - Een hybride model (eerste model voorspelt, tweede model voorspelt de residuals).
- [ ] **Pas lineaire regressie toe** en geef een duidelijke uitleg van de:
  - Loss function
  - Regularisatie
- [ ] **Leg de werking van het ensemble model** uit.
- [ ] **Pas cross-validation toe** op ieder model om overfitting te voorkomen.
- [ ] **Voer hyperparameter tuning uit** voor elk model om de prestaties te optimaliseren.
- [ ] **Pas ieder model toe op de testset** en upload de resultaten naar Kaggle.

## Opdracht 3: Bevindingen
- [ ] **Geef een samenvatting van de modelresultaten**:
  - Welk model presteert het beste en bij welke parameters?
  - Toon de scores op Kaggle en geef inzicht in verbeteringen door tuning.

## Opdracht 4: Conclusie en Aanbevelingen
- [ ] **Analyseer welke features het meeste invloed hebben** op de voorspellingen.
- [ ] **Beschrijf de overeenkomsten tussen de EDA en de belangrijkste features**.
- [ ] **Geef advies aan de verhuurder** op basis van de belangrijkste features:
  - Welk model zou je adviseren en waarom?
  - Is het model met de beste voorspellingen altijd het beste voor de verhuurder, of zijn er andere overwegingen (complexiteit, uitleg, etc.)?

