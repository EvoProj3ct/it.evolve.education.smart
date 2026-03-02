# SMART — Modulo 03 (S-BASIC v2.2)

## Privacy e dati personali nell’era dell’Intelligenza Artificiale

---

# PRINCIPIO APPLICATO

Modulo progettato secondo il **Principio di Neutralità Strutturale e Adattabilità Guidata**.

* Struttura trasversale rispetto al target.
* Include indicazioni operative per declinazione (PMI, PA, scuola/studenti, cittadini, enti culturali).
* Documento autosufficiente e pronto per erogazione.

---

## 0. Metadati del modulo

* **ID Modulo:** `SB-03`
* **Titolo Modulo:** Privacy e dati personali nell’era dell’Intelligenza Artificiale
* **Track / Livello:** `S-BASIC`
* **Tipologia:** Fondativo
* **Durata target:** 60 minuti

  * **Variante breve:** 30 minuti
  * **Variante estesa:** 90–120 minuti
* **Prerequisiti:** Modulo 01 e 02 consigliati (non obbligatori)
* **Collocazione nel percorso:** Dopo “realtà/limiti” e “responsabilità”, prima dei moduli pratici
* **Tag tematici:** privacy, dati personali, dati sensibili, minimizzazione, anonimizzazione, rischio, responsabilità
* **Versione:** v2.2
* **Data:** (da compilare)
* **Stato:** Pronto
* **Autore/Curatore:** (da compilare)

---

## 1. Scopo del modulo

Costruire una competenza di base: **usare strumenti di IA senza esporre dati personali o sensibili inutilmente**.

Il modulo serve a:

* chiarire perché i dati sono centrali nel funzionamento di molti sistemi digitali e di IA
* distinguere tra dati generici, personali e sensibili (in modo pratico, non giuridico)
* insegnare una regola operativa: **minimizzare, anonimizzare, controllare**
* prevenire abitudini rischiose (copio/incolla, invio documenti reali, condivisione di terzi)

È un modulo “di sicurezza quotidiana” e prepara all’uso pratico dell’IA.

---

## 2. Descrizione sintetica

Il modulo spiega il rapporto tra IA e dati personali, con un taglio pratico.

I partecipanti imparano a:

* riconoscere quali dati stanno inserendo (anche indirettamente)
* capire perché “più dettagli” non significa sempre “meglio”, se il dettaglio contiene dati identificativi
* applicare alternative sicure (dati fittizi, mascheramento, riassunti, variabili)

Il focus non è sulla normativa, ma su comportamenti concreti e ripetibili.

---

## 3. Pubblico e contesto (multi-target operativo)

### Pubblici possibili

* PMI
* Pubblica Amministrazione
* Docenti / Studenti
* Cittadini
* Enti culturali

### Livello

Base – orientato a consapevolezza e metodo.

### Declinazioni operative per target

**PMI**

* Focus su: clienti, fornitori, dipendenti, documenti (mail, preventivi, ticket, CRM)
* Rischio tipico: inserire dati reali per ottenere una risposta “più precisa”

**PA**

* Focus su: dati di cittadini, pratiche, comunicazioni, atti, richieste
* Rischio tipico: utilizzare IA per sintetizzare o riscrivere testi con dati identificativi

**Scuola / Studenti**

* Focus su: dati di minori, contesto scolastico, consegne
* Rischio tipico: condividere informazioni personali in modo inconsapevole

**Cittadini / Enti culturali**

* Focus su: salute, finanze, famiglia, documenti, messaggi
* Rischio tipico: chiedere consigli inserendo dettagli sensibili non necessari

---

## 4. Obiettivi didattici (misurabili)

Al termine del modulo il partecipante sarà in grado di:

### Comprendere

1. Spiegare perché i dati sono un elemento “delicato” quando si usa l’IA.
2. Distinguere tra dato generico, dato personale e dato sensibile (con esempi).
3. Comprendere il principio di minimizzazione: “inserisco solo ciò che serve”.

