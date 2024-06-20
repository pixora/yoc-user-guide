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

In questa schermata l'utente customer avrà la possibilità di visualizzare i propri `vessel` registrati all'interno del sistema, navigare nella **[Tracking Page](#tracking-page)**, o nelle **[F.A.Q](#faq)** attraverso i pulsanti posti in alto.

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

In questo menu è possibile visionare le informazioni relative alla dashboard principale, device, mappa e allarmi: `Home, Devices, Map, Alarm`.

Ogni pulsante del menu reindirizzerà l'utente verso una sezione specifica di cui tratteremo in seguito. **[(Dashboard Devices)](#dashboard-devices)**, **[(Dashboard Alarms)](#dashboard-alarms)**, **[(Tracking Page)](#tracking-page)**. 

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

##  F.A.Q

In questa pagina l’utente potrà leggere le `F.A.Q` (domande frequenti), e richiedere assistenza tramite le apposite informazioni di contatto. 

<div style="margin-top:30px;">
    <img src="../assets/faq-web.png" alt="faq" width ="750">
</div>

## Logout

Cliccando sul bottone in basso a sinistra posto su tutte le schermate dell'app, l'utente potrà effettuare il Logout e verrà, quindi, riportato alla schermata di Login dove potrà inserire di nuovo le credenziali di accesso. 