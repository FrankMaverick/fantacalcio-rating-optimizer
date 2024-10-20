# Fantacalcio Rating Optimizer

Sviluppare un modello di Machine Learning per il calcolo del valore di rating_target utilizzando i dati presenti nel file CSV, che contiene variabili legate alle statistiche dei giocatori durante una partita, il risultato della partita e altre info utili.

Tra le variabili di input c'è anche il rating di input, che però tende a essere più alto e a volte si discosta molto dal target.


Obiettivi del task:
- Esplorare il dataset e comprendere la distribuzione dei valori
- Analizzare i dati forniti nel CSV per comprendere quali feature sono più rilevanti per la predizione del rating.
- Pulizia e preparazione dei dati (gestione valori mancanti, normalizzazione/standardizzazione, encoding delle variabili categoriche, feature scaling, etc.).
- Dividere il dataset in training e test set.
- Definire un modello di Machine Learning supervisionato per predire rating_target come variabile di output.
- Testare diversi algoritmi di regressione (come Regressione Lineare, Random Forest, XGBoost, o reti neurali) per trovare quello con la performance migliore.
- Valutare la performance del modello tramite metriche come MSE (Mean Squared Error) o MAE (Mean Absolute Error).
- Documentare il processo e i risultati ottenuti.