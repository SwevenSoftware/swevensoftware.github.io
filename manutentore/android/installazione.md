---
layout: page
title: Installazione
parent: Android
grand_parent: Manuale Manutentore
nav_order: 2
---

# Setup
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
### Prerequisiti
- Android Studio
- (opzionale) Dispositivo Android

### Requisiti Hardware

- 4GB di memoria RAM
- Sistema operativo 64bit

## Installazione
### Prerequisiti
Per preparare l'ambiente di lavoro per lo sviluppo dell'applicazione mobile BlockCOVID è necessario:
1. scaricare ed installare Android Studio, disponibile al seguente link: [Android Studio](https://developer.android.com/studio);
2. scaricare l'ultima release dell'applicazione, in formato .zip, disponibile al seguente link: [BlockCOVID-Android](https://github.com/SwevenSoftware/BlockCOVID-android/releases);
3. estrarne il contenuto in una cartella qualsiasi;
4. tramite Android Studio, aprire la cartella in cui è stata estratta la release come progetto.

### APK bundle

#### Android Studio
{: .no_toc }
Android Studio offre la possibilità di realizzare un bundle `apk`
della propria applicazione direttamente all'interno dell'IDE. Questa
funzione è disponibile all'interno di ***Build > Generate signed bundle/APK***.

## Esecuzione
È possibile eseguire l'applicazione per testarne il comportamento sempre tramite Android Studio:

- Attivare la modalità debug sul proprio dispositivo Android;
- fare la build del progetto tramite Android Studio tramite ***Build > Make Project*** o la shortcut `Ctrl + F9`;
- collegare il proprio dispositivo Android al computer, autorizzando
  la lettura/scrittura di file;
- aprire la tendina ***Available devices*** in alto a destra di Android
  Studio e selezionare il proprio dispositivo;
- fare il run del progetto tramite Android Studio tramite ***Run > Run app*** o la shortcut `Ctrl + F10`.

Se non si disponesse di un dispositivo Android fisico è possibile
utilizzare l'emulatore fornito da Android Studio. Per utilizzarlo è
sufficiente selezionare il dispositivo emulato, invece che quello
fisico, dalla tendina ***Available devices***. Il resto dei passi per
l'installazione rimangono gli stessi.

{% include prev_next.liquid %}
