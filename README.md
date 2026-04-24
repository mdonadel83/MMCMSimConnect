<p align="center">
  <img src="https://www.mmcmracing.it/wp-content/uploads/2024/03/cropped-mmcmracing_trasp-1-e1711745622868.png" alt="MMCM Racing" width="200">
</p>

<h1 align="center">🏎️ MMCM SimConnect v1.9.2</h1>

<p align="center">
  <strong>Plugin SimHub per Assetto Corsa Competizione e Assetto Corsa EVO</strong><br>
  Assistente di gara con ingegnere di pista virtuale a comandi vocali
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.9.2-red?style=flat-square" alt="Version">
  <img src="https://img.shields.io/badge/ACC-✅%20Supportato-2ecc71?style=flat-square" alt="ACC">
  <img src="https://img.shields.io/badge/AC%20EVO-🧪%20Sperimentale-f4a623?style=flat-square" alt="EVO">
  <img src="https://img.shields.io/badge/SimHub-9.x-blue?style=flat-square" alt="SimHub">
  <img src="https://img.shields.io/badge/Windows-10%2F11-0078d4?style=flat-square" alt="Windows">
</p>

---

> 🇮🇹 **Italiano** | [🇬🇧 English](#-english-version)

---

## 🆕 Novità v1.9.2 — Coach Proattivo EVO migliorato

Il **Coach Proattivo** per Assetto Corsa EVO è stato profondamente revisionato per offrire avvisi più precisi, tempestivi e utili durante la gara. Ora ti parla quando serve davvero, con i dati corretti.

### 🔧 Cosa è cambiato

| Area | Miglioramento |
|------|---------------|
| 🛞 **Usura freni** | Calcolo corretto dell'usura pad/dischi su tutte le auto EVO. Sistema auto-calibrante che si adatta a ogni vettura senza configurazione manuale. Niente più falsi allarmi al rientro dai box. |
| 🚧 **Danni carrozzeria** | Scala di lettura corretta per scocca e sospensioni. Mappatura zone left/right verificata sul campo. Le percentuali ora corrispondono al danno reale. |
| 🔧 **Alert sospensioni** | Nuovo: avviso vocale dedicato quando una sospensione è danneggiata, con soglia indipendente (più sensibile rispetto al body — perché una sospensione compromette subito la guidabilità). |
| 🚦 **Pit speeding** | Calcolo del delta di velocità completamente riscritto. Ora ti dice esattamente di quanti km/h stai sforando il limite, in tempo reale. |
| ⚙️ **Engine Map** | Tre alert distinti: avviso quali-map a inizio gara, avviso mappa aggressiva con carburante basso, promemoria di scalare a fine stint. Riconosce più nomi di mappe (push, max, attack, qualifying, level alti). |

### 🎯 Soglie configurabili

Tutte le nuove soglie del coach sono regolabili dal pannello impostazioni del plugin in SimHub, sotto "Impostazioni avanzate":
- Soglia avviso danno carrozzeria
- Soglia avviso danno sospensione
- Tolleranza pit-speeding (km/h)
- Soglia carburante residuo per alert mappa
- Soglia giri rimanenti per fine stint

### 🐛 Bug risolti

- Risolto: il coach annunciava "pad al 3%" appena usciti dai box su qualsiasi auto EVO
- Risolto: percentuali danno errate (24% invece del 2.4% reale)
- Risolto: alert pit-speeding mai attivato per saturazione del valore raw del sim
- Risolto: zone danno laterali invertite (sinistra/destra)
- Risolto: alert mappa motore non riconoscevano le denominazioni più comuni in EVO

---

## 🆕 v1.9 — Ingegnere di Pista Virtuale

Parla con il tuo ingegnere durante la gara. Chiedi gap, carburante, gomme, posizione e strategia usando solo la voce. Risponde in tempo reale con i dati dalla telemetria, come un vero team radio.

### Come funziona

```
Tu:         "Ingegnere"
Ingegnere:  🔊 *beep* (in ascolto, hai 5 secondi)
Tu:         "Gap dal primo"
Ingegnere:  "Rossi davanti, 2 secondi e 3. Dal leader, 8 secondi.
             Bene, mantieni il ritmo, vai vai vai"
```

**Due modi per attivare:**
- **Wake Word** — dì "ingegnere" e poi il comando
- **Push-to-Talk** — premi un tasto (mappabile su volante) e poi parla
- **Entrambi** — usa il metodo che preferisci

### 🎤 Comandi vocali generali (ACC + EVO)

| Categoria | Cosa dici | Risposta |
|-----------|-----------|----------|
| **Gap** | `gap` · `distacco` | Gap completo: davanti, dietro, leader |
| | `davanti` · `gap davanti` · `chi ho davanti` | Gap dal pilota davanti |
| | `dietro` · `gap dietro` · `chi ho dietro` | Gap dal pilota dietro |
| | `gap dal primo` · `gap leader` · `distacco dal primo` | Distacco dal leader |
| **Passo** | `passo` · `tempi` · `media giri` · `come vado` | Ultimo giro, miglior giro, confronto |
| **Carburante** | `carburante` · `benzina` · `fuel` · `autonomia` | Litri, consumo/giro, autonomia |
| | `strategia` · `pit stop` | + calcolo se basta per finire |
| **Gomme** | `gomme` · `pressioni` · `stato gomme` | Pressioni 4 ruote |
| | `temperature gomme` | Pressioni + temperature |
| **Posizione** | `posizione` · `dove sono` · `classifica` | Posizione, chi è davanti/dietro |
| **Meteo** | `meteo` · `piove` · `condizioni pista` · `grip` | Condizioni e grip pista |
| **Report** | `situazione` · `report` · `dammi tutto` | Tutto insieme |

### 🧪 Comandi vocali extra solo per AC EVO

Su Assetto Corsa EVO sono disponibili comandi aggiuntivi per i sistemi specifici della vettura:

| Categoria | Cosa dici | Risposta |
|-----------|-----------|----------|
| **Track Limits** | `limiti pista` · `track limit` · `taglio` · `penalita` | Stato track limits e warning attivi |
| **ERS / Ibrido** | `ers` · `deploy` · `ibrido` · `batteria` · `overtake` | Stato batteria, deploy mode, overtake |
| **Freni** | `freni` · `pad` · `pastiglie` · `dischi` · `usura freni` | Usura pad e dischi per ogni ruota |
| **Mappa motore** | `mappa` · `mappa motore` · `modalita` · `modalita motore` | Mappa corrente e nome modalità |
| **Giro ideale** | `ideale` · `giro ideale` · `predicted` · `come va il giro` · `come sto andando` | Predicted lap time vs miglior giro |
| **Danni** | `danni` · `situazione danni` · `carrozzeria` · `damage` | Danni scocca + sospensioni per zona |
| **Motore** | `motore` · `temperature motore` · `acqua` · `olio` · `come va il motore` | Temperature acqua/olio motore |

> **In qualifica** il gap è calcolato sul miglior tempo, non sulla posizione in pista.
> Se sei ai box o non hai completato un giro, l'ingegnere te lo dice.

### 🤖 Coach Proattivo EVO — avvisi spontanei

Oltre a rispondere ai comandi, su EVO il coach **parla da solo** quando rileva situazioni che richiedono la tua attenzione, senza che tu debba chiedere nulla:

- 🛞 Pad o dischi sotto soglia di usura
- 🚧 Danni carrozzeria o sospensioni
- 🔥 Surriscaldamento acqua, olio, batteria
- 🚦 Sforamento limite pit lane
- ⚙️ Mappa motore inadeguata (troppo aggressiva con poco carburante, dimenticata in quali-mode a inizio gara, da scalare a fine stint)
- ⚠️ Track limits invalidati
- 🔄 Marcia inversa / wrong way
- ⏱️ Predicted lap migliore o peggiore del riferimento

Tutti gli alert sono configurabili e disattivabili individualmente dal pannello impostazioni.

---

## 🏁 Compatibilità

| Gioco | Stato | Note |
|-------|-------|------|
| **Assetto Corsa Competizione** | ✅ Stabile | Tutte le funzionalità operative |
| **Assetto Corsa EVO** | 🧪 Sperimentale | Funzionalità base operative + comandi vocali e coach proattivo dedicati |

---

## ✅ Tutte le funzionalità

| Funzionalità | Descrizione |
|-------------|-------------|
| 🎙️ **Ingegnere vocale** | Comandi vocali per gap, passo, fuel, gomme, posizione, meteo (ACC + EVO) |
| 🧪 **Comandi EVO dedicati** | Comandi extra su AC EVO per ERS, freni, mappa motore, danni, predicted lap, temperature |
| 🤖 **Coach proattivo EVO** | Avvisi vocali spontanei su usura freni, danni, surriscaldamento, pit speeding, mappa motore |
| 🎯 **Riconoscimento pilota** | Verifica iscrizione all'evento MMCM all'ingresso in sessione |
| 📡 **Telemetria** | Carburante, temperature, danni, giri — ogni 60 secondi |
| ⚖️ **Fair play** | Verifica software e consumi realistici |
| 📻 **Radio Direzione Gara** | Messaggi vocali con ducking automatico del volume |
| 🌡️ **Pressioni gomme** | Suggerimenti regolazioni dopo 2 giri in qualifica |
| ⛽ **Calcolo carburante** | Litri necessari calcolati prima della gara |
| ⚠️ **Track limits** | Avviso vocale giro invalidato (Pre-Qualifiche) |
| 🔊 **Multilingua** | Italiano e inglese automatico da Windows |
| 🔄 **Auto-update** | Si aggiorna da solo |
| 🎨 **Livree** | Invio e scarico livree del campionato |
| 🔐 **Login semplice** | Auto-login, Steam, o classico |

---

## 📥 Installazione

### Auto-Installer (consigliato)

1. Scarica `Installa_MMCM_SimConnect.bat` e `Install-MMCMSimConnect.ps1` dalla [release page](https://github.com/mdonadel83/AutoInstall_MMCMSIMCONNECT/releases)
2. Mettili nella **stessa cartella**
3. Chiudi SimHub
4. Doppio click su `Installa_MMCM_SimConnect.bat`
5. Avvia SimHub → attiva **MMCM SimConnect** nei plugin

### Installazione manuale

1. Scarica tutti i file da [GitHub Releases](https://github.com/mdonadel83/MMCMSimConnect/releases) (cartella `Release/net48`)
2. Copia nella cartella di installazione SimHub
3. Avvia SimHub → abilita il plugin → login

> **Requisiti:** Windows 10/11, SimHub, connessione Internet

---

## 🎬 Video tutorial

[![Video tutorial](https://img.shields.io/badge/YouTube-Tutorial-red?style=for-the-badge&logo=youtube)](https://youtu.be/MqDn1ar2A54)

---

## ❓ FAQ

<details>
<summary><strong>Il plugin funziona con AC EVO?</strong></summary>
Il supporto per AC EVO è in fase sperimentale. Le funzionalità base sono operative, e dalla v1.9.2 sono disponibili comandi vocali dedicati e un coach proattivo specifico per i sistemi EVO (ERS, mappa motore, predicted lap, temperature, danni). Stiamo continuando a sviluppare il supporto pieno.
</details>

<details>
<summary><strong>L'ingegnere vocale funziona in tutte le sessioni?</strong></summary>
Sì — qualifica, prove libere e gara. In qualifica il gap è basato sul miglior tempo. Se sei ai box o non hai fatto un giro, l'ingegnere te lo dice.
</details>

<details>
<summary><strong>I comandi EVO funzionano anche su ACC?</strong></summary>
No — i comandi specifici EVO (ERS, mappa motore, predicted, danni dettagliati, temperature motore) sono disponibili solo quando giochi ad Assetto Corsa EVO. Se li chiedi su ACC l'ingegnere ti dice che la funzione non è disponibile su quel gioco.
</details>

<details>
<summary><strong>Posso disattivare gli alert proattivi?</strong></summary>
Sì, ogni categoria di alert (freni, danni, mappa motore, pit speeding, surriscaldamento, ecc.) è abilitabile/disabilitabile individualmente nel pannello impostazioni del plugin in SimHub.
</details>

<details>
<summary><strong>Il riconoscimento vocale cala gli FPS?</strong></summary>
No. Gira su un processo separato a priorità alta, completamente indipendente dal gioco.
</details>

<details>
<summary><strong>Posso usare un tasto del volante come PTT?</strong></summary>
Sì! Mappa un tasto del volante su una F-key, poi assegnala come PTT nelle impostazioni del plugin.
</details>

<details>
<summary><strong>Il plugin è obbligatorio?</strong></summary>
Per le gare MMCM Racing sì. L'ingegnere vocale e il coach proattivo sono opzionali e possono essere disattivati.
</details>

<details>
<summary><strong>Devo aggiornarlo manualmente?</strong></summary>
No, si aggiorna da solo.
</details>

---

## 🔗 Link

| | |
|---|---|
| 🌐 **Sito** | [www.mmcmracing.it](https://www.mmcmracing.it) |
| 💬 **Discord** | [discord.gg/jMa4GzGW](https://discord.gg/jMa4GzGW) |
| 📧 **Email** | league@mmcmracing.it |
| 🚀 **Auto-Installer** | [Download](https://github.com/mdonadel83/AutoInstall_MMCMSIMCONNECT/releases) |

---

<br><br><br>

---

# 🇬🇧 English Version

> [🇮🇹 Versione Italiana](#-novità-v192--coach-proattivo-evo-migliorato)

---

## 🆕 What's New in v1.9.2 — Improved EVO Proactive Coach

The **Proactive Coach** for Assetto Corsa EVO has been deeply revised to provide more accurate, timely and useful warnings during the race. Now it speaks when it really matters, with the right data.

### 🔧 What changed

| Area | Improvement |
|------|-------------|
| 🛞 **Brake wear** | Correct pad/disc wear calculation across all EVO cars. Auto-calibrating system that adapts to each vehicle without manual configuration. No more false alerts when leaving the pits. |
| 🚧 **Body damage** | Correct reading scale for chassis and suspension. Left/right zone mapping verified on track. Percentages now match real damage. |
| 🔧 **Suspension alerts** | New: dedicated voice warning when a suspension is damaged, with an independent (more sensitive) threshold than body — because a damaged suspension immediately compromises driveability. |
| 🚦 **Pit speeding** | Speed delta calculation completely rewritten. Now it tells you exactly how many km/h you're over the pit limit, in real time. |
| ⚙️ **Engine Map** | Three distinct alerts: quali-map warning at race start, aggressive map with low fuel warning, end-of-stint reminder to step down. Recognizes more map names (push, max, attack, qualifying, high levels). |

### 🎯 Configurable thresholds

All new coach thresholds are adjustable from the plugin settings panel in SimHub, under "Advanced settings":
- Body damage warning threshold
- Suspension damage warning threshold
- Pit-speeding tolerance (km/h)
- Remaining fuel threshold for map alert
- Remaining laps threshold for end-of-stint

### 🐛 Bug fixes

- Fixed: coach announced "pads at 3%" right after exiting the pits on any EVO car
- Fixed: incorrect damage percentages (24% instead of the real 2.4%)
- Fixed: pit-speeding alert never triggered due to saturation of the sim's raw value
- Fixed: lateral damage zones inverted (left/right)
- Fixed: engine map alerts didn't recognize the most common naming conventions in EVO

---

## 🆕 v1.9 — Virtual Race Engineer

Talk to your race engineer during the race. Ask for gaps, fuel, tyres, position and strategy using just your voice. Real-time responses from live telemetry — like a real team radio.

### How it works

```
You:       "Engineer"
Engineer:  🔊 *beep* (listening, you have 5 seconds)
You:       "Gap to leader"
Engineer:  "Smith ahead, 2 point 3. Gap to leader, 8 point 1.
            Good pace, keep it up, let's go"
```

**Two activation modes:**
- **Wake Word** — say "engineer" then your command
- **Push-to-Talk** — press a button (mappable to steering wheel) then speak
- **Both** — use whichever you prefer

### 🎤 General voice commands (ACC + EVO)

| Category | What you say | Response |
|----------|-------------|----------|
| **Gap** | `gap` | Full gap: ahead, behind, leader |
| | `ahead` · `gap ahead` | Gap to car ahead |
| | `behind` · `gap behind` | Gap to car behind |
| | `gap to leader` · `leader` | Gap to race leader |
| **Pace** | `pace` · `lap times` · `my pace` · `how am i doing` | Last lap, best lap, comparison |
| **Fuel** | `fuel` · `fuel remaining` · `how much fuel` · `range` | Litres, consumption/lap, range |
| | `strategy` · `pit stop` | + calculation if fuel is enough |
| **Tyres** | `tyres` · `tires` · `pressures` | Pressures all 4 wheels |
| | `tyre temps` | Pressures + temperatures |
| **Position** | `position` · `where am i` · `standings` | Position, who's ahead/behind |
| **Weather** | `weather` · `rain` · `track conditions` | Conditions and track grip |
| **Report** | `situation` · `update` · `full report` | Everything combined |

### 🧪 Extra voice commands AC EVO only

On Assetto Corsa EVO, additional commands are available for the car's specific systems:

| Category | What you say | Response |
|----------|-------------|----------|
| **Track Limits** | `track limits` · `limits` · `cut` · `penalty` | Track limits status and active warnings |
| **ERS / Hybrid** | `ers` · `deploy` · `hybrid` · `battery` · `overtake` | Battery state, deploy mode, overtake |
| **Brakes** | `brakes` · `pads` · `discs` · `brake wear` | Pad and disc wear per wheel |
| **Engine Map** | `map` · `engine map` · `mode` | Current map and mode name |
| **Ideal Lap** | `ideal` · `ideal lap` · `predicted` · `how is my lap` | Predicted lap time vs best lap |
| **Damage** | `damage` · `body damage` · `car damage` | Body + suspension damage per zone |
| **Engine** | `engine` · `engine temps` · `water temp` · `oil temp` | Water/oil engine temperatures |

> **In qualifying** the gap is calculated from best lap times, not track position.
> If you're in the pits or haven't completed a lap, the engineer tells you.

### 🤖 EVO Proactive Coach — spontaneous warnings

Beyond responding to commands, on EVO the coach **speaks on its own** when it detects situations that require your attention, without you needing to ask:

- 🛞 Pads or discs below wear threshold
- 🚧 Body or suspension damage
- 🔥 Water, oil, battery overheating
- 🚦 Pit lane speed limit exceeded
- ⚙️ Inadequate engine map (too aggressive with low fuel, forgotten in quali-mode at race start, to step down at end of stint)
- ⚠️ Track limits invalidated
- 🔄 Wrong way / reverse direction
- ⏱️ Predicted lap better or worse than reference

All alerts are configurable and individually disableable from the settings panel.

---

## 🏁 Compatibility

| Game | Status | Notes |
|------|--------|-------|
| **Assetto Corsa Competizione** | ✅ Stable | All features fully operational |
| **Assetto Corsa EVO** | 🧪 Experimental | Basic features working + dedicated voice commands and proactive coach |

---

## ✅ All Features

| Feature | Description |
|---------|-------------|
| 🎙️ **Voice engineer** | Voice commands for gap, pace, fuel, tyres, position, weather (ACC + EVO) |
| 🧪 **Dedicated EVO commands** | Extra commands on AC EVO for ERS, brakes, engine map, damage, predicted lap, temperatures |
| 🤖 **EVO proactive coach** | Spontaneous voice warnings on brake wear, damage, overheating, pit speeding, engine map |
| 🎯 **Driver recognition** | Verifies MMCM event registration on session join |
| 📡 **Telemetry** | Fuel, temperatures, damage, laps — every 60 seconds |
| ⚖️ **Fair play** | Software and consumption verification |
| 📻 **Race Director radio** | Voice messages with automatic volume ducking |
| 🌡️ **Tyre pressures** | Adjustment suggestions after 2 qualifying laps |
| ⛽ **Fuel calculation** | Required litres calculated before race start |
| ⚠️ **Track limits** | Voice warning on invalidated laps (Pre-Qualifying) |
| 🔊 **Multi-language** | Italian and English, auto-detected from Windows |
| 🔄 **Auto-update** | Updates itself automatically |
| 🎨 **Liveries** | Upload and download championship liveries |
| 🔐 **Easy login** | Auto-login, Steam, or classic |

---

## 📥 Installation

### Auto-Installer (recommended)

1. Download `Installa_MMCM_SimConnect.bat` and `Install-MMCMSimConnect.ps1` from [releases](https://github.com/mdonadel83/AutoInstall_MMCMSIMCONNECT/releases)
2. Place them in the **same folder**
3. Close SimHub
4. Double-click `Installa_MMCM_SimConnect.bat`
5. Open SimHub → enable **MMCM SimConnect** in plugins

### Manual installation

1. Download all files from [GitHub Releases](https://github.com/mdonadel83/MMCMSimConnect/releases) (`Release/net48` folder)
2. Copy to SimHub installation folder
3. Open SimHub → enable plugin → login

> **Requirements:** Windows 10/11, SimHub, Internet connection

---

## 🎬 Video tutorial

[![Video tutorial](https://img.shields.io/badge/YouTube-Tutorial-red?style=for-the-badge&logo=youtube)](https://youtu.be/MqDn1ar2A54)

---

## ❓ FAQ

<details>
<summary><strong>Does it work with AC EVO?</strong></summary>
AC EVO support is experimental. Basic features work, and from v1.9.2 dedicated voice commands and a specific proactive coach are available for EVO systems (ERS, engine map, predicted lap, temperatures, damage). We're continuing to develop full support.
</details>

<details>
<summary><strong>Does the voice engineer work in all sessions?</strong></summary>
Yes — qualifying, practice, and race. In qualifying, gaps are based on best lap times. If you're in the pits or haven't completed a lap, the engineer tells you.
</details>

<details>
<summary><strong>Do EVO commands work on ACC too?</strong></summary>
No — the EVO-specific commands (ERS, engine map, predicted, detailed damage, engine temperatures) are only available when playing Assetto Corsa EVO. If you ask them on ACC, the engineer tells you the feature is not available on that game.
</details>

<details>
<summary><strong>Can I disable proactive alerts?</strong></summary>
Yes, every alert category (brakes, damage, engine map, pit speeding, overheating, etc.) can be enabled/disabled individually in the plugin settings panel in SimHub.
</details>

<details>
<summary><strong>Does voice recognition affect FPS?</strong></summary>
No. It runs on a separate high-priority process, completely independent from the game.
</details>

<details>
<summary><strong>Can I use a steering wheel button as PTT?</strong></summary>
Yes! Map a wheel button to an F-key, then assign that F-key as PTT in the plugin settings.
</details>

<details>
<summary><strong>Is the plugin mandatory?</strong></summary>
For MMCM Racing events, yes. The voice engineer and proactive coach are optional and can be disabled.
</details>

<details>
<summary><strong>Do I need to update manually?</strong></summary>
No, it updates itself automatically.
</details>

---

## 🔗 Links

| | |
|---|---|
| 🌐 **Website** | [www.mmcmracing.it](https://www.mmcmracing.it) |
| 💬 **Discord** | [discord.gg/jMa4GzGW](https://discord.gg/jMa4GzGW) |
| 📧 **Email** | league@mmcmracing.it |
| 🚀 **Auto-Installer** | [Download](https://github.com/mdonadel83/AutoInstall_MMCMSIMCONNECT/releases) |

---

<p align="center">
  <strong>🏎️ MMCM SimConnect v1.9.2</strong><br>
  ACC: fully supported · AC EVO: experimental<br>
  <sub>Made with ❤️ for the MMCM Racing community</sub>
</p>
