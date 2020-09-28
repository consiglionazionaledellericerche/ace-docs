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

In sintesi per ogni contesto è specificato:

-  Amministratore del contesto (Ruolo) – Chi ha assegnato questo ruolo è abilitato ad assegnare tutti i ruoli del contesto ed è abilitato a condividere i ruoli del contesto ad altri contesti;

-  Gestore del contesto (Ruolo) – Chi ha assegnato questo ruolo è abilitato solo ad assegnare tutti i ruoli del contesto.

-  Il Contesto ‘SISTEMA’, che definisce i ruoli necessari al funzionamento di ACE, sarà gestibile solo dal Superutente.

Ruolo
=====
Il ruolo in ACE qualifica funzioni di tipo Istituzionali e mansioni di tipo Applicativo, come specificato al paragrafo precedente.

Ci sono poi alcuni ruoli di SISTEMA per l’amministrazione del sistema ACE:

-  SUPERUTENTE: Gestore dell’Applicazione. Abilitato a tutto;

-  ADMIN: Amministratore del Sistema. Abilitato a gestire tutte le ‘configurazioni’;

-  DEVELOPER: Ruolo di sviluppo utilizzato da applicazioni esterne ad ACE. Abilitato in lettura a tutti i dati;

Sui contesti abbiamo i ruoli che *concedono* particolari abilitazioni (come indicato prima: Ruolo Amministratore e Ruolo Gestore).

Le informazioni previste nella definizione di un Ruolo sono, oltre a descrizione e sigla:

Ruolo padre: utile alla gestione del raggruppamento dei ruoli;

L’indicazione dell’associazione del ruolo ai contesti. In questa sezione viene specificato il contesto al quale il ruolo appartiene, che può essere uno solo e deve essere indicato all'atto della creazione del Ruolo stesso.

E’ possibile inoltre specificare i Tipi entità organizzative che possono utilizzare il Ruolo ed è specificato l’utilizzo del ruolo: Assegnabile a livello globale. Questa informazione specifica se nell’associazione Persona-Ruolo-Entità organizzativa è possibile o meno assegnare il ruolo ad una persona senza specificare l’entità organizzativa. L’assenza dell’entità organizzativa in questa associazione da la possibilità all’utente (persona) di espletare il Ruolo su tutte le entità organizzative dell’Ente.

E' possibile, inoltre, rendere visibile da questa funzionalità il Ruolo ad altri contesti.

Ci sono due funzionalità di ACE che consentono, successivamente alla creazione del Ruolo, la sua assegnazione ad Utenti oppure Persone.
L'assegnazione alle persone, che avviene a cura del Gestore dei Ruoli di un Contesto, attribuisce i Ruoli a Persone ed eventuale Entità Organizzativa.
Diversa invece è l’abilitazione ‘Ruolo Utente’ (funzionalità specifica utilizzabile solo dagli Amministratori del Sistema). Questa abilitazione serve per poter assegnare un Ruolo ad un Utente che non sia una Persona fisica (riservata ad esempio alle applicazioni che interrogano ACE). Ad esempio Scrivania Digitale potrebbe interrogare ACE per avere i ruoli sia del contesto ‘Scrivania Digitale’ sia alcuni ruoli del contesto ‘Missioni’ che gli verranno resi disponibili, perché avvia flussi anche per conto di Missioni.

Il Gruppo dei Ruoli invece rappresenta una ulteriore parametrizzazione per poter gestire i Ruoli ‘Ereditati’. Ogni contesto può gestire i suoi raggruppamenti creando appunto un gruppo di ruoli che hanno caratteristiche simili. Ciò è possibile definendo dei Ruoli di tipo ‘raggruppatore’ e assegnando a questi i ruoli che ne fanno parte.
Un Gruppo risulta automaticamente condiviso ad altri contesti, quando tutti i ruoli che ne fanno parte risultano condivisi.






