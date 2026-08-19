# 05 — Termodinamica dei buchi neri

## 1. Perché ci interessa

Negli anni '70, un gruppo di fisici (Bekenstein, Hawking, Bardeen, Carter) scoprì qualcosa di sconcertante: le leggi che governano i buchi neri hanno **esattamente la stessa struttura matematica** delle quattro leggi della termodinamica classica. All'inizio si pensava fosse solo un'analogia formale curiosa. Oggi sappiamo — grazie alla radiazione di Hawking (file 06) — che **non è un'analogia: è la termodinamica vera**. I buchi neri sono oggetti termodinamici a tutti gli effetti, con una temperatura e un'entropia reali.

## 2. Le quattro leggi della termodinamica dei buchi neri

### Legge zero
> La gravità superficiale κ (surface gravity) è costante su tutto l'orizzonte degli eventi di un buco nero stazionario.

Analogo di: *in un sistema in equilibrio termico, la temperatura è uniforme ovunque*. Questo suggerisce che κ sia proporzionale a una temperatura.

### Prima legge
> dM = (κ/8πG) dA + Ω dJ + Φ dQ

dove A è l'area dell'orizzonte, Ω è la velocità angolare dell'orizzonte, Φ è il potenziale elettrico dell'orizzonte. Analogo di: *dE = T dS + (termini di lavoro)*. Confrontando i due, si legge che κ/8πG deve giocare il ruolo della "temperatura" e A il ruolo dell'"entropia" (a meno di costanti).

### Seconda legge (teorema dell'area di Hawking, 1971)
> In qualunque processo classico, l'area totale degli orizzonti degli eventi non può mai diminuire: dA ≥ 0.

Analogo diretto della seconda legge della termodinamica: *l'entropia totale di un sistema isolato non può mai diminuire*. Per esempio, quando due buchi neri si fondono, l'area dell'orizzonte del buco nero finale è sempre maggiore o uguale alla somma delle aree dei due orizzonti iniziali (questo è stato verificato sperimentalmente con le onde gravitazionali di LIGO, vedi file 09!).

### Terza legge
> È impossibile ridurre la gravità superficiale κ a zero con un numero finito di operazioni fisiche (cioè: non si può creare un buco nero "estremale" con un processo fisico realistico in un numero finito di passi).

Analogo di: *è impossibile raggiungere lo zero assoluto di temperatura con un numero finito di processi* (terzo principio della termodinamica).

## 3. Da analogia a realtà: l'entropia di Bekenstein-Hawking

Jacob Bekenstein, nel 1972-73 (allora dottorando), fece un salto concettuale audace: propose che l'area dell'orizzonte **fosse davvero** (a meno di una costante) l'entropia del buco nero, non solo per analogia matematica. La sua motivazione: se un buco nero non avesse entropia, si potrebbe violare la seconda legge della termodinamica gettandoci dentro oggetti ad alta entropia (es. gas caldo) e facendoli "sparire" dall'universo osservabile, riducendo l'entropia totale dell'universo. Servendo un'entropia del buco nero che cresce almeno quanto quella "ingoiata", la seconda legge viene salvata in una forma **generalizzata**:

```
S_generalizzata = S_esterna + S_buco_nero    e    dS_generalizzata ≥ 0 sempre
```

All'inizio Hawking stesso era scettico (se un buco nero ha una temperatura reale, per le leggi della termodinamica *deve* emettere radiazione — ma "nulla può uscire da un buco nero classico"!). Fu proprio cercando di dimostrare che Bekenstein si sbagliava che Hawking, nel 1974, scoprì che i buchi neri **emettono davvero radiazione termica** — la scoperta che oggi porta il suo nome (file 06). Un bellissimo esempio di come un tentativo di confutazione abbia portato a una delle scoperte più importanti della fisica teorica del XX secolo.

## 4. La formula dell'entropia

```
S = (k_B c³ A) / (4 G ħ)
```

dove:
- k_B = costante di Boltzmann
- A = area dell'orizzonte degli eventi
- G = costante di gravitazione
- ħ = costante di Planck ridotta

Per un buco nero di Schwarzschild, A = 4πRs² = 4π(2GM/c²)², quindi:

```
S = (4π k_B G M²) / (ħ c)
```

**L'entropia cresce col quadrato della massa.** Ed è enorme: un buco nero con la massa del Sole ha un'entropia dell'ordine di 10⁷⁷ k_B — più di 20 ordini di grandezza superiore all'entropia termica del Sole stesso prima di collassare. Questo dato da solo dice che i buchi neri sono, per unità di massa, **gli oggetti a più alta entropia conosciuti nell'universo** — un fatto centrale in cosmologia quando si parla della "freccia del tempo" dell'universo.

## 5. Un fatto profondo: l'entropia è proporzionale all'AREA, non al VOLUME

In ogni sistema fisico ordinario che conosci (un gas in una scatola, per esempio), l'entropia è **estensiva**: raddoppiando il volume e la quantità di materia, raddoppia l'entropia — è proporzionale al **volume**. Per un buco nero, l'entropia è proporzionale all'**area della sua superficie di confine**, non al suo volume interno.

Questo fatto — scoperto qui, per i buchi neri, negli anni '70 — è diventato uno degli indizi più importanti verso l'idea che **tutta l'informazione fisica contenuta in una regione di spazio possa essere codificata sulla sua superficie di confine**, e non nel suo "interno": è il seme del **principio olografico** ('t Hooft, Susskind, anni '90), che vedremo nel file 08 e nel Modulo 11. Un'idea che oggi è centrale in molta della fisica teorica di frontiera (corrispondenza AdS/CFT).

## 6. Cosa NON dice ancora questo file

- Non spiega *perché* fisicamente un buco nero abbia una temperatura reale — questo richiede la meccanica quantistica dei campi vicino all'orizzonte, che è il file successivo.
- Non risolve il problema di *cosa siano microscopicamente* gli stati che contano per S (in meccanica statistica, S = k_B ln(numero di microstati) — quali sono i "microstati" di un buco nero? È una domanda tuttora aperta nella sua generalità, anche se la teoria delle stringhe ha dato un conteggio esplicito e corretto per certe classi di buchi neri estremali — Strominger & Vafa, 1996, un risultato spettacolare che vedremo nel Modulo 11).

## 7. Per andare oltre subito
- Bekenstein, J. (1973), *Black Holes and Entropy*, Physical Review D — l'articolo originale (ricercabile su Google Scholar / arXiv per riassunti).
- Wald, *General Relativity*, cap. 12.5 (leggi della meccanica dei buchi neri).
- Susskind & Lindesay, *An Introduction to Black Holes, Information and the String Theory Revolution* — libro pensato apposta per collegare termodinamica dei buchi neri, informazione e stringhe ad un livello accessibile ma serio.
