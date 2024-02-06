# Shopping List App

Questa applicazione Flutter funge da lista della spesa digitale con integrazione Firebase per il backend. Gli utenti possono gestire i loro articoli di spesa, categorizzarli e aggiungere nuovi articoli alla loro lista.

## Funzionalità

- **Integrazione Firebase**: Utilizza Firebase Firestore per l'archiviazione e il recupero dei dati relativi alla lista della spesa.
- **Classi Modello**: Include classi modello come `GroceryItem` e `Category` per rappresentare gli articoli di spesa e le relative categorie.
- **Schermate e Navigazione**: Due schermate principali: `GroceryList` per visualizzare la lista della spesa e `NewItem` per aggiungere nuovi articoli. La navigazione tra le schermate avviene tramite il `Navigator` di Flutter.
- **Aggiunta di Nuovi Articoli**: Gli utenti possono inserire il nome, la quantità e la categoria dei nuovi articoli di spesa nella schermata `NewItem`. I dati vengono quindi inviati a Firebase per l'archiviazione.
- **Visualizzazione della Lista della Spesa**: La schermata `GroceryList` recupera gli articoli di spesa da Firebase e li visualizza. Gli utenti possono rimuovere gli articoli dalla lista facendo scorrere l'elemento da sinistra a destra.
- **Gestione degli Errori**: L'app gestisce gli errori di rete e visualizza messaggi appropriati agli utenti in caso di problemi nel recupero dei dati.

## Per Iniziare

1. Clona il repository sul tuo computer locale.
2. Assicurati di avere Flutter installato e configurato sul tuo ambiente di sviluppo.
3. Configura Firebase Firestore e sostituisci i dettagli della configurazione Firebase nel codice con i tuoi.
4. Esegui l'app su un emulatore o su un dispositivo fisico.

## Miglioramenti Futuri

- Aggiungi funzionalità per modificare gli articoli esistenti.
- Implementa l'autenticazione e l'autorizzazione degli utenti.
- Introduci notifiche in tempo reale utilizzando Firebase Cloud Messaging.

## Collaboratori

- [Matteo Lanci](https://github.com/MatteoLanci)

Sentiti libero di contribuire al progetto inviando pull request o segnalando problemi!
