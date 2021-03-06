---
layout: page
title: Utente
parent: Android App
nav_order: 1
grand_parent: Manuale Utente
---

# Utente
{: .no_toc }
<details closed markdown="block">
  <summary>
    Indice
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

## Requisiti minimi di sistema
- Dispositivo Android dotato di tecnologia RFID

# Funzionalità
## Login
L'utente può autenticarsi inserendo il proprio nome utente e la password. Queste credenziali gli saranno comunicate dell'amministratore e la password potrà essere cambiata dalla pagine utente solo dopo aver fatto il primo login.

<a href="/assets/android/app_screenshots/login.png" style="cursor: zoom-in">
<img src="/assets/android/app_screenshots/login.png" width="200">
</a>
> Click per ingrandire

## Landing Page
A login effettuato l'utente si troverà sulla pagina Home. Da questa pagina l'utente potrà accedere alle 4 pagine principali dell'app:
- Home
- Stanze
- Impostazioni
- Account

<a href="/assets/android/app_screenshots/empty_home.png" style="cursor: zoom-in">
<img src="/assets/android/app_screenshots/empty_home.png" width="200">
</a>
> Click per ingrandire

## Lista delle stanze prenotabili
Nella pagina Stanze è possibile consultare una lista di tutte le stanze aperte, con le relative informazioni:
- nome della stanza
- stanza attualmente aperta/chiusa
- orari/giorni di apertura

<a href="/assets/android/app_screenshots/user_rooms.png" style="cursor: zoom-in">
<img src="/assets/android/app_screenshots/user_rooms.png" width="200">
</a>
> Click per ingrandire

## Prenotazione postazione
Dopo aver selezionato una stanza dalla pagina Stanze, si viene portati nella pagina di selezione postazione. Qui vengono rappresentate tutte le postazioni presenti nella stanza, sotto forma di quadratini colorati: verde per una postazione prenotabile e rosso per una occupata. Per iniziare una prenotazione è sufficiente scegliere l'intervallo orario e la data desiderata per la prenotazione e cliccare una postazione. La disponibilità delle postazioni viene aggiornata automaticamente al cambiare dell'orario e della data selezionata.

<a href="/assets/android/app_screenshots/room_view.png" style="cursor: zoom-in">
<img src="/assets/android/app_screenshots/room_view.png" width="200">
</a>
> Click per ingrandire

## Conferma prenotazione
Dopo aver cliccato una postazione si verrà portati alla pagina di conferma prenotazione dove si avrà un resoconto dei dati ed un bottone per confermare la prenotazione.

<a href="/assets/android/app_screenshots/reservation.png" style="cursor: zoom-in">
<img src="/assets/android/app_screenshots/reservation.png" width="200">
</a>
> Click per ingrandire

## Account Utente
In ogni pagina è possibile accedere alla pagina account dal bottone in alto a destra, qui vengono mostrate tutte le informazioni dell'utente ed è anche possibile modificare la propria password, vedere le proprie prenotazioni attualmente attive ed effettuare il logout.

<a href="/assets/android/app_screenshots/user_account.png" style="cursor: zoom-in">
<img src="/assets/android/app_screenshots/user_account.png" width="200">
</a>
> Click per ingrandire

## Modifica password
Da questa pagina, accessibile dalla propria pagina Account, si può cambiare la propria password inserendo la vecchia password e la nuova password, ripetuta due volte.

<a href="/assets/android/app_screenshots/password.png" style="cursor: zoom-in">
<img src="/assets/android/app_screenshots/password.png" width="200">
</a>
> Click per ingrandire

## Lista prenotazione
Da questa pagina, accessibile dalla propria pagina Account, si può consultare una lista delle prenotazioni effettuate con i loro rispettivi dati:
- l'id della postazione
- l'orario e la data della prenotazione
- la stanza della postazione

<a href="/assets/android/app_screenshots/reservations_list.png" style="cursor: zoom-in">
<img src="/assets/android/app_screenshots/reservations_list.png" width="200">
</a>
> Click per ingrandire

## Modifica prenotazione
Selezionando una prenotazione si entra nella pagina di modifica prenotazione, che consente di cambiare tutti i dati di una prenotazione già effettuata o di eliminarla.

<a href="/assets/android/app_screenshots/edit_reservation.png" style="cursor: zoom-in">
<img src="/assets/android/app_screenshots/edit_reservation.png" width="200">
</a>
> Click per ingrandire

## Scansione Tag RFID
Il lettore RFID è sempre acceso. Quando un tag viene letto si verrà portati alla pagina Home che si aggiornerà automaticamente con i dati della postazione scannerizzata, tra cui:
- la disponibilità
- l'eventuale momento in cui tornerà disponibile
- lo stato di pulizia

<a href="/assets/android/app_screenshots/rfid_scan.png" style="cursor: zoom-in">
<img src="/assets/android/app_screenshots/rfid_scan.png" width="200">
</a>
> Click per ingrandire

## Prenotare tramite Tag RFID
Dopo aver scansionato una postazione è possibile prenotarla cliccando sul pulsante "Prenota". In questo modo si verrà portati ad una pagina dove si potranno inserire l'orario e la data della prenotazione per la postazione scannerizzata.

<a href="/assets/android/app_screenshots/rfid_reservation.png" style="cursor: zoom-in">
<img src="/assets/android/app_screenshots/rfid_reservation.png" width="200">
</a>
> Click per ingrandire

## Iniziare una prenotazione
Una volta arrivato alla postazione prenotata all'interno dell'orario prestabilito, scannerizzando il tag RFID sarà possibile iniziare effettivamente la prenotazione cliccando sul pulsante "Inizia".

<a href="/assets/android/app_screenshots/reservation_start.png" style="cursor: zoom-in">
<img src="/assets/android/app_screenshots/reservation_start.png" width="200">
</a>
> Click per ingrandire

## Finire una prenotazione
Nel momento in cui si sta per lasciare la postazione, scannerizzando il tag RFID sarà possibile terminare effettivamente la prenotazione cliccando sul pulsante "Finisci". Se la postazione dovesse essere stata pulita autonomamente è possibile spuntare il pulsante "Pulito autonomamente" e poi cliccare su "Finisci". Una prenotazione verrà automaticamente finita una volta finito l'intervallo di tempo prestabilito ma sarà ancora possibile indicare se è stata pulita autonomamente.

<a href="/assets/android/app_screenshots/reservation_end.png" style="cursor: zoom-in">
<img src="/assets/android/app_screenshots/reservation_end.png" width="200">
</a>
> Click per ingrandire

## Notifica di fine prenotazione
All'orario in cui la prenotazione finisce, l'utente riceverà una notifica per ricordargli di terminare la prenotazione

<a href="/assets/android/app_screenshots/notification.png" style="cursor: zoom-in">
<img src="/assets/android/app_screenshots/notification.png" width="400">
</a>
> Click per ingrandire

{% include prev_next.liquid %}