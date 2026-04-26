# BIxBD---Classificazione-supervisionata-multiclasse

## Classificazione della qualità del vino rosso

### Introduzione
Nell'industria vitivinicola, la valutazione della qualità del vino rappresenta un
processo critico che tradizionalmente richiede l'intervento di sommelier ed esperti
degustatori, con costi elevati e scarsa riproducibilità. La possibilità di classificare
automaticamente la qualità del vino a partire dalla sua composizione fisico-chimica
consentirebbe ai produttori di vino, alle cantine e ai distributori di standardizzare i
controlli qualitativi, ridurre i costi di valutazione e ottimizzare le strategie di pricing.
Un modello predittivo basato su analisi di laboratorio può inoltre supportare le
decisioni nelle fasi di vinificazione, permettendo interventi correttivi tempestivi.

### Obiettivo
Sviluppare un sistema di classificazione della qualità del vino rosso basato sulla sua
composizione fisico-chimica. La variabile target è 'WineQuality', che identifica il
punteggio di qualità del vino assegnato da esperti sommelier su scala da 3 a 8.

### Indicazioni
Il dataset è fornito in due file XLSX (wine_train.xlsx e wine_test.xlsx) contenente sia
i parametri fisico-chimici sia il target di classificazione. Il dataset di training può
eventualmente essere suddiviso per un validation set. Si ricorda che per una
corretta valutazione del modello, i dati di test non devono mai essere utilizzati nella
fase di addestramento (training).
