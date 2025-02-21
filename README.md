# Esame_TRMD
Repository contenente il lavoro d'esame (Effetto Ekman) per l'appello del 27/02/2025.

La Repository contiene:

- file .csv (copiato dal sito della Stazione di Biologia Marina di Pirano) contenente i dati analizzati;

- Notebook in cui è presente la analisi dei dati, con commenti sul codice e sui risultati ottenuti.


N.B. : nel corso dell'implementazione dell'analisi bayesiana, ho usato scipy.minimize per minimizzare il posterior (e ottenere il punto di partenza di emcee), tuttavia
non sono riuscito a rimuovere il Warning relativo ad errori nel calcolo del gradiente:

"RuntimeWarning: invalid value encountered in subtract df = fun(x) - f0)"

La funzione risulta minimizzata ma resta l'errore come output.
