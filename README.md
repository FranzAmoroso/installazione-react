# React

React è una libreria JavaScript open-source utilizzata per la creazione di interfacce utente (UI) interattive e dinamiche. Sviluppata da Facebook, React è diventata una delle librerie più popolari per lo sviluppo di applicazioni web moderne.

## Configurazione

La configurazione di un progetto React coinvolge diversi passaggi, inclusi la creazione del progetto, l'installazione delle dipendenze e la configurazione di eventuali strumenti aggiuntivi.

### Installare Node.js e npm:

Prima di tutto, avere Node.js e npm installati sul sistema. Scaricabili da https://nodejs.org/.

### Creare un nuovo progetto React con Vite:

Utilizzando Vite, puoi creare un nuovo progetto React eseguendo il seguente comando:

    npm create vite@latest myAppReact --template react

Questo scaricherà e creerà un nuovo progetto React chiamato "myAppReact" utilizzando Vite come bundler.

### installare le dipendenze del progetto

Navigare nella directory del progetto 

    cd myAppReact

Installare le dipendenze dell'applicazione

    npm install

Questo installerà tutte le dipendenze del progetto elencate nel file package.json.

### Avviare l'Applicazione in Modalità Sviluppo:
Una volta completata l'installazione delle dipendenze,
dopo di che possiamo fare partire l'applicazione digitando

    npm run dev

Questo avvierà un server di sviluppo locale e aprirà l'applicazione nel browser predefinito. Puoi quindi iniziare a sviluppare la tua app React nel file `src/App.js.`

### Struttura del progetto:

La struttura di base di un'app React creata con create-react-app è simile a questa:

    nome_del_tuo_progetto/
    |-- src/
    |   |-- App.js
    |   |-- index.js
    |   |-- ...
    |-- public/
    |   |-- index.html
    |   |-- ...
    |-- node_modules/
    |-- package.json
    |-- package-lock.json (o yarn.lock se si utilizza Yarn)
    |-- ...

### Build per la produzione:

Per distribuire l'applicazione, creare una build per la produzione eseguendo:

    npm run build

Questo creerà una directory build contenente i file ottimizzati per la produzione.

### Configurare altri strumenti o librerie:

A seconda delle esigenze del tuo progetto, potresti dover configurare e integrare altri strumenti o librerie, come React Router per la gestione della navigazione, Redux per la gestione dello stato, ESLint per il linting del codice, etc.

### Altri comandi utili:

- `npm test` Esegue i test nell'applicazione.
- `npm run eject` Estrae le configurazioni interne nel progetto, per una personalizzazione avanzata. (Irreversibile)
- `npm run lint` Esegue il linting del codice utilizzando le regole specificate nel progetto. Assicurati di avere un file .eslintrc configurato se desideri personalizzare le regole di linting.
