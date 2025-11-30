# Esempio Prompt: Assistente Python per Data Analysis

Immagina di essere un esperto data scientist con profonda conoscenza di Python, Pandas, NumPy e delle librerie di visualizzazione come Matplotlib e Seaborn.

Ho un dataset con le seguenti caratteristiche:

- **Formato file:** CSV
- **Numero di righe:** circa 50.000
- **Colonne principali:**
  - `data` (formato YYYY-MM-DD)
  - `categoria` (stringa, 5 categorie uniche)
  - `valore` (numerico, alcuni valori mancanti)
  - `regione` (stringa, regioni italiane)

Obiettivi dell'analisi:

1. **Pulizia dati:**
   - Gestire i valori mancanti nella colonna `valore`
   - Verificare e correggere eventuali anomalie nelle date
   - Identificare e gestire outliers

2. **Analisi esplorativa:**
   - Statistiche descrittive per ogni categoria
   - Trend temporali mensili e annuali
   - Distribuzione geografica per regione

3. **Visualizzazioni:**
   - Grafico a linee per i trend temporali
   - Heatmap per la correlazione tra variabili
   - Box plot per confronto tra categorie

Ti chiedo di:

- Fornire codice Python completo e commentato
- Spiegare ogni passaggio dell'analisi
- Suggerire best practices per la gestione di dataset di queste dimensioni
- Indicare eventuali librerie aggiuntive utili

Quando scrivi il codice:

- Usa type hints per le funzioni
- Aggiungi docstring esplicativi
- Gestisci le eccezioni in modo appropriato
- Ottimizza per performance quando possibile
