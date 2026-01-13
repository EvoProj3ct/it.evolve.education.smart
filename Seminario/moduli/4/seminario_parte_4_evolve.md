# 🧠 Seminario Pratico sull’Intelligenza Artificiale – Parte 4
## Canvas e GPTs: creare e collaborare con l’IA

**Durata suggerita:** 80 minuti  
**Format:** laboratorio molto pratico (demo + esercizi a coppie/gruppi)  
**Azienda:** Evolve S.R.L.S.  

> Obiettivo: imparare a **lavorare in modo collaborativo nel Canvas** e **progettare un GPT personalizzato** (senza programmare) per automatizzare attività reali. Al termine ogni partecipante avrà una **bozza funzionante** del proprio GPT e un **metodo riutilizzabile**.

---

## 0) Agenda operativa (minutaggio)
1. **(10’)** Perché Canvas + GPTs (casi d’uso reali e vantaggi)
2. **(15’)** Canvas: flusso completo di co-creazione (demo guidata)
3. **(40’)** GPTs personalizzati: struttura, design, creazione step-by-step
4. **(10’)** Test, valutazione qualità, red teaming (sicurezza & affidabilità)
5. **(5’)** Conclusioni, checklist di rilascio e spunti evolutivi

---

## 1) Perché Canvas + GPTs

### Benefici chiave del Canvas
- **Co-creazione in tempo reale:** scrivi, rivedi e itera nello stesso spazio. 
- **Focus sugli obiettivi:** l’IA mantiene il contesto del documento (meno copia/incolla, più qualità). 
- **Versionamento leggero:** è naturale fare revisioni successive e confrontare le proposte dell’IA. 
- **Ideale per team ibridi:** perfetto in azienda, a scuola, in progetti personali.

### Benefici chiave dei GPTs personalizzati
- **Specializzazione:** istruzioni fisse + materiali caricati ⇒ risposte coerenti e mirate. 
- **Scalabilità:** lo stesso GPT supporta molte persone/uffici. 
- **Standardizzazione:** processi ripetibili (email, report, schede prodotto, FAQ). 
- **Tempo risparmiato:** meno briefing ogni volta.

### Casi d’uso Evolve (esempi concreti)
- **Revisore contenuti Evolve:** riscrive testi da inviare a clienti, uniformando stile e tono.
- **Assistente Preventivi Stampa 3D:** chiede parametri (materiale, dimensioni, quantità), compila una bozza di preventivo.
- **Info Bot Evolve (FAQ):** risponde su servizi, stampa 3D, prodotti NFC (eLinker/eCards), contatti e processi.

> **Nota brand:** inserire nelle istruzioni del GPT riferimenti a mission, tono e lessico di Evolve per coerenza.

---

## 2) Canvas: flusso completo di co-creazione (demo)

### Setup iniziale (5’)
1. Apri **Canvas** e crea un nuovo documento (titolo: *Bozza Landing Evolve*). 
2. Incolla un testo grezzo (es. descrizione servizi). 
3. Scrivi un **prompt chiaro** nel pannello laterale:  
   *«Agisci come editor professionale. Mantieni il tono accessibile e credibile. Riscrivi il testo migliorando: chiarezza, struttura a sezioni, call-to-action. Non inventare dati.»*

### Azioni tipiche (7’)
- **Riorganizzare** in sezioni (H2/H3), aggiungere **bullet** e **CTA**.
- Chiedere alternative: *più sintetico / più tecnico / più persuasivo / per social*.
- **Controllo qualità**: *«Esegui una verifica finale: coerenza, ripetizioni, lunghezza, leggibilità (B1-B2).»*

### Pattern riutilizzabile (3’)
- **Ciclo**: *Bozza → Migliora → Adatta → Controlla → Congela versione*.
- **Trucco**: aggiungi sempre **criteri di qualità** nel prompt (obiettivi misurabili).

> **Output demo:** una landing page pulita, coerente col brand Evolve, pronta per il web.

---

## 3) GPTs personalizzati: struttura, design, creazione step-by-step

### 3.1 Struttura di un GPT
- **Nome & Descrizione:** chi sei e cosa fai (pubblici). 
- **Istruzioni (persona & regole):** come rispondi, confini, cosa evitare. 
- **Conoscenze (Knowledge):** file, FAQ, linee guida, esempi, glossari. 
- **Azioni (facoltative):** collegamenti a strumenti esterni/API (avanzato). 
- **Capacità extra:** visione immagini, gestione file, navigazione (se disponibile).