### Saper fare

1. Riconoscere dati personali “nascosti” in testi apparentemente innocui.
2. Trasformare un prompt rischioso in un prompt sicuro (anonimizzato).
3. Applicare una checklist rapida prima di incollare testo/documenti.

### Saper valutare/decidere

1. Decidere quando NON usare uno strumento di IA con un contenuto reale.
2. Scegliere un’alternativa sicura (dati fittizi, mascheramento, descrizione astratta).

---

## 5. Struttura didattica dettagliata

> Il modulo è progettato per funzionare anche senza demo.

### BLOCCO 1 — Attivazione: “Che cosa sto dando davvero?” (10 min)

**Messaggio chiave:** spesso condividiamo più dati del necessario, senza accorgercene.

**Azione docente (plug & play):**

1. Domanda al pubblico:

   * “Quando chiedete aiuto a uno strumento digitale, incollate testi reali?”
2. Mostrare 3 esempi rapidi (su slide o letti):

   * email con firma completa
   * screenshot di chat
   * estratto di documento con nomi
3. Conclusione: “Il rischio non è solo ciò che scrivi: è ciò che il testo **contiene**.”

**Declinazioni:**

* PMI: “mail cliente, ticket, preventivo”
* PA: “richiesta cittadino, pratica, atto”
* Scuola: “consegna studente, dati minore”
* Cittadini: “referto, contratto, messaggio”

---

### BLOCCO 2 — Dati: tre categorie operative (15 min)

**Messaggio chiave:** non tutti i dati sono uguali.

Definizioni pratiche (non legali):

1. **Dati generici:** informazioni non riconducibili a persone reali (es. “una persona”, “una città grande”).
2. **Dati personali:** informazioni che identificano o rendono identificabile qualcuno (nome, email, telefono, indirizzo, dettagli unici).
3. **Dati sensibili/critici:** informazioni che possono causare danno se diffuse o usate impropriamente (salute, minori, finanze, dati di terzi, valutazioni, numeri documento, pratiche).

**Azione docente:**

* Chiedere: “Dove mettereste ‘email con firma’?”
* Far emergere che spesso contiene dati personali.

---

### BLOCCO 3 — Perché il dettaglio aumenta anche il rischio (10 min)

**Messaggio chiave:** più dettagli = output più pertinente, ma può significare più esposizione.

Tre concetti semplici:

1. Il contesto è utile, ma può essere sostituito da variabili.
2. Molti risultati si ottengono con esempi fittizi.
3. Se l’informazione è sensibile, il beneficio deve superare il rischio.

**Azione docente:**

* Mostrare una frase:

  * “Scrivi una risposta a Mario Rossi, codice fiscale…, residente…”
* Poi la versione sicura:

  * “Scrivi una risposta a un cliente [NOME], con richiesta [TIPO], tono [TONO].”

---

### BLOCCO 4 — Rischi tipici (15 min)

**Messaggio chiave:** il rischio non è solo “hacker”: spesso è abitudine e distrazione.

Cinque rischi pratici:

1. **Condivisione involontaria di dati (copio/incolla)**
2. **Dati di terzi senza consenso**
3. **Persistenza / tracciabilità insufficiente (non so cosa succede al testo)**
4. **Re-identificazione** (anche se tolgo il nome, altri dettagli identificano)
5. **Uso improprio dell’output** (es. riscrivere un documento sensibile e inviarlo)

**Declinazioni rapide:**

* PMI: clienti/fornitori/dipendenti
* PA: cittadini/pratiche
* Scuola: minori
* Cittadini: salute/finanze

---

### BLOCCO 5 — Metodo minimo: “3M + 2C” (10 min)

**Messaggio chiave:** una regola operativa riduce la probabilità di errore.

Introdurre la checklist memorizzabile:

**3M**

1. **Minimizza:** inserisci solo ciò che serve.
2. **Maschera:** sostituisci dati reali con variabili.
3. **Modella:** usa esempi fittizi o astratti quando possibile.

