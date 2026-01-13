# 🧠 Seminario Pratico sull’Intelligenza Artificiale – Parte 2
## Come ragiona l’IA e come dialogare con lei

### Introduzione
Ben ritrovati! Dopo aver esplorato nella prima parte cos’è l’Intelligenza Artificiale e come usarla in modo consapevole, entriamo ora **nel cuore del funzionamento e della comunicazione con l’IA**.  
Capire come “pensa” e come “dialoga” un modello come ChatGPT o Gemini è fondamentale per ottenere risultati realmente utili e precisi.

---

## 1️⃣ Come “pensa” un modello linguistico

Un modello linguistico (LLM – *Large Language Model*) non “pensa” come un essere umano: **prevede**.  
Analizza miliardi di testi e costruisce risposte calcolando **quale parola è più probabile venga dopo l’altra** in base al contesto.

> 💡 In altre parole, l’IA non sa cosa è vero o falso: sa cosa è **probabile**.

### 🔍 Esempio intuitivo
Immagina di ricevere la frase: “C’era una volta un…”  
Tu probabilmente penserai a “principe”, “castello”, “drago” o “bambino”.  
L’IA fa esattamente lo stesso: completa la frase in modo coerente con miliardi di esempi visti in passato.

### 🧠 Ma allora è solo statistica?
Non proprio. L’IA non si limita a contare parole: **riconosce relazioni semantiche**, cioè significati.  
Sa che “gatto” e “cane” sono animali, ma anche che spesso “miagola” segue “gatto” e “abbaia” segue “cane”.

---

## 2️⃣ Il concetto di token e contesto

Ogni frase che scriviamo viene divisa in **token**, cioè piccoli pezzi di testo (parole o parti di parole).  
Ogni modello ha un **limite di token**, che definisce quanto testo può “ricordare” contemporaneamente.

> 💬 Se il modello dimentica parte della conversazione, non è distratto: ha esaurito lo spazio di memoria temporanea.

### ⚙️ Esempio pratico
Se un modello ha 16.000 token di contesto, equivale a circa **10–12 pagine di testo**.  
Oltre quella soglia, le parti più vecchie vengono “dimenticate” per lasciare spazio alle nuove.

---

## 3️⃣ Il Prompt: la chiave del dialogo

La qualità delle risposte dell’IA dipende **da come formuliamo la domanda**.  
Questa domanda, nel linguaggio dell’IA, si chiama **prompt**.

Un prompt efficace segue la formula:

> 🎯 **Ruolo → Obiettivo → Contesto → Output atteso**

### 🔹 Esempio generico
> “Agisci come un esperto di marketing. Scrivi un breve testo promozionale per un nuovo ristorante vegano, tono amichevole e professionale.”

📋 Qui l’IA sa:
- **Ruolo:** esperto di marketing;
- **Obiettivo:** scrivere un testo promozionale;
- **Contesto:** nuovo ristorante vegano;
- **Output:** tono amichevole e professionale.

> 💡 Più informazioni utili forniamo, più la risposta sarà mirata e coerente.

---

## 4️⃣ Errori comuni nel prompting

Molti utenti, soprattutto all’inizio, commettono piccoli errori che portano a risultati imprecisi o troppo generici.

### 🚫 Errori frequenti
- Scrivere domande troppo vaghe (es. “Parlami dell’IA”).
- Non specificare il tono o il formato.
- Non dare un contesto sufficiente.
- Fare più richieste diverse in un unico prompt.

### ✅ Soluzioni
- Essere **chiari e specifici**.
- Indicare **il ruolo** del modello (es. “Agisci come un insegnante”).
- Usare **passaggi numerati** se si richiede un processo.
- Chiedere **un riepilogo o un controllo finale** del risultato.

> ✍️ Esempio: “Correggi questo testo ma mantieni il tono informale e spiega le modifiche.”

---

## 5️⃣ Prompt di controllo e miglioramento

Un buon modo per ottenere risultati migliori è **usare il modello come revisore di sé stesso**.

### 🔁 Prompt di controllo
> “Rileggi la tua risposta e migliorala rendendola più sintetica e diretta.”

Oppure:
> “Ora riformula il testo in uno stile più tecnico e aggiungi esempi concreti.”

> 💡 L’IA può riscrivere, migliorare, ampliare o verificare ciò che ha appena prodotto.

---

## 6️⃣ ChatGPT vs Gemini: differenze pratiche

Entrambi sono modelli linguistici generativi, ma con **filosofie e punti di forza diversi**.

| Aspetto | ChatGPT | Gemini |
| -------- | -------- | ------- |
| Creatività testuale | 🔹 Eccellente per scrittura, storytelling, copywriting | 🔸 Buona, ma più sintetica |
| Accesso ai dati aggiornati | Solo se collegato al Web | Integrato di default |
| Gestione immagini | Tramite DALL·E o analisi visiva | Nativa su immagini e grafici |
| Personalizzazione GPTs | ✅ Crea GPT personalizzati | 🚧 Non ancora disponibile |
| Interfaccia collaborativa | Canvas, progetti, salvataggi | Interfaccia Google Workspace |

> ⚖️ In sintesi: ChatGPT è ottimo per la **creazione e co-creazione di contenuti**, Gemini eccelle nella **ricerca e integrazione dei dati**.

---

## 7️⃣ Esercizio pratico: riscrivere un prompt

### ✍️ Fase 1: prompt libero
Scrivi un prompt spontaneo su un argomento che ti interessa.  
Esempio: “Scrivi un post su Instagram per promuovere una pizzeria.”

### 🔁 Fase 2: applica la formula guidata
> “Agisci come un social media manager. Scrivi un post su Instagram per promuovere una pizzeria artigianale nel centro di Roma, tono allegro e accattivante, massimo 80 parole.”

### 🔍 Fase 3: confronto
Confrontiamo le due risposte e analizziamo insieme **quanto cambia la qualità del risultato**.  
L’obiettivo è capire che **non serve chiedere di più, ma chiedere meglio.**

---

## 8️⃣ Tecnica del Prompt Step-by-Step

Un approccio avanzato ma intuitivo consiste nel dividere le richieste in **fasi successive**, aiutando il modello a concentrarsi su un compito alla volta.

> 💡 “Prima genera la scaletta. Poi scrivi il testo per il punto 1. Poi passa al punto 2.”

Questo metodo migliora:
- la **precisione**;
- la **coerenza** tra le parti;
- la **qualità complessiva del risultato**.

---

## 🧩 Attività interattiva

### Esercizio di gruppo
Ognuno scrive un prompt seguendo la formula Ruolo → Obiettivo → Contesto → Output.  
Poi, in piccoli gruppi, si confrontano i risultati ottenuti su ChatGPT e (se possibile) su Gemini.

### Discussione guidata
- Cosa ha funzionato meglio?
- Quali differenze emergono tra i due modelli?
- Come possiamo migliorare ulteriormente i prompt?

---

## 🎯 Obiettivi della seconda parte
Al termine di questa sezione, i partecipanti avranno imparato a:

- comprendere in modo intuitivo **come ragiona un modello linguistico**;
- scrivere **prompt chiari, strutturati e mirati**;
- riconoscere e correggere errori comuni;
- sfruttare **ChatGPT e Gemini** secondo i loro punti di forza.

> 🚀 Nella terza parte entreremo nel mondo **pratico dei file**: scopriremo come far lavorare l’IA su documenti, PDF ed Excel reali.

