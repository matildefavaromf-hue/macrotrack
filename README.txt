MACROTRACK — versione personale per iPhone

CONTENUTO
- Diario con cinque pasti
- Obiettivi macro manuali, mai modificati automaticamente
- Inserimento alimenti in grammi e macro per 100 g
- Ricerca tramite codice a barre nel database Open Food Facts
- Ricette salvate a partire dagli ingredienti registrati nel diario
- Backup e ripristino JSON
- Salvataggio locale nel browser

IMPORTANTE
Questa è una prima versione di base. Il campo codice a barre cerca il prodotto online tramite Open Food Facts; non usa ancora la fotocamera per leggere il codice. Le ricette vengono create dagli ingredienti selezionati nel diario del giorno e vanno considerate una funzione iniziale da migliorare. I dati restano nel browser del dispositivo: esporta regolarmente un backup.

COME METTERLA SULL'IPHONE GRATIS
1. Da un computer, crea un account GitHub gratuito se non ne hai già uno.
2. Crea un nuovo repository pubblico chiamato macrotrack (i dati personali NON sono nel repository: sono salvati nel browser).
3. Carica index.html, manifest.json e sw.js nella radice del repository.
4. In GitHub apri Settings > Pages, scegli Deploy from a branch, seleziona main e /(root), poi Save.
5. Attendi che GitHub Pages mostri l'indirizzo HTTPS del sito.
6. Apri quell'indirizzo in Safari sul tuo iPhone.
7. Premi Condividi > Aggiungi alla schermata Home > Aggiungi.

Dopo l'installazione, apri sempre l'icona MacroTrack. Per il primo caricamento e la ricerca dei codici a barre serve una connessione internet. Non cancellare i dati del sito in Safari, altrimenti potresti perdere il diario; usa la funzione Esporta backup.

PRIVACY
I dati del diario e le ricette sono salvati nel localStorage del browser sul dispositivo. La ricerca del codice a barre invia il codice a Open Food Facts. Non inserire informazioni sensibili.
