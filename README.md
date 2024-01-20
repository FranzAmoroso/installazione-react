# React
React è una libreria JavaScript open-source utilizzata per la creazione di interfacce utente (UI) interattive e dinamiche. Sviluppata da Facebook, React è diventata una delle librerie più popolari per lo sviluppo di applicazioni web moderne.
## Configurazione
Per utilizzare React, è necessario incorporare la libreria nel progetto, tramite npm (Node Package Manager).

Nel terminale dopo aver installato Node.js, eseguiamo il comando nel terminale:

    npm create vite@latest myAppReact --template react

Questo scaricherà e creerà un nuovo progetto React chiamato "myAppReact" utilizzando Vite come bundler.
### installare le dipendenze del progetto
Navigare nella cartella del progetto appena creato tramite il terminale e digitare:

    npm install

Questo installerà tutte le dipendenze del progetto elencate nel file package.json.
Una volta completata l'installazione delle dipendenze,
dopo di che possiamo fare partire l'applicazione digitando

    npm run dev

Questo avvierà un server di sviluppo locale e aprirà l'applicazione nel browser predefinito. Puoi quindi iniziare a sviluppare la tua app React nel file `src/App.js.`