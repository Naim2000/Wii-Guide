---
title: "Updating Wii Menu to v4.3"
---

{% include toc title="Table of Contents" %}

Se hai bisogno di qualsiasi informazione riguardante questo tutorial, entra nel [server discord di RiiConnect24 ](https://discord.gg/rc24)(raccomandato) oppure [scrivici una mail a support@riconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

This tutorial will explain how to update your Wii Menu to version 4.3, as you can no longer use the updater built into the Wii Menu since the servers are no longer up.

#### Di cosa hai bisogno
* Una scheda SD o chiavetta USB
* A computer with Windows on it
* [NUS Downloader](https://github.com/WiiDatabase/nusdownloader/releases/latest)
* [Wii Mod Lite](https://oscwii.org/library/app/WiiModLite)

If you don't have a Windows computer, please join [the RiiConnect24 Discord server](https://discord.gg/rc24) (recommended) or [e-mail us at support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

#### Istruzioni

##### Sezione 1 - Scaricare

Your Wii must be modded in order to perform this. If it isn't, then it's best to follow [the guide](get-started) first before doing this.
{: .notice--info}

To protect against bricks, [make sure you install Priiloader](priiloader). Also, install [BootMii](bootmii) (as Boot2 if you have an early Wii, otherwise IOS). Installare la protezione dai blocchi e seguire correttamente la guida ti tiene al sicuro da blocchi. NON CONTINUARE FINO A CHE NON HAI PRIILOADER E BOOTMII INSTALLATI!
{: .notice--danger}

1. Extract the .zip file for NUS Downloader vWii and open the application.
2. Go to `Database...` > `System` > `0000000100000002 - System Menu` and select the version corresponding to your region as shown in the table below.
3. Make sure `Pack WAD` is checked.
4. Press `Start NUS Download!`.
5. Open the `titles` -> `0000000100000002` -> (Wii Menu version) and copy the .wad file to a folder called `wad` on your SD Card or USB drive.
6. (If you have [RiiConnect24](riiconnect24), you can skip this step) Repeat steps 2-5 with `IOS` -> `0000000100000050 - IOS80` -> `Latest Version`.

| Region | Wii Menu version |
| ------ | ---------------- |
| Japan  | v512 (4.3J)      |
| USA    | v513 (4.3U)      |
| Europe | v514 (4.3E)      |
| Korea  | v518 (4.3K)      |

##### Sezione 2 - Installare

Si usa il +Control Pad per usare questo strumento.
{: .notice--info}

1. Metti la tua scheda SD o il tuo dispositivo USB nella tua WIi.
2. Carica il Canale Homebrew sulla tua Wii.
3. Avvia Wii Mod Lite.
4. Usando ul tuo +Control Pad sul telecomando Wii, naviga su `WAD Manager`, e poi naviga sulla cartella `wad`.
5. Press A to install the Wii Menu WAD (and the IOS80 WAD if necessary).
6. Dopo che ha installato con successo, premi il tasto HOME per tornare all'Hombrew Channel.