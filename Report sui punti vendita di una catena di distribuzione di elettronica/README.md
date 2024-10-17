# Gestione delle Vendite per Punti Vendita di TechMarket S.p.A.


TechMarket S.p.A. è una delle principali catene di distribuzione al dettaglio di prodotti di elettronica in Italia, con punti vendita distribuiti in tutto il Paese. L’azienda si trova a dover gestire enormi quantità di dati provenienti da ciascun punto vendita, e ha bisogno di ottenere report completi e dettagliati sulle vendite dei suoi prodotti di punta. Per questo motivo, TechMarket ha deciso di investire in una soluzione avanzata di **reportistica delle vendite**, capace di aggregare e visualizzare dati complessi in modo chiaro e navigabile.

TechMarket ti assume per implementare un sistema di reportistica che elabori i dati di vendita e fornisca informazioni dettagliate ai decision-maker. Il report permetterà di monitorare le vendite, le performance dei prodotti, l’efficacia delle promozioni e la resa di ogni singolo negozio.

### Obiettivo del Progetto

L'obiettivo è creare un **report interattivo** che permetta ai manager di TechMarket di:

- Visualizzare le vendite mensili, tenendo in considerazione sconto, unità vendute e prezzo
- Analizzare le vendite per ciascuna città
- Monitorare le performance di vendita per ogni prodotto
- Ottenere una panoramica completa dei dati di ciascun punto vendita

Inoltre, sarà necessario:

- Creare una pagina che tenga conto dei **resi** per calcolare le vendite nette, al fine di avere una visione più accurata delle performance.

### Valore Aggiunto

Il report che verrà sviluppato fornirà a TechMarket un importante **vantaggio competitivo** grazie a:

1. **Decisioni basate sui dati**: I dirigenti avranno accesso a informazioni precise e aggiornate per prendere decisioni strategiche mirate. Sarà possibile visualizzare i prodotti che vendono meglio in determinati periodi e le città con le migliori performance.
  
2. **Ottimizzazione delle vendite e delle promozioni**: Grazie ai dati dettagliati, sarà possibile ottimizzare le campagne promozionali, identificando quali sconti e offerte hanno il maggiore impatto sulle vendite.

3. **Monitoraggio in tempo reale dei punti vendita**: I manager potranno tenere sotto controllo l'andamento di ciascun negozio, migliorando la gestione delle scorte e delle risorse umane.

4. **Gestione dei resi**: L’integrazione dei dati sui resi permetterà di calcolare le vendite nette, offrendo una visione più accurata delle performance reali di ciascun punto vendita.

5. **Interattività e navigabilità**: La possibilità di navigare tra le varie pagine e usare segnalibri e pulsanti interattivi renderà il report di facile utilizzo anche per utenti non tecnici.

### Fasi del Progetto

#### 1. Caricamento dei Dati

- **Dati delle Vendite**: Saranno caricati i file dalla cartella **DATI** (link: https://drive.google.com/drive/folders/1iYuYuvip3NwvB2LK9SAbKWZP-aZ5IObL), che contengono le informazioni relative alle vendite di diversi negozi nei vari mesi del 2014.
- **Dati Aggiuntivi**: Dalla cartella **DATI NEGOZI** verranno caricati i file con le informazioni sui negozi, sui prodotti e sulle province italiane.
  
#### 2. Trasformazione dei Dati

I dati saranno trasformati e uniti tramite la funzione **Merge di Query**, per unire le tabelle in modo appropriato, consentendo di ottenere informazioni come il **Prezzo Unitario** e la **Descrizione Prodotto** per ciascun **Prodotto_ID**.

#### 3. Creazione del Report Interattivo

Il report sarà composto da diverse pagine, ciascuna con visualizzazioni appropriate:

- **Vendite per Mese**: Una pagina che visualizza le vendite totali per ciascun mese, tenendo conto di sconti, unità vendute e prezzi.
- **Unità Vendute per Città**: Un'analisi delle unità vendute in ogni città in cui è presente un punto vendita TechMarket.
- **Dettaglio Prodotto**: Una pagina che mostra tutte le informazioni rilevanti per ogni prodotto venduto, inclusi i dati di performance.
- **Informazioni sui Negozi**: Una panoramica di ciascun negozio, unendo i dati provenienti dai file dei negozi e dalle vendite, per ottenere una visione completa delle performance per punto vendita.

#### 4. Gestione dei Resi

Saranno caricati i dati dei **resi** e verrà creata una nuova pagina che mostra una tabella in cui le vendite, escluse le transazioni di reso, vengono visualizzate per i mesi di gennaio e febbraio. Questo darà una visione più accurata delle performance nette di TechMarket.

#### 5. Navigabilità e Interattività

Il report sarà completamente **navigabile**, con pulsanti che permettono di passare da una pagina all’altra. Inoltre, verranno creati **segnalibri** per accedere rapidamente alle sezioni chiave del report.

### Conclusione

Il progetto di gestione dei punti vendita per **TechMarket S.p.A.** rappresenta un’importante opportunità per ottimizzare la gestione delle vendite e migliorare le decisioni aziendali. Il valore aggiunto è evidente nel miglioramento della visibilità sui dati, nella capacità di prendere decisioni strategiche più informate e nell'ottimizzazione delle risorse a livello di punto vendita. L'integrazione dei dati sui resi consente inoltre di ottenere una visione realistica delle vendite nette, migliorando l’accuratezza dei report e aumentando la capacità dell’azienda di adattarsi rapidamente alle variazioni del mercato.