**2C**

4. **Controlla:** rileggi il testo per dati nascosti (firma, numeri, riferimenti).
5. **Conferma:** chiediti “potrei giustificare questa condivisione?”

**Azione docente:**

* Applicare 3M+2C su un esempio (vedi esercizio).

---

### BLOCCO 6 — Sintesi e ponte ai moduli successivi (5 min)

Take-away:

1. Prima di usare l’IA: riconosci i dati.
2. Se puoi: minimizza e maschera.
3. La privacy è una responsabilità, non un dettaglio.

Ponte:

* verso moduli di prompting/uso: “prompt buoni = anche prompt sicuri”.

---

## 6. Contenuto del modulo (testo guida per il docente)

### 6.1 Testo guida (strutturato)

Aprire con una frase semplice:

“L’IA non è pericolosa perché è ‘cattiva’. È rischiosa quando la usiamo senza accorgerci dei dati che stiamo condividendo.”

Spiegare che molti strumenti funzionano meglio con contesto, ma che il contesto può essere fornito in modo sicuro.

Fare una distinzione pratica:

* informazioni utili al problema (tipo richiesta, vincoli, tono, obiettivo)
* informazioni che identificano persone reali (spesso non necessarie)

Introdurre l’idea di “dati nascosti”:

* firme automatiche
* numeri di pratica
* indirizzi
* nomi in allegati

Chiudere con una regola:

“Se un dato non serve per ottenere un buon risultato, non deve entrare nel prompt.”

### 6.2 Errori e fraintendimenti comuni

* “Se tolgo il nome, ho risolto.” (spesso altri dettagli identificano)
* “Tanto è solo una bozza.” (la bozza può contenere dati reali)
* “Mi serve preciso, quindi devo incollare tutto.” (spesso bastano variabili)
* “Sono dati miei, posso sempre inserirli.” (anche dati propri possono essere sensibili)
* “Privacy = burocrazia.” (in realtà è gestione del rischio)

Formula correttiva:

“Più dati non significa più qualità. Significa più esposizione.”

---

## 7. Esempi e applicazioni pratiche (pronti)

### 7.1 Caso narrativo 1 — “Incolla e invia”

**Scenario:** una persona incolla un’email reale con firma e dettagli, chiede una riscrittura e poi invia il risultato.

**Obiettivo:** far emergere dati nascosti e rischio di terzi.

**Istruzioni per il relatore:**

* chiedere: “Quali dati personali ci sono qui dentro?”
* far elencare almeno 5 elementi.

**Declinazioni:**

* PMI: email cliente con ordine e riferimenti.
* PA: richiesta cittadino con numero pratica.
* Scuola: comunicazione con dati studente.
* Cittadini: richiesta su contratto/bolletta.

---

### 7.2 Caso narrativo 2 — “Stesso problema, dati fittizi”

**Scenario:** stesso obiettivo, ma usando variabili e dati neutri.

**Obiettivo:** mostrare che spesso si ottiene lo stesso risultato senza dati reali.

**Istruzioni:**

* presentare due prompt (rischioso vs sicuro) e confrontare.

---

### 7.3 Esempio dimostrativo (opzionale) — Prompt trasformato

**Obiettivo:** far vedere la trasformazione in tempo reale.

**Istruzioni:**

* prendere un prompt con dati
* trasformarlo con 3M+2C
* mostrare che l’output resta utile

**Variante senza strumenti:** usare due versioni stampate.

---

### 7.4 Contro-esempio — Dati sensibili “non necessari”

**Scenario:** richiesta di consiglio inserendo dettagli su salute/finanze/minori.

**Obiettivo:** riconoscere quando fermarsi e scegliere alternative.

Domanda guida:

* “Quale parte del dettaglio qui è superflua rispetto all’obiettivo?”

---

## 8. Attività, esercizi e interazione

### 8.1 Domande per il pubblico (pronte)

**Attivazione**

