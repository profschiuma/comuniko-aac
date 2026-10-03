# Comuniko AAC 🧩

> **Strumento web compensativo per la Comunicazione Aumentativa e Alternativa (CAA), il pregrafismo e la scrittura graduale.**  
> Sviluppato per docenti di sostegno, curricolari, educatori e famiglie nella scuola dell'infanzia e primaria[cite: 2].

---

## 🌟 Cos'è Comuniko AAC

**Comuniko AAC** è un'applicazione web monolitica, leggera e ad accesso immediato, creata per convertire frasi in strisce e tessere di CAA strutturate secondo criteri pedagogici rigorosi. 

Non si limita a generare simboli, ma fa da ponte verso l'autonomia nella letto-scrittura grazie a funzioni integrate di **fading (dissolvenza)**, **pregrafismo tratteggiato** e **stampa su carta** ottimizzata per i quaderni operativi[cite: 1, 2, 5].

---

## 🚀 Caratteristiche Principali

* **Chiave Fitzgerald Rigorosa:** categorizzazione grammaticale automatica delle tessere con codifica cromatica uniforme[cite: 2, 3]:
  * 🟡 **Giallo:** Soggetti, persone e pronomi[cite: 3].
  * 🟢 **Verde:** Verbi e azioni coniugate[cite: 3].
  * 🟠 **Arancione:** Sostantivi, oggetti, cibi e luoghi[cite: 3].
  * 🔵 **Azzurro:** Aggettivi qualificativi, colori e stati emotivi[cite: 3].
  * 🌸 **Rosa:** Formule sociali e saluti di cortesia[cite: 3].
  * ⚪ **Bianco:** Connettivi, articoli e preposizioni[cite: 3].
  * *Controllo manuale rapido della categoria direttamente sulla tessera[cite: 3].*
* **Scaffolding e Didattica del Fading:**
  * **Testo Pieno:** font ad alta leggibilità (`Fredoka` / `Nunito`)[cite: 1, 3].
  * **Tratteggiato (Ripassa):** caratteri puntinati/tratteggiati per il pregrafismo a matita[cite: 1, 3].
  * **Solo Trattini:** maschera il testo lasciando solo la guida per il conteggio delle lettere (`_ _ _ _`), stimolando la scrittura autonoma[cite: 1, 3].
  * **Slider Fading (100% → 0%):** dissolvenza graduale della traccia alfabetica per disancorare l'alunno dal modello visivo[cite: 1, 3].
* **Simboli ARASAAC & Vocabolario Personale:**
  * Integrazione diretta con le API ufficiali ARASAAC con ricerca sinonimi e alternative[cite: 1, 2, 4].
  * Possibilità di caricare fotografie reali (ambiente classe, compagni, oggetti quotidiani) salvate in memoria locale[cite: 1, 2, 4].
* **Sintesi Vocale Multilingua Avanzata (TTS):**
  * Supporto vocale per 5 lingue: Italiano 🇮🇹, Inglese 🇬🇧, Spagnolo 🇪🇸, Francese 🇫🇷, Tedesco 🇩🇪[cite: 1, 4].
  * Algoritmo di selezione automatica delle voci neurali/potenziate del dispositivo con evidenziazione visiva della tessera letta (`tts-active`)[cite: 1, 4].
* **Stampa & PDF per la Didattica Materiale:**
  * **Striscia Continua:** sequenza orizzontale da incollare intera su banco o quaderno[cite: 1, 5].
  * **Griglia da Ritaglio (✂):** tessere perimetrate da linee tratteggiate e icone a forbice per attività manipolative e sviluppo della motricità fine[cite: 1, 5].
* **Interazione Ibrida Desktop & Touch:**
  * Supporto drag & drop su PC e tramite tocco su tablet/LIM/smartphone[cite: 1, 4].
  * Installabile come **Progressive Web App (PWA)** direttamente sulla schermata Home senza passare da store commerciali.

---

## 🛡️ Privacy & Conformità Scuola (Zero Server, Zero Cloud)

Comuniko AAC è stato progettato nel pieno rispetto delle normative sulla tutela dei minori e del GDPR scolastico:
1. **Elaborazione 100% Locale:** l'applicazione gira interamente all'interno del browser dell'utente.
2. **Nessun Server Esterno:** nessun testo digitato, nominativo di alunno o foto caricata viene trasmesso o registrato su server di terze parti[cite: 1, 2].
3. **Persistenza Offline:** il vocabolario personale risiede unicamente nel `localStorage` del browser utilizzato[cite: 1, 2].
4. **Nessun tracciamento:** zero cookie di profilazione, zero annunci pubblicitari, zero script di telemetria[cite: 1, 2].

---

## 💻 Installazione ed Esecuzione Locale

Essendo strutturato come **monolite a file singolo** (`index.html`), non necessita di Node.js, server web dedicati o comandi di compilazione[cite: 1, 2]:

1. Clona il repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<tuo-username>/<nome-repository>.git