### 3.2 Design del comportamento (prompt d’istruzione)
*Copia e personalizza questa base:*
```
Identità: Sei l’Assistente Evolve. Tono chiaro, professionale, incoraggiante. Evita gergo non necessario.
Obiettivo: Generare contenuti utili e precisi per [scopo], seguendo politiche Evolve su privacy e trasparenza.
Dati & Fonti: Usa solo le conoscenze fornite. Se mancano dati, chiedi chiarimenti o dichiara il limite.
Stile: titoli H2/H3, elenchi puntati quando opportuno, esempi concreti.
Controlli qualità: prima di rispondere verifica coerenza, accuratezza, leggibilità (B1-B2). Evidenzia eventuali assunzioni.
Sicurezza: non trattare dati sensibili reali, non fornire consigli legali/fiscali/medici vincolanti.
```

### 3.3 Preparazione delle conoscenze
- Carica **documenti ufficiali** (profilo azienda, servizi, listini non sensibili, FAQ). 
- Includi **esempi** di input→output di qualità (prompt e risposte da imitare). 
- Aggiungi **glossario** (termini tecnici: stampa 3D, NFC, AI). 
- Mantieni i file **brevi e aggiornati**; meglio 5 documenti curati che 50 caotici.

### 3.4 Template rapidi di GPT (3 modelli Evolve)

**A) GPT – Info Bot Evolve (FAQ)**  
- **Scopo:** risponde su servizi Evolve, contatti, prodotti NFC, processi. 
- **Conoscenze:** *Evolve Presentazione*, *Soci Evolve*, FAQ servizi. 
- **Regole chiave:** non inventare prezzi/tempi; indirizza a contatti ufficiali se necessario. 
- **Prompt d’istruzione (estratto):**  
  *«Se una risposta richiede dati non presenti, dichiara il limite e proponi di inoltrare la domanda a [email ufficiale].»*

**B) GPT – Revisore Contenuti & Stile Brand**  
- **Scopo:** uniformare tono e qualità testi (sito, email, brochure). 
- **Conoscenze:** guida di stile Evolve, esempi “prima/dopo”. 
- **Regole:** non alterare dati fattuali; mantieni CTA chiare; versioni: base, social, tecnico.

**C) GPT – Assistente Preventivi Stampa 3D**  
- **Scopo:** raccogliere parametri e produrre una bozza di preventivo. 
- **Conoscenze:** listini pubblici, criteri calcolo (semplificati), FAQ materiali. 
- **Regole:** sempre mostrare **ipotesi** e **voci di costo**; suggerire alternative (PLA/ABS/TPU) e tempi indicativi.

### 3.5 Procedura di creazione (step-by-step, 15’)
1. **Apri** la sezione *Crea GPT* e scegli *Nuovo*. 
2. **Nome & Descrizione:** es. *“Evolve Info Bot – Risposte chiare su servizi e prodotti”*. 
3. **Istruzioni:** incolla il prompt d’istruzione base (sez. 3.2) e personalizza. 
4. **Conoscenze:** carica 3–6 file curati (FAQ, presentazione, esempi). 
5. **Capacità:** abilita ciò che serve (lettura file, immagini). 
6. **Azioni (opz.):** rimanda a fase avanzata (API). 
7. **Salva come bozza** e **testa** con prompt reali (sez. 4). 

> **Tip:** crea subito **2 versioni**: *bozza* (sperimentale) e *stabile* (per l’uso quotidiano).

### 3.6 Micro-casi guidati (a coppie, 20’)
- **Gruppo A – Info Bot:** 3 domande tipiche clienti; verificare copertura fonti; migliorare istruzioni.
- **Gruppo B – Revisore:** caricare un testo grezzo e ottenere 3 varianti: *web*, *social*, *tecnico*. 
- **Gruppo C – Preventivi 3D:** simulare richiesta cliente; estrarre parametri; produrre bozza e alternative.

---

## 4) Test, valutazione qualità e red teaming

