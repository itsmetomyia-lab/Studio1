# 06 — Radiazione di Hawking, approfondita

## 1. Perché ci interessa (e perché questo file va oltre quello che sapevi già)

Sai già, a livello concettuale, che un buco nero emette radiazione di Hawking. Questo file vuole portarti oltre la spiegazione "da bar" più comune — che in realtà, come vedrai, è imprecisa — verso quella corretta.

## 2. La spiegazione popolare (e perché è fuorviante)

La spiegazione che si sente più spesso è: *"il vuoto quantistico crea continuamente coppie particella-antiparticella virtuali; se questo accade appena fuori dall'orizzonte, a volte una delle due cade dentro e l'altra scappa, diventando radiazione reale."*

Hawking stesso ha usato questa immagine per divulgare il risultato, ed è **utile come intuizione di partenza**, ma **non è come funziona davvero il calcolo**, e presa alla lettera porta a idee sbagliate (per esempio, farebbe pensare che la radiazione provenga da un punto preciso appena fuori dall'orizzonte, cosa non vera: il calcolo mostra che il flusso di particelle si può ricondurre a proprietà globali dello spaziotempo, non a un evento locale specifico vicino all'orizzonte).

## 3. La spiegazione corretta: cambio di definizione di "particella"

Il vero meccanismo (Hawking, 1975) usa la **teoria quantistica dei campi in spaziotempo curvo** (Modulo 08): si studia un campo quantistico (es. il campo elettromagnetico) non nello spaziotempo piatto della relatività ristretta, ma nello spaziotempo curvo di un buco nero che si sta formando per collasso gravitazionale.

Il punto chiave, sorprendente e sottile: **in meccanica quantistica dei campi, "cosa conta come una particella" dipende dall'osservatore**, più precisamente dal sistema di riferimento (dal moto) dell'osservatore, in modo molto più radicale che in relatività ristretta. Questo è già vero senza buchi neri: è l'**effetto Unruh** — un osservatore accelerato nel vuoto della relatività ristretta *misura* un bagno di particelle termiche che un osservatore inerziale (fermo) non vede affatto. Il vuoto di uno non è il vuoto dell'altro.

Il calcolo di Hawking fa la versione "gravitazionale" di questo stesso fenomeno:
1. Si definisce lo stato di "vuoto" del campo **prima** che la stella collassi (nessun buco nero ancora, spaziotempo quasi piatto lontano).
2. Si fa evolvere questo stato attraverso il collasso gravitazionale, usando le equazioni della meccanica quantistica dei campi nello spaziotempo curvo che cambia nel tempo.
3. Si chiede: cosa "vede" (misura) un osservatore lontano, molto dopo che il buco nero si è formato ed è diventato stazionario?

Il risultato del calcolo (usando le cosiddette **trasformazioni di Bogoliubov**, che collegano la definizione di particella "prima" e "dopo") è che lo stato che era vuoto all'inizio, **appare come un bagno di particelle termiche** all'osservatore lontano dopo la formazione del buco nero. Non è che "qualcosa cada dentro e qualcosa scappi" in un punto preciso: è che il concetto stesso di vuoto/particella si è irrimediabilmente "mescolato" a causa della curvatura dinamica dello spaziotempo durante il collasso, e ciò che resta osservabile a tempi lunghi è indistinguibile da radiazione termica proveniente dall'orizzonte.

## 4. Il risultato: uno spettro esattamente termico

La cosa più sorprendente del calcolo di Hawking è che lo spettro di energia delle particelle emesse è **esattamente** quello di un corpo nero (Modulo 07) a una temperatura precisa, la **temperatura di Hawking**:

```
T_H = ħ c³ / (8 π G M k_B)
```

Nota il rapporto inverso con la massa: **più un buco nero è massiccio, più è FREDDO**. È l'opposto dell'intuizione quotidiana (dove un oggetto più grande spesso è più "energetico").

### Calcoli veri

