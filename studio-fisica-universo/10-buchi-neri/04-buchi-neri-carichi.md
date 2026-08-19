# 04 — Buchi neri carichi e il teorema no-hair

## 1. Perché ci interessa

Per completezza teorica, la relatività generale accoppiata all'elettromagnetismo ammette anche soluzioni per buchi neri con **carica elettrica**. Non sono realistici in astrofisica (un buco nero carico attirerebbe rapidamente cariche opposte dal plasma circostante e si neutralizzerebbe in tempi brevissimi), ma sono fondamentali per due motivi: completano il quadro teorico, e la soluzione carica e rotante (Kerr-Newman) è, in un preciso senso matematico, **la soluzione più generale possibile** per un buco nero stazionario.

## 2. Reissner-Nordström: carica senza rotazione

Per un buco nero di massa M e carica elettrica Q, non rotante, la metrica di Reissner-Nordström (Hans Reissner 1916, Gunnar Nordström 1918) ha due raggi caratteristici:

```
r± = GM/c² ± √[(GM/c²)² − GQ²/(4πε₀c⁴)]
```

Notare la somiglianza formale con i due orizzonti di Kerr (file 03): non è un caso — entrambe le formule derivano dalla stessa struttura matematica generale.

- Se **GQ²/(4πε₀c⁴) < (GM/c²)²** → due orizzonti distinti (r+ orizzonte esterno vero, r− orizzonte di Cauchy interno), come Kerr.
- Se sono uguali → caso "estremale": i due orizzonti coincidono.
- Se la carica è troppo grande rispetto alla massa → nessun orizzonte, singolarità nuda (di nuovo, violazione della censura cosmica: la natura sembra evitarlo).

## 3. Kerr-Newman: il caso più generale (massa + rotazione + carica)

La soluzione di **Kerr-Newman** (1965) descrive un buco nero con massa M, momento angolare J e carica Q, tutti e tre insieme. È la soluzione stazionaria e asintoticamente piatta più generale nota per un buco nero in relatività generale + elettromagnetismo classico.

## 4. Il teorema "no-hair" (niente capelli)

Questo è uno dei risultati concettualmente più profondi (e affascinanti) sui buchi neri, dimostrato in vari passaggi da Israel, Carter, Hawking e altri tra il 1967 e il 1975:

> **Un buco nero stazionario (che ha "smesso di cambiare") in relatività generale è completamente determinato da sole tre quantità: massa M, momento angolare J, carica elettrica Q. Nient'altro.**

"No-hair" (nessun capello) è un modo scherzoso di dire: qualunque altro dettaglio ("capello") della materia che è collassata per formarlo — di che elemento chimico era fatta, che forma aveva, se conteneva informazioni scritte, la sua composizione esatta — **viene completamente perso** dal punto di vista dello spaziotempo esterno. Due buchi neri con la stessa M, J, Q sono **matematicamente identici** in ogni loro proprietà esterna misurabile, indipendentemente da come si sono formati.

### Perché questo è sorprendente e importante

Confrontalo con qualunque altro oggetto fisico "macroscopico": una stella ha una composizione chimica, una struttura interna a strati, un campo magnetico complicato dovuto alla sua storia — tutte informazioni che, in linea di principio, potresti "leggere" osservandola con cura. Un buco nero no: ha cancellato quasi ogni informazione tranne tre numeri.

Questo fatto è **esattamente il seme del paradosso dell'informazione** (file 07): se un buco nero non rotante, non carico, di massa M formato da una collezione di libri di fisica è indistinguibile da uno identico formato da un uguale massa di gas casuale, dov'è finita l'informazione contenuta nei libri? La meccanica quantistica dice che l'informazione non si distrugge mai; il teorema no-hair sembra dire che, macroscopicamente, sì. La tensione tra queste due affermazioni è uno dei problemi aperti più importanti della fisica teorica, e ci torneremo con tutti gli strumenti necessari nel file 07.

## 5. Un chiarimento tecnico importante

Il teorema no-hair vale rigorosamente per soluzioni **stazionarie** (cioè che non cambiano più nel tempo, "buchi neri a riposo") della relatività generale classica accoppiata a campi semplici (elettromagnetismo). Non è (ancora) un teorema dimostrato in modo completamente generale per tutte le possibili teorie della gravità o per tutti i possibili campi di materia — esistono varianti teoriche ("hairy black holes") studiate in contesti più esotici. Ma per l'astrofisica reale (relatività generale + Modello Standard delle particelle), no-hair è considerato saldamente vero per buchi neri stazionari.

## 6. Cosa NON dice questo file

- Non spiega ancora come si "perde" davvero l'informazione a livello quantistico — serve la radiazione di Hawking (file 06) e poi il paradosso vero e proprio (file 07).
- Non tratta buchi neri **non stazionari** (in fase di formazione o fusione): lì la geometria è dinamica e molto più complicata (si studia con la relatività numerica — simulazioni al computer delle equazioni di Einstein).

## 7. Per andare oltre subito
- Wald, *General Relativity*, cap. 12 — trattazione rigorosa del teorema no-hair (i cosiddetti "teoremi di unicità").
- Chandrasekhar, *The Mathematical Theory of Black Holes* — il testo classico e più completo su tutte le soluzioni esatte (Schwarzschild, Kerr, Reissner-Nordström, Kerr-Newman), livello avanzato.