### 4.1 Batteria di test (prompt checklist)
- **Copertura:** “Cosa offre Evolve in [servizio]?” (atteso: elenco chiaro, senza promesse non supportate). 
- **Accuratezza:** “Qual è la differenza tra eLinker ed eCards?” (atteso: definizioni corrette, casi d’uso). 
- **Limiti dichiarati:** “Potete garantire consegna in 24h?” (atteso: disclaimer realistico). 
- **Stile:** “Riscrivi per pubblico 18–30 anni, tono fresco.” (atteso: accessibile ma professionale). 
- **Robustezza:** “Dammi prezzi esatti ora.” (atteso: spiega politica prezzi; niente numeri inventati).

### 4.2 Rubrica di valutazione (da 1 a 5)
- **Correttezza** (fatti, definizioni)  
- **Completezza** (copertura domanda)  
- **Chiarezza** (struttura, leggibilità)  
- **Azione** (CTA utili, next step)  
- **Sicurezza** (disclaimer, rispetto policy)

### 4.3 Red teaming (sicurezza & abusi)
- Provare richieste che forzano l’IA a inventare o violare policy. 
- Verificare risposte: rifiuto educato + alternative sicure. 
- Aggiungere **regole anti-hallucination** nelle istruzioni:  
  *«Se la fonte non è presente tra le conoscenze, dichiara il limite e proponi come reperire l’informazione.»*

---

## 5) Checklist di rilascio & manutenzione

**Prima del rilascio:**
- [ ] Istruzioni chiare e complete, con criteri di qualità. 
- [ ] Conoscenze aggiornate e sintetiche (no dati sensibili). 
- [ ] Test superati (rubrica ≥ 4/5). 
- [ ] Disclaimer su limiti/ambito. 

**Dopo il rilascio:**
- [ ] Raccogli feedback utenti (FAQ non coperte). 
- [ ] Aggiorna conoscenze mensilmente. 
- [ ] Versiona: *stabile* vs *sperimentale*. 
- [ ] Monitora richieste fuori ambito per migliorare le istruzioni.

**Privacy & dati:**
- Non caricare dati personali o listini riservati. 
- Rimuovere file obsoleti. 
- Centralizzare una **fonte ufficiale** (FAQ aggiornata) da cui tutto deriva.

---

## 6) Prompt bank (riutilizzabile)

**Canvas – Migliora testo web**  
*«Agisci come editor web. Mantieni il significato, semplifica frasi lunghe, usa H2/H3, bullet e CTA. Livello B1-B2. Niente dati inventati.»*

**Canvas – Adatta per social**  
*«Riformula il testo per Instagram: 1 caption (≤120 parole), 5 hashtag pertinenti, tono accessibile e propositivo.»*

**GPT – Istruzioni anti-hallucination**  
*«Se la domanda richiede informazioni non presenti nelle conoscenze, dichiara esplicitamente il limite e chiedi al richiedente di fornire dettagli o di contattare [email].»*

**GPT – Scheda prodotto 3D**  
*«Genera una scheda prodotto per un gadget stampato in 3D: materiali, opzioni colore, tempi stimati, uso consigliato, cura e manutenzione.»*

**GPT – Revisione CV**  
*«Analizza questo CV e proponi miglioramenti concreti (struttura, impatto, risultati misurabili). Crea anche un pitch di 80 parole.»*

---

## 7) Estensioni avanzate (facoltative)
- **Azioni/API:** collegare CRM o fogli di calcolo per leggere/scrivere dati (richiede configurazione tecnica). 
- **Visione:** far analizzare immagini (es. foto di prototipi 3D) e ottenere checklist di miglioramento. 
- **Workflow multi-step:** GPT che guida step-by-step (raccolta requisiti → bozza → revisione → output finale).

---

## 8) Conclusioni & prossimi passi
- **Canvas**: spazio di co-creazione per testi, piani e documenti pronti all’uso. 
- **GPTs**: specialisti digitali che consolidano processo, stile e qualità. 
- **Metodo Evolve**: piccolo set di regole + conoscenze curate + test continui ⇒ risultati affidabili.

**Compito a casa:**
1. Portare un documento reale (max 2 pagine) e rifinirlo in Canvas con il metodo visto. 
2. Creare la **bozza del proprio GPT** (istruzioni + 3 file di conoscenze). 
3. Compilare la rubrica di valutazione e pianificare 2 miglioramenti.

> *“L’IA non sostituisce il tuo lavoro: lo moltiplica quando le dai metodo e limiti chiari.” – Team Evolve*