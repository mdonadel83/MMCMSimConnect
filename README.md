<p align="center">
  <img src="https://www.mmcmracing.it/img/MMCM_simconnect.jpg" alt="MMCM Racing — Online / Offline Championship" width="820">
</p>

<h1 align="center">MMCM SimConnect v2.0</h1>

<p align="center">
  <b>Plugin SimHub per Assetto Corsa Competizione e Assetto Corsa EVO</b><br>
  Ingegnere di pista vocale, campionato online e carriera offline — tutto dentro SimHub.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/versione-1.9.9-red?style=flat-square" alt="Versione">
  <img src="https://img.shields.io/badge/ACC-%E2%9C%85%20Supportato-2ecc71?style=flat-square" alt="ACC">
  <img src="https://img.shields.io/badge/AC%20EVO-%F0%9F%A7%AA%20Sperimentale-f4a623?style=flat-square" alt="EVO">
  <img src="https://img.shields.io/badge/SimHub-9.x-blue?style=flat-square" alt="SimHub">
  <img src="https://img.shields.io/badge/Windows-10%2F11-0078d4?style=flat-square" alt="Windows">
  <img src="https://img.shields.io/badge/licenza-GPL--3.0-lightgrey?style=flat-square" alt="Licenza">
</p>

---

> 🇮🇹 **Italiano** | [🇬🇧 English](#-english-version)

---

## 🆕 Novità v1.9.9 — Campionato online e carriera offline

La 1.9.9 è la versione più grande mai rilasciata. Fino alla 1.9.2 il plugin era un assistente
di gara: leggeva la telemetria, parlava, controllava le iscrizioni. Da oggi è anche **il posto
da cui si corre**.

Due modi di correre, uno accanto all'altro:

| | 🏆 **Carriera** (offline) | 🏁 **Campionato MP** (online) |
|---|---|---|
| **Contro chi** | Bot di AC EVO, quando vuoi tu | Piloti veri, al round della stagione |
| **Cosa metti in gioco** | Crediti, auto, licenza | Crediti, auto, punti, safety rating |
| **Chi giudica** | Nessuno: i contatti restano tra te e il tuo rating | Direzione Gara MMCM, con episodi e documenti |
| **Serve un server?** | No | Sì, quello ufficiale del round |

Le due cose condividono lo stesso pilota, lo stesso garage e lo stesso conto in banca. La
carriera offline è il modo di arrivare in griglia con un'auto pagata da te.

> **Cos'è il safety rating, per chi non lo conosce ancora.** È il tuo indicatore personale
> di quanto guidi pulito: un numero che ti segue in tutta la carriera MMCM, in single player
> e online. Ogni contatto lo abbassa. Fino a questa versione poteva **solo** abbassarsi — non
> esisteva modo di farlo risalire correndo bene, solo di smettere di farlo scendere. È
> proprio questo il punto che cambia con la 1.9.9, spiegato qui sotto.

---

### 🏆 Carriera MMCM — il campionato offline

Un pilota, un budget, un garage. Si comincia con un capitale iniziale e un'auto scelta al
concessionario, e da lì si va avanti a forza di risultati.

**Come si parte** — Alla prima attivazione si apre la creazione guidata dentro SimHub: come
funziona l'economia, quali auto puoi permetterti con il budget iniziale, quanto ti resta in
tasca dopo l'acquisto. Tre passi, nessun passaggio dal sito.

| Cosa | Come funziona |
|---|---|
| 🏪 **Concessionario** | Catalogo vetture con prezzo, categoria e costo delle riparazioni. Compri quello che il saldo ti permette. |
| 🔧 **Garage** | Le auto che possiedi, con il danno accumulato. Le riparazioni si pagano. |
| 🏆 **Campionati** | Offerte disponibili con requisiti, quota d'iscrizione e montepremi. Ti iscrivi scegliendo con quale auto correre. |
| 💰 **Sponsor** | Il vero motore economico: i premi gara da soli non bastano. Le offerte arrivano in base a reputazione e safety rating — prima i piccoli locali, poi i grandi. Scadono, quindi vanno guardate. |
| 🏦 **Banca** | Prestiti con i piani affiancati: rata, costo totale e TAEG di ognuno. Estinzione anticipata e storico dei rapporti. Nessun campo importo e bottone "richiedi": prima si confronta. |
| 📈 **Progressione** | Si sale di categoria e di licenza per merito, con criteri visibili. Le promozioni hanno una pagella con i numeri che l'hanno decisa. |
| 📊 **Storico** | Ogni sessione con contatti, track limits e quanto safety rating è costata. La risposta con i fatti a "il mio rating non sale ma non ho mai fatto niente". |

**Ora il safety rating può anche salire.** Prima, l'unico modo di "guadagnarlo" era la gara
perfetta — che non esiste, perché basta un contatto qualsiasi, anche non colpa tua, e il
numero scende comunque. Da questa versione il plugin misura gli **stint di lotta**: quanto a
lungo hai corso fianco a fianco con un avversario *senza toccarlo*. Uno stint matura il bonus
solo se si chiude pulito; un contatto lo azzera, non lo riduce. Sotto i 20 secondi non è una
lotta, è un sorpasso, e non conta.

---

### 🏁 Campionato MP — il campionato online

La stagione multiplayer, gestita dal plugin dall'iscrizione al verdetto della Direzione Gara.

**Tre modi di iscriversi**, una scelta sola valida per tutti i round:

- **Con la propria auto** — corri con una vettura del tuo garage. I danni sono tuoi.
- **A noleggio** — il campionato ti presta l'auto. Paghi il noleggio e i danni fino alla
  franchigia; oltre, paga il campionato.
- **Distaccato** — corri e basta: presenza, contatti e classifica sì, crediti no. Resta
  aperto anche a chi è in rosso, perché correre è l'unico modo di rientrare.

| Cosa | Come funziona |
|---|---|
| ⏱️ **Pre-qualifiche live** | Le piste del ciclo, quelle fatte, quelle che restano. Con la distinzione che conta: il **tempo ufficiale** (sotto soglia, che entra in classifica) e il **tuo migliore**, con il delta dalla soglia. Chi gira sopra soglia sa se gli mancano due decimi o dieci secondi. |
| 🚦 **Semaforo di sessione** | Overlay always-on-top che verifica pista, vettura, regolamento e iscrizione **mentre configuri la sessione nei menu**, non dopo. Passa da solo alla modalità compatta quando sei in pista. |
| ⚖️ **Direzione Gara** | Gli episodi arrivano dalla telemetria dei due piloti coinvolti, non da una segnalazione. Gli steward vedono entrambi i lati, giudicano, pubblicano il documento. Reclami e richieste di riesame gestiti dentro il plugin. |
| 📋 **Coda presenze** | Una riga per pilota con il suggerimento accanto e gli episodi della sua gara in linea. Un round non si chiude con dentro contatti mai guardati. |
| 🚗 **Entrylist e ammissioni** | Catalogo vetture con categoria MMCM e ammissioni per campionato. Cosa si può guidare qui, deciso dal regolamento. |
| 🏁 **Risultati e classifiche** | Risultati di round, classifica di campionato, storico. Import dei file risultati di AC EVO e da SimGrid per gli admin. |

**Rilevamento contatti riscritto.** Il plugin ora riconosce le posizioni di tutte le auto in
pista, non solo la propria: prima, senza sapere dove fossero gli avversari, ogni contatto
veniva classificato come muro. **Sola lettura: non modifica né interferisce col gioco.**

Il riconoscimento del contatto è più preciso: distingue un vero impatto da una staccata
forte o da una curva presa al limite, cosa che prima generava falsi positivi.

---

### 🔒 Trasparenza e dati

- **Niente parte senza consenso.** All'attivazione della carriera si apre l'informativa
  completa, con la casella **non pre-spuntata**. Se rifiuti, la spunta torna indietro da sola
  e nessun dato esce. Il rilevatore può girare in locale, ma i dati escono solo a sessione
  agganciata.
- **Payload firmati** HMAC-SHA256 su ogni invio.
- **Identità degli avversari risolta lato server**: il plugin registra posizioni e timestamp
  UTC, non nomi. I car_id di EVO cambiano a ogni sessione.
- **Nessuna penalità automatica.** Il plugin raccoglie i fatti, le decisioni sono della
  Direzione Gara secondo regolamento.
- **Niente giri persi.** La coda dei giri si scrive anche su disco: se il PC si pianta o
  salta la corrente, la gara non sparisce con la memoria.

---

### 🐛 Correzioni accumulate dalla 1.9.3 alla 1.9.9

| Area | Cosa è stato risolto |
|---|---|
| 🛞 **Gomme EVO** | SimHub scambiava anteriore destra e posteriore destra: ora i valori ruota su EVO passano dai path raw. Pressioni di riferimento per compound. |
| 🚧 **Danni EVO** | Normalizzazione basata su dati misurati, non stimati. Zone laterali non più invertite. |
| 🏁 **Sessioni EVO** | La qualifica di EVO gira come `AC_TIME_ATTACK`: il plugin la riconosce e non la tratta più come time attack libero. Risolto il "P2 su 0/1". |
| 🚦 **Pit speeding** | Delta in km/h reale rispetto al limite, non più saturato dal valore raw del sim. |
| 🛑 **Usura freni** | Salta il calcolo durante il pit e usa un grace period all'uscita: niente più "pad al 3%" appena rientrati. |
| 📍 **Gap e posizione** | Contesto di posizione e trend di avvicinamento nelle risposte dell'ingegnere. |

---

## 🎙️ Ingegnere di Pista Virtuale

Parla con il tuo ingegnere durante la gara. Chiedi gap, carburante, gomme, posizione e
strategia usando solo la voce. Risponde in tempo reale con i dati dalla telemetria.

```
Tu:         "Ingegnere"
Ingegnere:  🔊 *beep* (in ascolto, hai 5 secondi)
Tu:         "Gap dal primo"
Ingegnere:  "Rossi davanti, 2 secondi e 3. Dal leader, 8 secondi.
             Bene, mantieni il ritmo, vai vai vai"
```

**Due modi per attivare:** wake word ("ingegnere"), Push-to-Talk su un tasto del volante, o
entrambi. Il riconoscimento gira su un processo esterno a priorità alta: nessun calo di FPS
anche in fullscreen.

### 🎤 Comandi vocali generali (ACC + EVO)

| Categoria | Cosa dici | Risposta |
|---|---|---|
| **Gap** | `gap` · `distacco` | Gap completo: davanti, dietro, leader |
| | `davanti` · `chi ho davanti` | Gap dal pilota davanti |
| | `dietro` · `chi ho dietro` | Gap dal pilota dietro |
| | `gap dal primo` · `gap leader` | Distacco dal leader |
| **Passo** | `passo` · `tempi` · `come vado` | Ultimo giro, miglior giro, confronto |
| **Carburante** | `carburante` · `benzina` · `autonomia` | Litri, consumo/giro, autonomia |
| | `strategia` · `pit stop` | + calcolo se basta per finire |
| **Gomme** | `gomme` · `pressioni` | Pressioni 4 ruote |
| | `temperature gomme` | Pressioni + temperature |
| **Posizione** | `posizione` · `dove sono` · `classifica` | Posizione, chi è davanti/dietro |
| **Meteo** | `meteo` · `piove` · `grip` | Condizioni e grip pista |
| **Report** | `situazione` · `report` · `dammi tutto` | Tutto insieme |

> **In qualifica** il gap è calcolato sul miglior tempo, non sulla posizione in pista.
> Se sei ai box o non hai completato un giro, l'ingegnere te lo dice invece di darti dati
> inaffidabili.

### 🧪 Comandi vocali extra solo per AC EVO

| Categoria | Cosa dici | Risposta |
|---|---|---|
| **Track Limits** | `limiti pista` · `taglio` · `penalita` | Stato track limits e warning attivi |
| **ERS / Ibrido** | `ers` · `deploy` · `batteria` · `overtake` | Batteria, deploy mode, overtake |
| **Freni** | `freni` · `pad` · `dischi` · `usura freni` | Usura pad e dischi per ruota |
| **Mappa motore** | `mappa` · `modalita motore` | Mappa corrente e nome modalità |
| **Giro ideale** | `ideale` · `predicted` · `come sto andando` | Predicted lap vs miglior giro |
| **Danni** | `danni` · `carrozzeria` | Danni scocca + sospensioni per zona |
| **Motore** | `motore` · `acqua` · `olio` | Temperature acqua/olio |

### 🤖 Coach Proattivo EVO — avvisi spontanei

Su EVO il coach **parla da solo** quando serve, senza che tu chieda:

🛞 Pad o dischi sotto soglia · 🚧 Danni a carrozzeria o sospensioni · 🔥 Surriscaldamento
acqua, olio, batteria · 🚦 Sforamento limite pit lane · ⚙️ Mappa motore inadeguata ·
⚠️ Track limits invalidati · 🔄 Marcia inversa · ⏱️ Predicted lap migliore o peggiore

Ogni categoria è disattivabile singolarmente, e tutte le soglie sono regolabili dal pannello
impostazioni.

---

## 🏁 Compatibilità

| Gioco | Stato | Note |
|---|---|---|
| **Assetto Corsa Competizione** | ✅ Stabile | Ingegnere, telemetria, pre-qualifiche, fair play, Direzione Gara |
| **Assetto Corsa EVO** | 🧪 Sperimentale | Tutto quanto sopra + coach proattivo, comandi dedicati, carriera e campionato MP |

> Carriera e Campionato MP funzionano su AC EVO. Su ACC restano operative telemetria,
> pre-qualifiche e ingegnere vocale.

---

## ✅ Tutte le funzionalità

| Funzionalità | Descrizione |
|---|---|
| 🏆 **Carriera offline** | Pilota, budget, garage, sponsor, banca, licenze, progressione |
| 🏁 **Campionato MP** | Iscrizione stagione, noleggi, entrylist, presenze, risultati |
| ⚖️ **Direzione Gara** | Episodi dai due lati, documenti, reclami, riesami |
| 🚦 **Semaforo sessione** | Overlay di validazione visibile dai menu del gioco |
| ⏱️ **Pre-qualifiche** | Tempo ufficiale e migliore, delta dalla soglia, quadro generale |
| 🎙️ **Ingegnere vocale** | Gap, passo, fuel, gomme, posizione, meteo (ACC + EVO) |
| 🧪 **Comandi EVO** | ERS, freni, mappa motore, danni, predicted lap, temperature |
| 🤖 **Coach proattivo** | Avvisi vocali spontanei, tutti configurabili |
| 📡 **Telemetria** | Carburante, temperature, danni, giri — con coda persistente |
| ⚖️ **Fair play** | Verifica software e consumi realistici |
| 📻 **Radio Direzione Gara** | Messaggi vocali con ducking automatico del volume |
| 🌡️ **Pressioni gomme** | Suggerimenti dopo 2 giri in qualifica |
| ⛽ **Calcolo carburante** | Litri necessari calcolati prima della gara |
| 🎨 **Livree** | Invio e scarico livree del campionato |
| 🔊 **Multilingua** | Italiano e inglese automatico da Windows |
| 🔄 **Auto-update** | Si aggiorna da solo |
| 🔐 **Login** | Auto-login, Steam, o classico |
| 🛠️ **Strumenti admin** | Stagione, punti, catalogo, noleggi, progressione, import risultati |

---

## 📥 Installazione

### Auto-Installer (consigliato)

1. Scarica `Installa_MMCM_SimConnect.bat` e `Install-MMCMSimConnect.ps1` dalla
   [release page](https://github.com/mdonadel83/AutoInstall_MMCMSIMCONNECT/releases)
2. Mettili nella **stessa cartella**
3. Chiudi SimHub
4. Doppio click su `Installa_MMCM_SimConnect.bat`
5. Avvia SimHub → attiva **MMCM SimConnect** nei plugin

### Installazione manuale

1. Scarica tutti i file da [Releases](https://github.com/mdonadel83/MMCMSimConnect/releases)
   (cartella `Release/net48`)
2. Copia nella cartella di installazione di SimHub
3. Avvia SimHub → abilita il plugin → login

### Attivare la Carriera

1. Impostazioni del plugin → scheda **🏆 Carriera**
2. Spunta **Abilita modalità Carriera MMCM** → leggi l'informativa → **Accetto e attivo**
3. Si apre la creazione del pilota: budget iniziale, scelta dell'auto, conferma

> **Requisiti:** Windows 10/11, SimHub 9.x, .NET Framework 4.8, connessione Internet.

> 💡 **Consigliata una licenza SimHub.** Senza, SimHub aggiorna i dati di gioco 10 volte al
> secondo; con una licenza attiva sale a 60. Il plugin legge quei dati in tempo reale per
> calcolare tempi, contatti e validità delle sessioni: più aggiornamenti al secondo
> significano più precisione, specialmente nei momenti concitati di una gara. La licenza è
> un contributo libero (a partire da pochi euro), è perpetua e si acquista dal
> [sito ufficiale di SimHub](https://www.simhubdash.com/). Il plugin funziona anche senza,
> ma è la differenza fra "quasi sempre preciso" e "sempre preciso".

---

## 🎬 Video tutorial

[![Video tutorial](https://img.shields.io/badge/YouTube-Tutorial-red?style=for-the-badge&logo=youtube)](https://youtu.be/MqDn1ar2A54)

---

## ❓ FAQ

**Devo per forza avere una carriera per correre nel campionato online?**
No. Senza stagione carriera si corre lo stesso, semplicemente senza economia. E chi non vuole
crediti né spese può iscriversi come **distaccato**: presenza, contatti e classifica valgono
comunque.

**Cosa succede se rompo l'auto a noleggio?**
Paghi i danni fino alla franchigia. Oltre quella cifra paga il campionato. Alla restituzione
l'admin vede i danni e la franchigia prima di confermare l'addebito.

**Sono in rosso, sono fuori dal campionato?**
No. L'iscrizione da distaccato resta aperta anche a chi è insolvente, perché correre è l'unico
modo di rientrare.

**Il plugin decide le penalità?**
No. Raccoglie i fatti — danno, posizioni, orari — e li porta agli steward. Le
decisioni sono della Direzione Gara secondo il regolamento.

**Chi vede i miei contatti in carriera offline?**
Nessuno. Nel single player i contatti restano un fatto privato tra te e il tuo safety rating.
La Direzione Gara si occupa solo del multiplayer, dove ci sono avversari veri.

**Il plugin funziona con AC EVO?**
Il supporto EVO resta ufficialmente sperimentale, ma è dove il plugin fa di più: coach
proattivo, comandi dedicati, carriera e campionato MP sono tutte funzioni pensate per EVO.

**Posso disattivare gli alert proattivi?**
Sì, categoria per categoria, e anche le soglie sono regolabili.

**Il riconoscimento vocale cala gli FPS?**
No. Gira su un processo separato a priorità alta, indipendente dal gioco.

**Il plugin è obbligatorio?**
Per le gare MMCM Racing sì. Ingegnere vocale e coach proattivo sono opzionali.

**Devo aggiornarlo manualmente?**
No, si aggiorna da solo.

---

## 🔗 Link

| | |
|---|---|
| 🌐 **Sito** | [www.mmcmracing.it](https://www.mmcmracing.it) |
| 📖 **Pagina plugin** | [MMCM SimConnect](https://www.mmcmracing.it/simhub-mmcm-simconnect/) |
| 💬 **Discord** | [discord.gg/ZrJg7KGnsd](https://discord.gg/ZrJg7KGnsd) |
| ▶️ **YouTube** | [MMCM Racing](https://www.youtube.com/channel/UCnFQRv_ycZ8D8_hEivdR-ZA) |
| 🟣 **Twitch** | [mmcmracing](https://www.twitch.tv/mmcmracing) |
| 📧 **Email** | league@mmcmracing.it |
| 🚀 **Auto-Installer** | [Download](https://github.com/mdonadel83/AutoInstall_MMCMSIMCONNECT/releases) |

---

<br>

# 🇬🇧 English Version

> [🇮🇹 Versione Italiana](#-novità-v199--campionato-online-e-carriera-offline)

> ⚠️ **Work in progress.** This translation isn't complete yet and may lag behind the
> Italian version above. When in doubt, the Italian section is the one kept up to date.

---

## 🆕 What's new in v1.9.9 — Online championship and offline career

1.9.9 is the biggest release so far. Up to 1.9.2 the plugin was a race assistant: it read
telemetry, talked to you, checked your entry. From today it is also **the place you race
from**.

Two ways to race, side by side:

| | 🏆 **Career** (offline) | 🏁 **MP Championship** (online) |
|---|---|---|
| **Against** | AC EVO AI, whenever you want | Real drivers, on season round night |
| **At stake** | Credits, car, licence | Credits, car, points, safety rating |
| **Who judges** | Nobody: contacts stay between you and your rating | MMCM Race Direction, with episodes and documents |
| **Server needed?** | No | Yes, the official round server |

Both share the same driver, the same garage and the same bank account. The offline career is
how you reach the grid in a car you paid for yourself.

> **What safety rating is, for anyone new here.** It's your personal clean-driving score:
> a number that follows you through your whole MMCM career, offline and online. Every
> contact lowers it. Until this version it could **only** go down — there was no way to
> earn it back by racing well, only to stop losing it. That's exactly what changes with
> 1.9.9, explained below.

---

### 🏆 MMCM Career — the offline championship

One driver, one budget, one garage. You start with seed money and a car from the dealership,
and go on from there on results alone.

**Getting started** — On first activation a guided setup opens inside SimHub: how the economy
works, which cars your starting budget affords, what's left in your pocket after the purchase.
Three steps, no trip to the website.

| What | How it works |
|---|---|
| 🏪 **Dealership** | Car catalogue with price, class and repair cost. You buy what your balance allows. |
| 🔧 **Garage** | The cars you own, with accumulated damage. Repairs are paid for. |
| 🏆 **Championships** | Available entries with requirements, entry fee and prize pool. You pick which car to race. |
| 💰 **Sponsors** | The real economic engine: race prizes alone aren't enough. Offers arrive based on reputation and safety rating — small local ones first, bigger later. They expire, so check them. |
| 🏦 **Bank** | Loans shown as side-by-side plans: instalment, total cost and APR for each. Early repayment and full history. No amount field and "request" button: compare first. |
| 📈 **Progression** | Class and licence promotions on merit, with visible criteria. Every promotion comes with the numbers that decided it. |
| 📊 **History** | Every session with contacts, track limits and how much safety rating it cost. The factual answer to "my rating never goes up and I never did anything". |

**Now safety rating can go up too.** Before, the only way to "earn" it was a perfect race —
which doesn't exist, because a single contact, even one that isn't your fault, still brings
the number down. From this version the plugin measures **battle stints**: how long you raced
side by side with a rival *without touching him*. A stint pays out only if it closes clean; a
contact zeroes it, doesn't reduce it. Under 20 seconds it isn't a battle, it's an overtake,
and it doesn't count.

---

### 🏁 MP Championship — the online championship

The multiplayer season, run from the plugin from entry to the Race Direction verdict.

**Three ways to enter**, chosen once for the whole season:

- **Own car** — you race a car from your garage. The damage is yours.
- **Rental** — the championship lends you a car. You pay the rental and damage up to the
  excess; beyond that, the championship pays.
- **Detached** — you just race: attendance, contacts and standings count, credits don't. It
  stays open even to drivers in the red, because racing is the only way back.

| What | How it works |
|---|---|
| ⏱️ **Live pre-qualifying** | Tracks in the cycle, done and remaining. With the distinction that matters: the **official time** (under the threshold, counts for the standings) and **your best**, with the delta from the threshold. |
| 🚦 **Session traffic light** | Always-on-top overlay validating track, car, regulations and entry **while you set the session up in the menus**, not after. Switches to compact mode by itself once you're on track. |
| ⚖️ **Race Direction** | Episodes come from the telemetry of both drivers involved, not from a report. Stewards see both sides, judge, publish the document. Complaints and reviews handled in the plugin. |
| 📋 **Attendance queue** | One row per driver with the suggestion next to it and that driver's episodes inline. A round can't be closed with unreviewed contacts inside it. |
| 🚗 **Entry list and eligibility** | Car catalogue with MMCM class and per-championship eligibility. |
| 🏁 **Results and standings** | Round results, championship standings, history. Import of AC EVO result files and SimGrid data for admins. |

**Contact detection rewritten.** The plugin now recognises the position of every car on
track, not just your own: previously, without knowing where rivals were, every contact
was classified as a wall hit. **Read-only: it doesn't modify or interfere with the game.**

Contact recognition is more accurate too: it tells a real impact apart from hard braking
or a corner taken at the limit, which used to trigger false positives.

---

### 🔒 Transparency and data

- **Nothing leaves without consent.** Activating Career opens the full data notice with the
  checkbox **not pre-ticked**. Decline and the toggle reverts itself; no data is sent.
- **HMAC-SHA256 signed payloads** on every submission.
- **Rival identity resolved server-side**: the plugin records positions and UTC timestamps,
  not names. EVO car_ids change every session.
- **No automatic penalties.** The plugin collects facts, Race Direction decides.
- **No lost laps.** The lap queue is also journalled to disk: a crash or a power cut costs a
  delay, not the race.

---

### 🐛 Fixes since 1.9.3

| Area | Fixed |
|---|---|
| 🛞 **EVO tyres** | SimHub swapped front-right and rear-right: wheel values on EVO now come from raw paths. Reference pressures per compound. |
| 🚧 **EVO damage** | Normalisation based on measured data. Lateral zones no longer inverted. |
| 🏁 **EVO sessions** | EVO qualifying runs as `AC_TIME_ATTACK`: the plugin recognises it. "P2 out of 0/1" fixed. |
| 🚦 **Pit speeding** | Real km/h delta over the limit, no longer saturated by the sim's raw value. |
| 🛑 **Brake wear** | Skipped during the pit stop with a grace period on exit: no more "pads at 3%" right after coming out. |
| 📍 **Gap and position** | Position context and closing-rate trend in the engineer's answers. |

---

## 🎙️ Virtual Race Engineer

Talk to your engineer during the race. Ask for gaps, fuel, tyres, position and strategy with
your voice. Real-time answers from live telemetry.

```
You:       "Engineer"
Engineer:  🔊 *beep* (listening, you have 5 seconds)
You:       "Gap to leader"
Engineer:  "Smith ahead, 2 point 3. Gap to leader, 8 point 1.
            Good pace, keep it up, let's go"
```

**Two activation modes:** wake word, Push-to-Talk on a wheel button, or both. Recognition runs
in a separate high-priority process: no FPS drop, even in fullscreen.

### 🎤 General voice commands (ACC + EVO)

| Category | What you say | Response |
|---|---|---|
| **Gap** | `gap` | Full gap: ahead, behind, leader |
| | `ahead` · `gap ahead` | Gap to the car ahead |
| | `behind` · `gap behind` | Gap to the car behind |
| | `gap to leader` | Gap to the race leader |
| **Pace** | `pace` · `lap times` · `how am i doing` | Last lap, best lap, comparison |
| **Fuel** | `fuel` · `range` | Litres, consumption per lap, range |
| | `strategy` · `pit stop` | + whether fuel is enough to finish |
| **Tyres** | `tyres` · `pressures` | All four pressures |
| | `tyre temps` | Pressures + temperatures |
| **Position** | `position` · `where am i` | Position, who's ahead and behind |
| **Weather** | `weather` · `rain` · `track conditions` | Conditions and grip |
| **Report** | `situation` · `full report` | Everything at once |

> **In qualifying** gaps come from best lap times, not track position. In the pits or before
> your first lap, the engineer says so instead of giving you junk.

### 🧪 AC EVO only commands

| Category | What you say | Response |
|---|---|---|
| **Track Limits** | `track limits` · `cut` · `penalty` | Track limit status and active warnings |
| **ERS / Hybrid** | `ers` · `deploy` · `battery` · `overtake` | Battery, deploy mode, overtake |
| **Brakes** | `brakes` · `pads` · `discs` | Pad and disc wear per wheel |
| **Engine map** | `map` · `engine map` · `mode` | Current map and mode name |
| **Ideal lap** | `ideal` · `predicted` | Predicted lap vs best lap |
| **Damage** | `damage` · `body damage` | Body + suspension damage per zone |
| **Engine** | `engine` · `water temp` · `oil temp` | Water and oil temperatures |

### 🤖 EVO Proactive Coach

On EVO the coach **speaks on its own**: pad or disc wear, body and suspension damage, water,
oil and battery overheating, pit lane speeding, wrong engine map, invalidated track limits,
wrong way, predicted lap better or worse. Every category can be switched off individually and
every threshold is adjustable.

---

## 🏁 Compatibility

| Game | Status | Notes |
|---|---|---|
| **Assetto Corsa Competizione** | ✅ Stable | Engineer, telemetry, pre-qualifying, fair play, Race Direction |
| **Assetto Corsa EVO** | 🧪 Experimental | All of the above + proactive coach, dedicated commands, career and MP championship |

---

## 📥 Installation

### Auto-Installer (recommended)

1. Download `Installa_MMCM_SimConnect.bat` and `Install-MMCMSimConnect.ps1` from
   [releases](https://github.com/mdonadel83/AutoInstall_MMCMSIMCONNECT/releases)
2. Put them in the **same folder**
3. Close SimHub
4. Double-click `Installa_MMCM_SimConnect.bat`
5. Open SimHub → enable **MMCM SimConnect** in plugins

### Manual installation

1. Download everything from [Releases](https://github.com/mdonadel83/MMCMSimConnect/releases)
   (`Release/net48` folder)
2. Copy into your SimHub installation folder
3. Open SimHub → enable the plugin → log in

### Enabling Career

1. Plugin settings → **🏆 Career** tab
2. Tick **Enable MMCM Career mode** → read the notice → **Accept and enable**
3. Driver creation opens: starting budget, car choice, confirmation

> **Requirements:** Windows 10/11, SimHub 9.x, .NET Framework 4.8, Internet connection.

> 💡 **A SimHub license is recommended.** Without one, SimHub updates game data 10 times a
> second; with an active license, that goes up to 60. The plugin reads that data in real
> time to work out lap times, contacts and session validity: more updates per second means
> more precision, especially in the busy moments of a race. The license is a free-amount
> donation (from a few euros), it's perpetual, and you can get it from the
> [official SimHub website](https://www.simhubdash.com/). The plugin works without it too —
> it's the difference between "almost always precise" and "always precise".

---

## ❓ FAQ

**Do I need a career to race the online championship?**
No. Without a career season you race just the same, only without the economy. And anyone who
wants neither credits nor costs can enter as **detached**: attendance, contacts and standings
still count.

**What if I wreck a rental car?**
You pay the damage up to the excess. Beyond that the championship pays. On return the admin
sees the damage and the excess before confirming the charge.

**I'm in the red — am I out?**
No. Detached entry stays open to insolvent drivers, because racing is the only way back.

**Does the plugin hand out penalties?**
No. It collects the facts — damage, positions, timestamps — and takes them to the
stewards. Decisions belong to Race Direction under the regulations.

**Who sees my contacts in offline career?**
Nobody. In single player contacts stay private between you and your safety rating.

**Does voice recognition cost FPS?**
No. Separate high-priority process, independent from the game.

**Is the plugin mandatory?**
For MMCM Racing events, yes. The voice engineer and proactive coach are optional.

---

## 🔗 Links

| | |
|---|---|
| 🌐 **Website** | [www.mmcmracing.it](https://www.mmcmracing.it) |
| 📖 **Plugin page** | [MMCM SimConnect](https://www.mmcmracing.it/simhub-mmcm-simconnect/) |
| 💬 **Discord** | [discord.gg/ZrJg7KGnsd](https://discord.gg/ZrJg7KGnsd) |
| ▶️ **YouTube** | [MMCM Racing](https://www.youtube.com/channel/UCnFQRv_ycZ8D8_hEivdR-ZA) |
| 📧 **Email** | league@mmcmracing.it |

---

<p align="center">
  <img src="docs/assets/icon-badge-128.png" alt="MMCM Racing" width="88"><br>
  <b>🏎️ MMCM SimConnect v1.9.9</b><br>
  ACC: pienamente supportato · AC EVO: sperimentale<br>
  <i>Sviluppato con ❤️ per la community MMCM Racing</i><br>
  <sub>GPL-3.0 · © 2026 MMCM Corse</sub>
</p>