* Qual è l’ultima cosa “reale” che hai incollato in uno strumento digitale per farti aiutare?
* Quando hai fretta, cosa ti porta a incollare tutto?

**Verifica comprensione**

* Che differenza c’è tra dato personale e dato sensibile, in pratica?
* Quali sono tre “dati nascosti” tipici in un testo?

**Riflessione critica**

* In quali contesti l’errore di privacy sarebbe più grave?
* Qual è una piccola abitudine che puoi cambiare da subito?

---

### 8.2 Esercizio (1) — Classifica e riscrivi in modo sicuro (15 min)

**Obiettivo:** allenare riconoscimento dati + trasformazione in versione sicura.

**Modalità:** piccoli gruppi (3–5) oppure plenaria.

**Durata:** 15 minuti (10 lavoro + 5 restituzione).

**Materiale necessario:**

* una scheda con 10 elementi (vedi sotto)
* 2 prompt di esempio (rischioso vs da riscrivere)

**Parte A — Classificazione (8 min)**

Classificare ogni elemento come:

A) generico
B) personale
C) sensibile/critico

**Elementi (generici e riusabili):**

1. Nome e cognome
2. Email aziendale/personale
3. Numero di telefono
4. Indirizzo di casa
5. Numero documento / pratica
6. Informazione su salute
7. Informazione su minore
8. Informazione finanziaria (IBAN, reddito, debito)
9. Valutazione su una persona (“è incompetente”, “ha problemi”)
10. Dettaglio specifico che identifica indirettamente (azienda piccola + ruolo + città + evento)

**Parte B — Riscrittura sicura (7 min)**

Prendere un prompt rischioso (fornito dal docente) e trasformarlo con **3M+2C**.

Esempio prompt rischioso (da consegnare su scheda/slide):

“Riscrivi questa email a Mario Rossi (CF…), cliente che vive in…, che ha ordinato…, lamenta… e allega…”

Obiettivo: produrre versione sicura con variabili:

“Riscrivi una email a un cliente [NOME] che segnala [PROBLEMA] su [PRODOTTO/SERVIZIO]. Vincoli: tono [TONO], obiettivo [OBIETTIVO], lunghezza [LUNGHEZZA].”

**Output atteso:**

* tabella classificata
* 1 prompt riscritto in forma sicura

**Adattamento target (istruzioni):**

* PMI: usare esempi su cliente/ordine/preventivo.
* PA: usare esempi su richiesta/pratica/ufficio.
* Scuola: usare esempi su comunicazione scuola/famiglia e dati minori.
* Cittadini: usare esempi su referto/contratto/bolletta (senza dettagli reali).

---

### 8.3 Variante “senza strumenti” (obbligatoria)

Il modulo funziona senza demo.

Se necessario:

* usare schede stampate
* lavorare su prompt già preparati
* far riscrivere a mano o in gruppo

---

## 9. Azioni per il relatore (operativo)

### Da fare

* Rendere evidente che i dati sono spesso “nascosti” nei testi.
* Ripetere la regola: “se non serve, non entra nel prompt”.
* Usare la checklist 3M+2C come routine.
* Far lavorare su esempi fittizi (non chiedere casi reali del pubblico).

### Da evitare

* Linguaggio normativo o legale complesso.
* Tono allarmista.
* Esempi con dati reali o riconoscibili.
* Richieste al pubblico di condividere documenti personali.

### Modulazione del tono

* PMI: orientato a gestione rischio e reputazione.
* PA: orientato a responsabilità pubblica e dati di terzi.
* Scuola/studenti: orientato a tutela minori e consapevolezza.
* Cittadini: orientato a prudenza, sicurezza e abitudini.

---

## 10. Tempistiche

### Durata target (60 min)

* Attivazione e contesto (B1): 10 min
* Categorie dati (B2): 15 min
* Dettaglio vs rischio (B3): 10 min
* Rischi tipici (B4): 15 min
* Metodo 3M+2C + mini-applicazione (B5): 5 min
* Sintesi e ponte (B6): 5 min

