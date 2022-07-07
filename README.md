# Immuni-Tweet-Analysis
Analisi delle opinioni degli utenti in merito all'applicazione di Contact Tracking **Immuni**. 

La suddetta analisi è stata condotta attraverso le seguenti **fasi**:
  1. **Data Collection**: raccolta tweet pubblicati nell'arco temporale di un anno e mezzo (da giugno 2020 a dicembre 2021) sul tema *App Immuni* utilizzando la libreria di Scraping [https://github.com/twintproject/twint](Twint) e impostando come termine di ricerca i tre hashtags più popolari (Immuni, AppImmuni, ImmuniApp) 
  2. **Data Understanding & Cleaning**: analisi preliminare dei dataset risultanti dalla fase precedente e pulizia da eventuali valori nulli e/o inutili ai fini dell'analisi 
  3. **Analisi Linguistiche**: estrazione di informazioni linguistiche di base dei tweet utilizzando la libreria **NLTK**
  5. **Sentiment Analyis**: Estrazione della polarità e dei sentimenti provati dagli utenti a partire dai tweet, utilizzando il modello *Feeò-it*, adatto per Sentiment anlysis di testi scritti in italiano.
  6. **Topic Modeling**: estrazione dei temi più rilevanti all'interno dei tweet utilizzando il modello **BERTopic**
