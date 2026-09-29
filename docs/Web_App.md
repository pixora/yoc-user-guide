![Logo](./assets/logo2.png "Logo")

# Welcome to Yacht On Cloud user guide.

## Login Screen
Per effettuare il log-in è obbligatorio l’inserimento nei form dei seguenti campi: 

* `Tenant`: Nome identificativo dello specifico tenant abilitato.
* `Email`: La propria e-mail che rappresenta la chiave univoca dell’utente.
* `Password`: La propria password.


<div style="margin-top: 30px;">
    <img src="..\assets\login-web-app.png" alt="Login Screen" width="250">
</div>

Dopo aver riempito i campi sarà possibile cliccare sul tasto `Log In`.

In caso di credenziali errate l'utente verrà informato con un messaggio di errore.

In caso di credenziali corrette l'utente passerà alla prossima schermata.

## Vessel Selection Page

In questa schermata l'utente customer avrà la possibilità di visualizzare i propri `vessel` registrati all'interno del sistema, e navigare nella **[Tracking Page](#tracking-page)** attraverso il pulsante posto in alto.

<div style="margin-top: 30px;">
    <img src="../assets/vessels-web-app.png" alt="Vessel Screen" width="750">
</div>

Il bollino `verde` o `rosso` delle card rappresentanti i vessel indicherà rispettivamente una imbarcazione online (raggiungibile) o offline (non raggiungibile). 

Cliccando sul tasto `Registry`, apparirà la card che contiene le informazioni principali del vessel. E' possibile, inoltre, poter vedere in anteprima e scaricare un file che contiene le informazioni dei relativi sensori.

<div style="margin-top: 30px;">
    <img src="../assets/registry-vessel.png" alt="Vessel registry" width="750">
</div>

Il tasto `Explore`, invece, reindirizza alla pagina **Vessel Dashboard**.

## Vessel Dashboard

<div style="margin-bottom: 30px;"></div>

<div>
    <img src="..\assets\vessel-home-web-app.png" alt="Home Screen" width="750">
</div>

<div style="margin-bottom: 30px;"></div>

### 1. Boat Info

La dashboard si presenta in questo modo. 

In alto troveremo le informazioni riguardanti l'imbarcazione: 

* Il nome e la tipologia della propria imbarcazione: `Yatch`, `Catamarano` , `Dinghi` o `Sailboat`.
* Lo stato dell'imbarcazione: Se essa è raggiungibile o meno: `Attivo` o `Non attivo`.
* Se risulta armata oppure no: `Armed` o `Disarmed`.
* Se risulta ancorata oppure no: `Anchored` o `Unanchored`.

Lo stato di entrambe le operazioni di ormeggio sono modificabili cliccando sul tasto corrispondente.

<div style="text-align: center; margin-top:30px;">
    <img src="..\assets\barra-descrittiva.png" alt="name and type" width="275">
    <img src="../assets/barra-descrittiva2.png" alt="Status ship" width="243" style="display: inline-block; margin-left: 30px;">
</div>


L'immagine centrale cambierà in base alla `tipologia` di imbarcazione di cui siamo in possesso. 

In caso non sia presente un evento allarmante riguardante l'imbarcazione, o la barca risulta disarmata prima che sia scattato l'allarme, lo sfondo apparirà `blu` e le icone relative ad esse `verdi`.

In caso sia presente un evento allarmante riguardante l'imbarcazione che risulta armata, lo sfondo alle spalle sarà `rosso`, così come le icone relative ad esse.

<div style="text-align: center; margin-top:30px;">
    <img src="..\assets\vessel-non-allarme.png" alt="Not Alarmed Ship" width="250">
    <img src="../assets/vessel-in-allarme.png" alt="Alarmed Ship" width="243" style="display: inline-block; margin-left: 30px;">
</div>

Lungo la destra è presente un menù laterale con 3 bottoni che ci consentono di:

 * Far apparire la card relativa allo stato dei motori se si clicca sul tasto `Engines`.
 * Far apparire la card relativa ai valori dei sensori ambientali ed allo stato degli allarmi se si clicca sul tasto `Alarms`.

<div style="text-align: center; margin-top:30px;">
    <img src="../assets/engine-alarms-card.png" alt="Armed Disarmed" width="750">
</div>

* Far apparire la card relativa alle info del vessel se si clicca sul tasto `Registry`.

<div style="text-align: center; margin-top:30px; margin-bottom:30px;">
    <img src="../assets/registry.png" alt="Armed Disarmed" width="350">
</div>


<div style="margin-bottom: 50px;"></div>

### 2. Menu Rapido

Lungo la sinistra dello schermo, invece, è disponibile un menù rapido.

<div style="text-align: center; margin-top:30px; margin-bottom:30px;">
    <img src="../assets/menu-rapido.png" alt="Armed Disarmed" width="50">
</div>

In questo menu è possibile visionare le informazioni relative alla dashboard principale, device, mappa e allarmi: `Home, Devices, Map, Alarm, Maintenance, Routes`.

Ogni pulsante del menu reindirizzerà l'utente verso una sezione specifica di cui tratteremo in seguito. **[(Dashboard Devices)](#dashboard-devices)**, **[(Tracking Page)](#tracking-page)**, **[(Dashboard Alarms)](#dashboard-alarms)**, **[(Maintenance)](#maintenance)**, **[(Routes)](#routes)**.

## Dashboard Devices

Per poter visualizzare i dispositivi disponibili per la nostra imbarcazione è necessario utilizzare il `Menu Rapido` per andare ad analizzare la macrocategoria di dispositivi a cui siamo interessati, cliccando sul pulsante "Devices" (raffigurato da un icona apposita) che farà apparire una schermata con tutti i dispositivi.

Cliccando sull'icona per visualizzare tutti i dispositivi avremo questa schermata.


<div style="text-align:center; margin-top: 30px;">
    <img src="../assets/devices.png" alt="Devices1" width="750" style="display: inline-block;">
</div>

<div style="margin-top: 50px;"></div>

Ogni riga che troviamo in questa schermata corrisponde ad un device, ogni device ha la sua pagina con i relativi dettagli.

Accanto a ciascun dispositivo compare anche un pulsante che consentirà di accedere alla sezione *Telemetries* per la visualizzazione tutte le telemetrie per una più completa ricerca. **[(Vedi Telemetries Card)](#2-telemetries-card)**.

Infine è possibile filtrare la lista di dispositivi presenti per tipo di dispositivo.

*Questi funzionamenti sono uguali per tutti i dispositivi.*

### 1. Device infos Card

Cliccando sul pulsante `Device infos`, apparirà la card *info device* che serve per consultare le informazioni di un determinato dispositivo.

E' costituita da una coppia chiave-valore che consente di poter avere dettagli più precisi circa le caratteristiche del dispositivo, come ad esempio la temperatura che, nel dispositivo di cui sotto, è espressa in gradi Celsius.

<div style="text-align: center; margin-top:30px; margin-bottom:70px">
    <img src="../assets/device-info.png" alt="device-info" width ="550">
</div>


### 2. Telemetries Card

Cliccando sul pulsante `Telemetries` apparirà la card *Telemetry* che serve per monitorare i dati dei dispositivi.

<div style="margin-top:30px;">
    <img src="../assets/telemetry-card.png" alt="telemtry-card" width ="550">
</div>

* **Key** = Rappresenta il dato.
* **Value** = Rappresenta il valore del dato.
* **Timestamp** = Rappresenta la marca temporale che accerta l'avvenimento dell'ultimo evento.
 * **Graphic** = Rappresenta un grafico delle ultime telemetrie di un dato.

 Il pulsante `Graphics` farà apparire una card che rappresenta visivamente le ultime telemetrie durante un arco temporale.

 <div style="margin-top:30px; margin-bottom:70px;">
    <img src="../assets/grafico-telemetries.png" alt="telemtry-graphic" width ="750">
</div>

Oltre alla visualizzazione di default del grafico, è possibile impostare dei filtri per avere un grafico personalizzato.

##  Dashboard Alarms

Dal `Menu Rapido` è possibile, cliccando sull'apposita icona (rappresentata da una **campanella**), visualizzare la schermata relativa agli allarmi.

Dalla dashboard possiamo capire quale dispositivo ha fatto scattare un allarme indicando data e orario, il tipo di allarme, la gravità ed il suo stato.


<div style="margin-top:30px;">
    <img src="../assets/schermata-allarmi.png" alt="Alarm Screen" width ="800">
</div>

E' disponibile la funzionalità che consente di poter applicare dei filtri per ottenere una lista di allarmi personalizzata impostando un data range, tipo e stato di allarme. 

Vi è la possibilità, cliccando sul bottone apposito, di andare a visualizzare le registrazioni delle telecamere durante gli allarmi.

### 1. Registrazioni

Al momento della ricezione di un allarme, le telecamere inizieranno a registrare. Il sistema consente di poter visualizzare i video registrati.


<div style="margin-top:30px;">
    <img src="../assets/allarme-registrazione.png" alt="Alarm Screen" width ="800">
</div>

Lungo il lato sinistro della schermata è possibile visualizzare la lista delle telecamere disponibili, al cui interno è possibile consultare il video registrato durante l'allarme, tagliato in vari frammenti.

## Tracking Page

All'interno del `Menu rapido` è possibile, cliccando sull'apposita icona (rappresentata da una **Mappa**), il tracking in tempo reale su una mappa della propria imbarcazione.

<div style="text-align:center; margin-top:30px;">
    <img src="../assets/map.png" alt="Mappa" width ="650">
</div>

Cliccando sull'icona delle impostazioni sarà possibile vedere i vessel online, quelli offline o entrambi.

## Maintenance

Dal `Menu Rapido` è possibile, cliccando sull'apposita icona (rappresentata da una **chiave inglese**), accedere alla schermata *Maintenance*, che elenca tutte le manutenzioni programmate per l'imbarcazione.

<div style="margin-top:30px;">
    <img src="../assets/maintenance1-web.png" alt="Maintenance" width ="800">
</div>

Per ogni manutenzione presente in elenco vengono mostrate le seguenti informazioni: `Title` (nome della manutenzione), `Start` (data e ora di inizio), `Duration (min)` (durata prevista in minuti), `Priority` (priorità) e `State` (stato: `SCHEDULED`, `IN_PROGRESS`, `COMPLETED`, ecc.).

Nella colonna `Actions` sono disponibili due pulsanti per ciascuna riga: l'icona della `matita` per modificare la manutenzione e l'icona del `cestino` per eliminarla. In basso è presente un sistema di paginazione per scorrere l'elenco quando le manutenzioni sono numerose.

### 1. Creazione di una Manutenzione

Cliccando sul pulsante `+ New` in alto a destra si apre la finestra modale *New event*, che consente di creare una nuova manutenzione.

<div style="margin-top:30px;">
    <img src="../assets/maintenance2-web.png" alt="New event" width ="550">
</div>

Nella finestra è possibile compilare i seguenti campi:

* `Title`: Nome identificativo della manutenzione.
* `Description`: Descrizione libera della manutenzione da svolgere.
* `Start date and time`: Data e ora di inizio pianificata.
* `Duration (minutes)`: Durata prevista, espressa in minuti.
* `Priority`: Priorità della manutenzione (es. Low, Medium, High).
* `State`: Stato della manutenzione, impostato di default su `SCHEDULED` in fase di creazione.

I destinatari delle notifiche relative alla manutenzione vengono configurati automaticamente dal sistema, come indicato nell'apposita nota presente nella finestra.

Al termine della compilazione è possibile cliccare su `Save` per confermare la creazione, oppure su `Cancel` per annullare l'operazione.

### 2. Modifica di una Manutenzione

Cliccando sull'icona della `matita` in corrispondenza di una manutenzione già presente in elenco, si apre la finestra modale *Edit event*, che consente di consultare e modificare tutti i campi inseriti in fase di creazione, incluso lo `State` della manutenzione.

<div style="margin-top:30px;">
    <img src="../assets/maintenance3-web.png" alt="Edit event" width ="550">
</div>

In questa finestra è inoltre presente la sezione `Notifications`, che riepiloga il canale utilizzato per l'invio del promemoria (`Channel`, es. EMAIL), l'anticipo con cui verrà notificato rispetto all'orario di inizio (`Advance`, es. 60 minuti prima) e gli eventuali destinatari configurati (`Recipients`).

Anche in questa schermata è possibile confermare le modifiche tramite il pulsante `Save`, oppure annullarle tramite `Cancel`.

## Routes

Dal `Menu Rapido` è possibile, cliccando sull'apposita icona, accedere alla schermata *Routes*, che elenca tutte le rotte percorse dall'imbarcazione.

<div style="margin-top:30px;">
    <img src="../assets/routes-web.png" alt="Routes" width ="800">
</div>

In alto sono disponibili i filtri `From` e `To`, che consentono di impostare un intervallo temporale e restringere l'elenco delle rotte cliccando sul pulsante `Filter`; il pulsante `Clear` rimuove i filtri applicati.

Per ogni rotta presente in elenco vengono mostrate le seguenti informazioni: `Start` (data e ora di partenza), `End` (data e ora di arrivo), `Distance (Mi)` (distanza percorsa, espressa in miglia), `Duration` (durata del tragitto), `Avg speed (kn)` (velocità media, espressa in nodi) e `Fuel (lt)` (consumo di carburante, espresso in litri).

Nella colonna `Actions` è disponibile l'icona a forma di `occhio`, che consente di visualizzare i dettagli della rotta selezionata.

## Logout

Cliccando sul bottone in basso a sinistra posto su tutte le schermate dell'app, l'utente potrà effettuare il Logout e verrà, quindi, riportato alla schermata di Login dove potrà inserire di nuovo le credenziali di accesso. 