> Opzione: se si vuole fare l’esercizio completo (15 min), ridurre B4 a 10 min e dedicare 15 min all’esercizio.

### Variante breve (30 min)

* Attivazione: 5 min
* Categorie dati: 10 min
* Metodo 3M+2C: 5 min
* Mini-esercizio (classifica 5 elementi + 1 riscrittura): 10 min

### Variante estesa (90–120 min)

Aggiungere:

* Esercizio completo (15 min) + restituzione (10 min)
* Due casi aggiuntivi (10–15 min)
* Focus su re-identificazione con esempi (10 min)
* Applicazione 3M+2C su 2 prompt diversi (10–15 min)

Esempio struttura 90 min:

* B1 10
* B2 15
* B3 10
* B4 10
* Esercizio 15
* Restituzione 10
* Re-identificazione 10
* Applicazione 3M+2C 5
* Sintesi 5

---

## 11. Materiali e output didattici

### Slide outline suggerito (12 slide)

1. Titolo e obiettivo
2. Perché i dati contano
3. “Che cosa sto dando davvero?” (attivazione)
4. Dati generici / personali / sensibili (definizioni)
5. Dati nascosti nei testi
6. Dettaglio vs rischio
7. Rischio 1–2 (con esempi)
8. Rischio 3–5 (con esempi)
9. Checklist 3M+2C
10. Esempio: prompt rischioso → sicuro
11. Esercizio (scheda)
12. Take-away e ponte

### Handout (1 pagina) – pronto contenuto

Titolo: “Privacy e IA – regole minime”

* Regola 1: Se non serve, non entra nel prompt.
* Regola 2: Maschera nomi, numeri, dettagli identificativi.
* Regola 3: Usa esempi fittizi quando possibile.

Checklist 3M+2C (in elenco).

Mini-tabella (10 elementi) con colonne: Generico / Personale / Sensibile.

### Materiali di supporto

* Scheda esercizio (classifica + riscrittura)
* 2 prompt stampati (rischioso e da trasformare)

---

## 12. Valutazione e verifica (leggera)

Domande finali:

1. Fai un esempio di “dato nascosto” in un testo.
2. Applica la regola “minimizza”: cosa toglieresti da questo prompt?
3. Quali sono 2 passi della checklist 3M+2C che userai da domani?

Criterio minimo:

* il partecipante riconosce dati personali e sa trasformare un prompt rischioso in versione sicura.

---

## 13. Accessibilità e inclusività

* Linguaggio semplice, esempi non settoriali.
* Evitare tecnicismi normativi.
* Attenzione particolare a minori e pubblico con bassa alfabetizzazione digitale.
* Dare esempi in più ambiti (lavoro, scuola, vita quotidiana).

---

## 14. Note operative (rafforzate)

* **Livello di difficoltà reale:** base.
* **Prerequisiti reali:** nessuno.
* **Assunzione progettuale:** pubblico eterogeneo; contesto variabile; strumenti eventualmente assenti.
* **Rischi da gestire in aula:**

  * alcuni partecipanti possono portare casi personali: prevenire e usare esempi fittizi.
  * evitare che il tema privacy diventi “solo normativa”: riportare sempre a comportamenti.
* **Attenzioni:**

  * non far condividere documenti reali
  * non far scrivere dati personali in esercizi
  * usare sempre variabili e dati inventati

---

## 15. Checklist di completezza

* Metadati completi
* Scopo e descrizione chiari
* Obiettivi misurabili
* Struttura a blocchi con azioni per docente
* Esempi declinabili + contro-esempio
* 1 esercizio con output atteso + adattamenti
* Variante senza strumenti
* Tempistiche complete (30/60/90+)
* Materiali pronti (slide outline + handout)
* Coerenza con Principio di Neutralità Strutturale e Adattabilità Guidata

✅ Modulo pronto per erogazione immediata.
