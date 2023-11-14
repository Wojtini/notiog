# Data Driven
## Definicja
Data-drivenness dotyczy budowania narzędzi, zdolności, a przede wszystkim kultury, kótra działa na danych

## Co to oznacza że organizacja jest Data-Driven?

### Warunki wstępne
#### 1. Gromadzenie danych
- Dużo danych i dobrych danych
- Zbiór danych musi być terminowy, dokładny, czysty, bezstronny oraz godny zaufania
- mogą istnieć subtelne ukryte uprzezenia,które mogą wpłynąć na twoje wnioski, a czyszczenie i "massaging" danych mogą być trudne, czasochłonne i kosztowne.

Data Scientids spęzdają 80% czasi na czyszczenie i przygotowywanie danych, a pozostałe 20% na budowaniu modeli, analizowaniu, wizualzizacji i wyciąganiu wniosków z danych

Dużo prawidłowych danych nie sprawia jeszcze że jestesś data-driven

Czyste dane > Petabajty śmieci

#### 2. Gromadzenie danych
Aby traktować jako data-driven dane muszą być dodatkowo:
- Joinable (NoSQL, SQL, Hadoop)
- Shareable (kultura udostępniania danych np. łączenie transkacji z kliknięciami klientów)
Całość jest więszksza niż suma części
- Quearyable (filtrowanie, segregowanie i takie tam, również łatwość tych narzędzi/ obliczania metryk)

Ale to i tak jeszcze nie jest Data Driven

#### 3. Ludzie
Potrzeba ludzi z umiejętnośiami aby korzystać z tych danych.

Tacy którzy umią korzystać z narzędzi aby np stworzyć jakieś metryki. (wskażniki wzrostu subsrybcji)

Ludzie ci zadają Właściwe pytania dotyczące danych i wskaźniów (oraz ludzie któzy później z nich korzystają)

W skrócie na te dane musi być zapotrzebowanie

## Reporting vs Analysis
Reporting (informacja):

"The process of organizing data into informational summaries in order to monitor how different areas of a business are performing"
- Desriptive
- What?
- Backward-looking
- Raise questions
- Data -> Information
- Reports, dashborads, alerts
- No context

Analysis (wiedza):

"Transformation data assets into competetive insights that will drive business decisions and actions using people, processes and technologies"
- Prescriptive
- Why?
- Forward looking
- Answer Questions
- Data + information -> insights
- Findings recommendations predictions
- Context + storytelling

### Kluczowe kwestie (wg Davenport)
- Information
  - past - what happend(reporting) 
  - present - what is happening (alerts)
  - future - what will happen (extrapolation)
- Insight
  - how and why did it happend? (modelling, experimental design)
  - Whats the nest best action (recommendation)
  - Whats the best/worst that can happen (simulation, optimiztion)

## Działania które mocno angażują się w Datadriven orgs
1. org może nieustannie testować
   - test przepływu transakcji (linkedin robi 200 eksperymentów dziennie)
   - z użytkownikami (na temat nowych funkcjonalności)
2. Modelowanie predykcyjne (ważne wykrywanie błędów prognoz, wyciągać wnioski i ulepszać)
3. org wybiera warianty spośród scenariuszy lub przyszłości zdarzeń przy użyciu zestawu ważonych zmiennych
    - w każdej drodze plusy i minusy
    - określić zdarzenia ciekawe i niepokojące i określic ich wagi a następnie podjąć ostateczną decyzję

## The Analytics Vale Chain (Dykes, 2010)
W organizacjach opartych o danych jest taki chain:

Data -> Reporting -> Analysis -> Action -> Value

## Dojrzałość systemów analitycznych (Jim Davis, 2009)
8 poziomów systemów analitycznych
1. Standardowe raporty (what happened)
2. Raporty ad hoc (How many how oftern, where)
3. Zapytania drill down (where exactly is problem)
4. Alerty (what actions are needed)
5. Analizy statystyczne (why is it happening)
6. Prognozowanie (what if trend continue)
7. Modelowanie predykcyjne (what will happen next)
8. Optymalizacja (whats the best that can happen)