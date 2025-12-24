# 📚 Manuale di Gioco - Trivia Path

Benvenuti in **Trivia Path**, il party game dove la cultura incontra la strategia e l'imprevedibilità dell'Intelligenza Artificiale.
Non si tratta solo di rispondere correttamente: bisogna gestire il rischio, attaccare gli avversari e sopravvivere fino al duello finale.

---

## 🏆 Obiettivo del Gioco

Lo scopo è semplice: **rimanere l'ultimo giocatore in vita** o avere il punteggio più alto quando scade il tempo.

Ogni giocatore inizia con:
* **3 Vite** (Cuori) ❤️
* **0 Punti**
* **3 Aiuti Strategici**

---

## ❤️ Sistema delle Vite e Bonus

La sopravvivenza è la chiave.
* **Risposta Errata:** Perdi **1 Vita**.
* **0 Vite:** Sei eliminato dal gioco (Game Over per te).
* **BONUS VITA:** Se hai meno di 3 vite e rispondi correttamente a **5 domande di fila** (Streak), guadagni un cuore extra! ❤️➕

---

## 🧠 Svolgimento del Turno

1.  **La Domanda:** L'Host (IA) genera una domanda basata sulla categoria scelta o casuale.
2.  **L'Attesa:** Il testo appare a schermo. Puoi premere `SPAZIO` o fare `Click` per saltare l'animazione e l'audio.
3.  **La Risposta:** Seleziona una delle 4 opzioni col mouse.
4.  **La Conferma:** Ti verrà chiesto "Sei sicuro?". Puoi confermare o annullare.
5.  **Il Risultato:**
    * **Esatto:** Guadagni punti (+100 base) e l'Host festeggia.
    * **Sbagliato:** Perdi punti (-50 base), perdi una vita e l'Host ti deride.

---

## 🆘 Gli Aiuti (Lifelines)

Hai 3 aiuti a disposizione per tutta la partita. Usali con saggezza! Una volta usati, sono persi per sempre.

* **50:50:** L'IA elimina due risposte sbagliate, lasciandoti con il 50% di probabilità.
* **SWITCH (Cambio):** La domanda non ti piace? Cambiala! L'Host rivelerà la risposta della domanda scartata e te ne farà una nuova.
* **HINT (Indizio):** Chiedi un suggerimento all'IA. L'Host ti darà un indizio (a volte utile, a volte sarcastico) generato in tempo reale per aiutarti a ragionare.

> **Nota:** Gli aiuti rimangono disponibili anche durante il *Duello Finale* (se non li hai già usati!).

---

## 🎲 Eventi Speciali (Director AI)

Il gioco non è lineare! Un "Regista Virtuale" può attivare eventi speciali in qualsiasi momento (specialmente dopo il 5° turno).

### 💰 Betting (Scommesse)
Appare periodicamente o se sei molto indietro col punteggio.
Devi scommettere una percentuale dei tuoi punti attuali (**0%**, **50%** o **100% / All-In**).
* **Indovini:** Vinci la somma scommessa oltre ai punti della domanda.
* **Sbagli:** Perdi la somma scommessa oltre alla penalità standard.

### 🔥 Risk Mode (Rischio)
Se stai andando bene, l'Host potrebbe offrirti una sfida: una domanda **"Molto Difficile"** per **Punti Doppi (x2)**.
* Puoi **Accettare** (rischio alto, guadagno alto).
* Puoi **Rifiutare** (giochi una domanda normale).

### 😈 Malus Mode (Cattiveria)
La modalità d'attacco pura. Prima di rispondere, devi scegliere un **Avversario Vittima** (non puoi scegliere te stesso).
* **Indovini:** Non guadagni punti per te stesso (avrai solo il bonus streak), ma **la vittima perde 100 punti**.
* **Sbagli:** Il karma ti punisce! **Perdi 200 punti** dal tuo totale.

### 🥷 Steal Points (Furto)
Scegli un avversario a cui rubare direttamente dei punti.
* **Indovini:** Rubi una somma fissa (es. 300 punti) dal suo totale e li aggiungi al tuo.
* **Sbagli:** Regali quei punti alla vittima!

### ⏱️ Speedrun
Improvvisamente, il gioco accelera! Parte un conto alla rovescia di 10 secondi. Devi rispondere velocemente o il turno è perso (considerato come risposta errata o tempo scaduto).

---

## ⚔️ Il Duello Finale

Quando rimangono solo **2 Giocatori** in vita (o viene forzato):
1.  Lo sfondo diventa rosso (Allarme!).
2.  La musica diventa epica.
3.  Le domande diventano **immediatamente "Molto Difficili"**.
4.  È uno scontro all'ultimo sangue per decretare il vincitore.

---

## 🛠️ Modalità Debug (Novità)

Per testare le funzionalità, è presente un menu segreto per gli sviluppatori.
* **Tasto F3:** Apre/Chiude il Menu di Debug in sovrimpressione.
* Da questo menu puoi forzare l'attivazione di un evento specifico (es. Malus, Steal, Duello) al turno successivo.
* Se mancano giocatori per l'evento richiesto, il sistema aggiungerà automaticamente dei Bot.

---

## 🕹️ Comandi e Interfaccia

* **Mouse:** Navigazione nei menu, selezione risposte, uso aiuti.
* **Barra Spaziatrice:** Salta l'animazione del testo / Salta l'intro vocale dell'Host.
* **Rotellina Mouse:** Scorri la classifica se ci sono molti giocatori.
* **Pulsante PAUSA:** In alto a sinistra. Ferma il tempo e "congela" il gioco.
* **Tasto F3:** Menu Debug.

---
*Buona fortuna! Che la cultura (e un po' di fortuna) sia con te!*