- **Buco nero di 1 massa solare**: T_H ≈ 6.2 × 10⁻⁸ K (60 nanokelvin). Per confronto, la radiazione cosmica di fondo (Modulo 09) è a ≈ 2.7 K — **quasi 50 milioni di volte più calda**. Un buco nero stellare oggi **assorbe** molta più energia dalla CMB di quanta ne emetta per Hawking: sta ancora "crescendo" nettamente, non evaporando.
- **Sagittarius A\*** (4 milioni di masse solari): T_H ≈ 1.6 × 10⁻¹⁴ K — incommensurabilmente più freddo.
- Un buco nero dovrebbe raggiungere una temperatura pari alla CMB (e quindi iniziare a evaporare nettamente più di quanto assorbe) solo quando la CMB stessa si sarà raffreddata abbastanza per via dell'espansione dell'universo, tra moltissimi miliardi di anni.
- **Buco nero "primordiale"** con massa di un asteroide (≈ 10¹² kg, ipotetico, formatosi nell'universo primordiale, non da collasso stellare): T_H sarebbe dell'ordine di decine di migliaia di kelvin — abbastanza caldo da evaporare rapidamente ed essere potenzialmente rilevabile. La ricerca di buchi neri primordiali in evaporazione (tramite i lampi gamma che dovrebbero produrre nell'istante finale) è un campo di ricerca attivo, finora senza rilevazioni confermate.

## 5. Evaporazione e tempo di vita

Man mano che un buco nero emette radiazione di Hawking, perde massa (per conservazione dell'energia: E = Mc² diminuisce). Poiché T_H ∝ 1/M, **più il buco nero si rimpicciolisce, più si scalda, più emette velocemente** — un processo che accelera (instabilità termica: a differenza di un oggetto ordinario, un buco nero ha **capacità termica negativa**). Il tempo di evaporazione completa scala come:

```
t_evaporazione ∝ M³
```

Per un buco nero di 1 massa solare, il tempo di evaporazione stimato è dell'ordine di **10⁶⁷ anni** — incommensurabilmente più lungo dell'attuale età dell'universo (≈ 1.38 × 10¹⁰ anni). Per un buco nero supermassiccio, ancora molti ordini di grandezza più lungo. Questo è uno dei motivi per cui la radiazione di Hawking, pur essendo teoricamente solidissima, **non è mai stata osservata direttamente**: è troppo debole e i tempi coinvolti troppo lunghi per i buchi neri astrofisici conosciuti.

## 6. Un chiarimento importante sul "dove" della radiazione

Studi più moderni (a partire dagli anni 2000, in particolare il lavoro di Parikh e Wilczek sul "tunneling quantistico") offrono un'immagine alternativa e complementare, più vicina all'intuizione "da coppie vicino all'orizzonte" ma resa rigorosa: modellano l'emissione come un **effetto tunnel quantistico** attraverso l'orizzonte, con un tasso di emissione consistente con lo spettro termico di Hawking. Questo approccio conferma il risultato originale con un metodo diverso, ed è considerato una buona intuizione "localizzata" complementare a quella globale di Hawking — utile da conoscere entrambe.

## 7. Cosa NON dice ancora questo file / dove si rompe

- Non spiega dove va a finire l'informazione sulla materia che è caduta nel buco nero, dato che la radiazione emergente è (in prima approssimazione) puramente termica, cioè "senza informazione" codificata in modo evidente. Questo è esattamente il **paradosso dell'informazione**, argomento del prossimo file.
- Il calcolo di Hawking è "semiclassico": tratta la gravità come classica (curvatura di sfondo fissata) e solo il campo di materia come quantistico. Non è (ancora) un calcolo di gravità quantistica completa — è un'approssimazione, seppur estremamente ben fondata, valida quando la curvatura non è quella estrema della scala di Planck.

## 8. Per andare oltre subito
- Hawking, S. (1975), *Particle Creation by Black Holes*, Comm. Math. Phys. — l'articolo originale.
- Birrell & Davies, *Quantum Fields in Curved Space* — il testo di riferimento completo (avanzato, per quando avremo fatto il Modulo 08).
- Parikh & Wilczek (2000), *Hawking Radiation as Tunneling* (arXiv) — la versione "tunneling", più intuitiva.
- Susskind & Lindesay (vedi bibliografia generale) per un'introduzione a metà strada, molto ben scritta.
