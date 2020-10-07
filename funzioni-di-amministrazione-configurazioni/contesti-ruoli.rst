Contesto
========

I contesti rappresentano un insieme di ruoli, aventi caratteristiche simili e per questo utilizzabili e accessibile a seconda del contesto di appartenenza. 
Ogni contesto resta autonomamente gestito, dal relativo Amministratore, per la definizione dei ruoli che vi appartengono e per le abilitazioni di visibilità consesse. 

I contesti raggruppano fondamentalmente tre tipi di ruoli e sono individuati univocamente dalla Sigla del contesto:

- Contesto di Sistema

- Contesto Istituzionale (che raggruppa separatamente Ruoli istituzionale e Ruoli istituzionali non in Albo)

- Contesti Applicativi

Il contesto di Sistema e i contesti  Istituzionali (per ruoli istituzionali inseriti o meno nell’Albo dell’ente) vengono definiti e gestiti dall'Amministratore di ACE, Superutente, perché rappresentano ruoli ufficiali non modificabili. I contesti invece ‘applicativi’ includono specifiche esigenze di applicazioni dell'ente che si integrano ad ACE ed utilizzano le informazioni centralizzate per completare i propri processi amministrativi e gestionali.
Tutti i Ruoli, infine, sono assegnati ad Utenti oppure ad Utenti/Persone dell'applicazione per poter esercitare le funzioni relative.

I Contesti vengono gestiti esclusivamente dall'Amministratore di ACE che si occupa anche di assegnare ad ognuno di essi:
- Ruolo Amministratore del contesto;
- Gestore del Contesto.

All’interno di un contesto vengono definiti i ruoli che ne fanno parte, esclusivamente dall'Amministratore del contesto, che si occupa anche di renderli visibili, alcuni o tutti, eventualmente ad altri contesti che hanno necessità di consultarli.
Un ruolo può essere associato soltanto ad un contesto, quindi, ed essere reso visibile ad altri contesti in visualizzazione.

In sintesi per ogni contesto è possibile consultare:

-  Ruoli Generici . Tutti i ruoli applicativi che sono stati creati e associati al contesto da parte dell'Amministratore;

-  Amministratore del contesto (Ruolo) – Chi ha assegnato questo ruolo è abilitato a gestire i ruoli del contesto, ad assegnare tutti i ruoli del contesto ed è abilitato a condividere i ruoli del contesto ad altri contesti (attraverso la funzione dei ruoli);

-  Gestore del contesto (Ruolo) – Chi ha assegnato questo ruolo è abilitato solo ad assegnare tutti i ruoli del contesto di appartenenza attraverso la funzione di 'assegnazione ruoli'. Il Gestore non accede all'anagrafica Contesti e Ruoli.

-  Il Contesto ‘SISTEMA’, che definisce i ruoli necessari al funzionamento di ACE, non è modificabile da applicazione.

Ruolo
=====
Il ruolo in ACE qualifica funzioni di tipo Istituzionali e mansioni di tipo Applicativo, come specificato al paragrafo precedente.

Ci sono poi alcuni ruoli di SISTEMA per l’amministrazione di ACE che hanno funzionalità predefinite:

-  SUPERUTENTE: Gestore dell’Applicazione. Abilitato a tutto;

-  ADMIN: Amministratore del Sistema. Abilitato a gestire tutte le ‘configurazioni’;

-  DEVELOPER: Ruolo di sviluppo utilizzato da applicazioni esterne ad ACE. Abilitato in lettura a tutti i dati;

-  USERS-VIEWER: Ruolo che consente la visualizzazione dei dati anagrafici (Persone, Appartenenza);

-  SEDI-VIEWER: Ruolo per la visualizzazione di Entità organizzative e gerarchie;

-  Gestione Ufficio Sedi: Ruolo per la gestione delle Sedi e la loro assegnazione alla Gerarchia Sedi (Gerarchia scientifica e Amministrazione Centrale);

-  Gestione RSU: Ruolo per la creazione di sedi RSU e gestione della gerarchia RSU;

-  Supervisione Entità Locali: Ruolo per la gestione di indirizzi ed entità locali.

Sui contesti abbiamo i ruoli che *concedono* particolari abilitazioni (come indicato prima: Ruolo Amministratore e Ruolo Gestore).

Le informazioni previste nella definizione di un Ruolo sono, oltre a descrizione e sigla:

-  Associazione obbligatoria del ruolo al contesto di appartenenza. Questo essere indicato all'atto della creazione del Ruolo stesso.

-  Tipologia. In questo campo viene specificato il tipo di ruolo:
  -  Gestore,
  -  Amministratore, 
  -  Generico (Utente Applicativo)
oppure è possibile specificare un tipo di Ruolo di sistema solo se chi opera è un'utente di amministrazione. 

Tra le tipologie si può specificare anche il ruolo di tipo 'Gruppo'. In questo caso bisogna specificare i ruoli che fanno parte del gruppo.
Il Gruppo dei Ruoli rappresenta una ulteriore parametrizzazione per poter gestire i Ruoli ‘Ereditati’. Ogni contesto può gestire i suoi raggruppamenti creando appunto un gruppo di ruoli che hanno caratteristiche simili. 
Un Gruppo risulta automaticamente condiviso ad altri contesti, quando tutti i ruoli che ne fanno parte risultano condivisi.

E’ possibile inoltre, per il ruolo di tipo Utente Applicativo, specificare i Tipi entità organizzative che possono utilizzare il Ruolo ed è specificato l’utilizzo del ruolo: Assegnabile a livello globale. Questa informazione specifica se nell’associazione Persona-Ruolo-Entità organizzativa è possibile o meno assegnare il ruolo ad una persona senza specificare l’entità organizzativa. L’assenza dell’entità organizzativa in questa associazione da la possibilità all’utente (persona) di espletare il Ruolo su tutte le entità organizzative dell’Ente.

E' possibile, infine, rendere visibile da questa funzionalità il Ruolo ad altri contesti. In questo caso il contesto a cui è condiviso il ruolo, può assegnare anche questo insieme agli altri ruolo del contesto di cui si è Manager o Gestore.

Ci sono due funzionalità di ACE che consentono, successivamente alla creazione del Ruolo, la sua assegnazione ad Utenti oppure Persone.
L'assegnazione alle persone, che avviene a cura del Gestore dei Ruoli di un Contesto, attribuisce i Ruoli a Persone ed eventuale Entità Organizzativa.
Diversa invece è l’abilitazione ‘Ruolo Utente’ (funzionalità specifica utilizzabile solo dagli Amministratori del Sistema). Questa abilitazione serve per poter assegnare un Ruolo ad un Utente che non sia una Persona fisica (riservata ad esempio alle applicazioni che interrogano ACE). 








