<p align="center">
  <img src="https://www.mmcmracing.it/wp-content/uploads/2024/03/cropped-mmcmracing_trasp-1-e1711745622868.png" alt="MMCM Racing" width="200">
</p>

<h1 align="center">🏎️ MMCM SimConnect v1.9</h1>

<p align="center">
  <strong>Plugin SimHub per Assetto Corsa Competizione</strong><br>
  Assistente di gara con ingegnere di pista virtuale a comandi vocali
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.9-red?style=flat-square" alt="Version">
  <img src="https://img.shields.io/badge/ACC-✅%20Supportato-2ecc71?style=flat-square" alt="ACC">
  <img src="https://img.shields.io/badge/AC%20EVO-🧪%20Sperimentale-f4a623?style=flat-square" alt="EVO">
  <img src="https://img.shields.io/badge/SimHub-9.x-blue?style=flat-square" alt="SimHub">
  <img src="https://img.shields.io/badge/Windows-10%2F11-0078d4?style=flat-square" alt="Windows">
</p>

---

> 🇮🇹 **Italiano** | [🇬🇧 English](#-english-version)

---

## 🆕 Novità v1.9 — Ingegnere di Pista Virtuale

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

### 🎤 Comandi vocali disponibili

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

> **In qualifica** il gap è calcolato sul miglior tempo, non sulla posizione in pista.
> Se sei ai box o non hai completato un giro, l'ingegnere te lo dice.

---

## 🏁 Compatibilità

| Gioco | Stato | Note |
|-------|-------|------|
| **Assetto Corsa Competizione** | ✅ Stabile | Tutte le funzionalità operative |
| **Assetto Corsa EVO** | 🧪 Sperimentale | Funzionalità base operative, supporto pieno in sviluppo |

---

## ✅ Tutte le funzionalità

| Funzionalità | Descrizione |
|-------------|-------------|
| 🎙️ **Ingegnere vocale** | Comandi vocali per gap, passo, fuel, gomme, posizione, meteo |
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
Il supporto per AC EVO è in fase sperimentale. Le funzionalità base sono operative ma alcune features potrebbero non essere completamente funzionanti. Stiamo sviluppando attivamente il supporto pieno.
</details>

<details>
<summary><strong>L'ingegnere vocale funziona in tutte le sessioni?</strong></summary>
Sì — qualifica, prove libere e gara. In qualifica il gap è basato sul miglior tempo. Se sei ai box o non hai fatto un giro, l'ingegnere te lo dice.
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
Per le gare MMCM Racing sì. L'ingegnere vocale è opzionale e può essere disattivato.
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

> [🇮🇹 Versione Italiana](#-novità-v19--ingegnere-di-pista-virtuale)

---

## 🆕 What's New in v1.9 — Virtual Race Engineer

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

### 🎤 Available voice commands

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

> **In qualifying** the gap is calculated from best lap times, not track position.
> If you're in the pits or haven't completed a lap, the engineer tells you.

---

## 🏁 Compatibility

| Game | Status | Notes |
|------|--------|-------|
| **Assetto Corsa Competizione** | ✅ Stable | All features fully operational |
| **Assetto Corsa EVO** | 🧪 Experimental | Basic features working, full support in development |

---

## ✅ All Features

| Feature | Description |
|---------|-------------|
| 🎙️ **Voice engineer** | Voice commands for gap, pace, fuel, tyres, position, weather |
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
AC EVO support is experimental. Basic features work but some may not be fully functional yet. We're actively developing full support.
</details>

<details>
<summary><strong>Does the voice engineer work in all sessions?</strong></summary>
Yes — qualifying, practice, and race. In qualifying, gaps are based on best lap times. If you're in the pits or haven't completed a lap, the engineer tells you.
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
For MMCM Racing events, yes. The voice engineer is optional and can be disabled.
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
  <strong>🏎️ MMCM SimConnect v1.9</strong><br>
  ACC: fully supported · AC EVO: experimental<br>
  <sub>Made with ❤️ for the MMCM Racing community</sub>
</p>
