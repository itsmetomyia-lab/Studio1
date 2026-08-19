# 02 — La metrica di Schwarzschild

## 1. Perché ci interessa

È la prima soluzione esatta trovata (Karl Schwarzschild, 1916, poche settimane dopo la pubblicazione della Relatività Generale di Einstein — trovata mentre era al fronte nella Prima Guerra Mondiale) delle equazioni di campo di Einstein. Descrive lo spaziotempo attorno a **qualunque** massa a simmetria sferica, non rotante e non carica: sia essa il Sole, la Terra, o un buco nero. È il punto di partenza obbligato per capire i buchi neri con formule vere.

## 2. Cosa vuol dire "metrica"

Una **metrica** è la regola che dice come calcolare la "distanza" (in realtà: l'**intervallo spaziotemporale**) tra due eventi vicini. Nello spazio piatto della geometria che conosci (Pitagora), la distanza tra due punti vicini è:

```
ds² = dx² + dy² + dz²
```

Nello spaziotempo piatto della relatività ristretta (Modulo 04), l'intervallo diventa (con c = velocità della luce):

```
ds² = -c²dt² + dx² + dy² + dz²
```

Il segno meno davanti al tempo è cruciale: è ciò che rende il tempo "diverso" dallo spazio e da origine ai coni di luce.

In relatività generale, la presenza di massa/energia **curva** questa regola: i coefficienti davanti a dt², dr² etc. non sono più semplicemente 1 e -1, ma dipendono dal punto nello spaziotempo. La metrica di Schwarzschild è esattamente questa regola, calcolata per lo spaziotempo attorno a una massa sferica M:

```
ds² = -(1 - Rs/r) c²dt² + dr²/(1 - Rs/r) + r²(dθ² + sin²θ dφ²)
```

dove (r, θ, φ) sono coordinate sferiche centrate sulla massa, t è il tempo misurato da un osservatore molto lontano ("all'infinito"), e **Rs** è il **raggio di Schwarzschild**:

```
Rs = 2GM / c²
```

con G costante di gravitazione universale, M massa dell'oggetto, c velocità della luce.

## 3. Il raggio di Schwarzschild: cosa significa fisicamente

Rs è il raggio a cui, *se tutta la massa M fosse compressa dentro quel raggio*, la velocità di fuga eguaglierebbe c: quella superficie diventerebbe un orizzonte degli eventi. Notare bene: **Rs si può calcolare per qualunque massa**, non solo per i buchi neri — è solo che per il Sole o la Terra, Rs è molto più piccolo del raggio reale dell'oggetto, quindi la formula di Schwarzschild vale solo *fuori* dalla superficie reale (dove effettivamente c'è il vuoto), e Rs resta un numero puramente teorico dentro alla stella.

Un buco nero è ciò che si ottiene quando *tutta* la massa finisce compressa dentro il proprio raggio di Schwarzschild.

### Calcoli veri, con numeri veri

```
Rs = 2GM/c²,   con G = 6.674 × 10⁻¹¹ m³ kg⁻¹ s⁻², c = 3 × 10⁸ m/s
```

- **Sole** (M = 1.989 × 10³⁰ kg): Rs ≈ 2.95 km. Il Sole vero ha raggio ≈ 696.000 km, quindi è enormemente più grande del suo Rs — non è un buco nero, ovviamente, e non lo diventerà mai da solo (non ha abbastanza massa per collassare così).
- **Terra** (M = 5.97 × 10²⁴ kg): Rs ≈ 8.9 mm. Se qualcuno comprimesse tutta la Terra dentro una sfera di meno di 9 millimetri di raggio, diventerebbe un buco nero.
- **Un buco nero stellare tipico** (M = 10 masse solari): Rs ≈ 29.5 km.
- **Sagittarius A\*** (il buco nero supermassiccio al centro della Via Lattea, M ≈ 4.15 × 10⁶ masse solari): Rs ≈ 1.22 × 10⁷ km ≈ 12,3 milioni di km (per confronto: il raggio dell'orbita di Mercurio attorno al Sole è ≈ 58 milioni di km — quindi l'orizzonte di Sgr A* ci starebbe comodamente dentro l'orbita di Mercurio).
- **M87\*** (buco nero fotografato dall'Event Horizon Telescope nel 2019, M ≈ 6.5 × 10⁹ masse solari): Rs ≈ 1.9 × 10¹⁰ km ≈ 128 unità astronomiche, più grande dell'intero sistema solare fino all'orbita di Plutone.

## 4. Cosa succede alla metrica per r → Rs (l'orizzonte)

Guarda di nuovo il termine `dr² / (1 - Rs/r)`: quando r si avvicina a Rs, il denominatore (1 - Rs/r) tende a zero, quindi quel termine **diverge**. Contemporaneamente, il termine del tempo `(1 - Rs/r)` tende a zero.

Questo sembra un disastro (una singolarità nella metrica!), ma è **falso allarme**: è una **singolarità di coordinate**, non fisica. Le coordinate (t, r) di Schwarzschild semplicemente "si rompono" all'orizzonte, un po' come le coordinate di longitudine si comportano male ai poli terrestri pur essendo la Terra perfettamente liscia lì. Cambiando sistema di coordinate (es. coordinate di Eddington-Finkelstein o di Kruskal-Szekeres — le vedremo nel Modulo 05), si dimostra che lo spaziotempo all'orizzonte è perfettamente regolare: nessuna curvatura infinita, nessun evento speciale per chi ci cade attraverso.

La **vera** singolarità fisica è solo a r = 0, dove la curvatura (misurata da uno scalare che non dipende dalle coordinate, come lo scalare di Kretschmann) diverge davvero.

## 5. Il tempo si comporta in modo sorprendente vicino a un buco nero

Consideriamo un osservatore fermo a distanza r dal buco nero (per r > Rs) e un osservatore molto lontano ("all'infinito", r → ∞). Il tempo proprio (quello misurato realmente da un orologio) dell'osservatore vicino, dτ, è collegato al tempo coordinato t (che coincide col tempo dell'osservatore lontano) da:

```
dτ = √(1 - Rs/r) dt
```

Questo è il **redshift gravitazionale / dilatazione temporale gravitazionale**: più sei vicino al buco nero (r piccolo, vicino a Rs), più il tuo tempo scorre lentamente **rispetto a chi osserva da lontano**.

- Un osservatore che cade verso l'orizzonte, visto da lontano, sembra rallentare sempre di più, avvicinandosi all'orizzonte **asintoticamente senza mai, apparentemente, attraversarlo del tutto** (per l'osservatore lontano il tempo per arrivarci è infinito).
- La luce che l'osservatore in caduta emette viene sempre più "stirata" verso lunghezze d'onda maggiori (redshift), fino a diventare invisibile.
- **Ma per l'osservatore che sta effettivamente cadendo**, il suo tempo proprio τ scorre normalmente, e attraversa l'orizzonte in un tempo finito, senza accorgersene (per un buco nero abbastanza massiccio — vedi sotto sulle forze di marea). Le due descrizioni non si contraddicono: sono due prospettive diverse sullo stesso spaziotempo, ed è uno degli esempi più belli di come la relatività generale unisca punti di vista apparentemente incompatibili.

## 6. Forze di marea: perché "grande" è più sicuro di "piccolo"

Le forze di marea (differenza di attrazione gravitazionale tra la testa e i piedi di un astronauta che cade) sono proporzionali a M/r³, non semplicemente a M/r² come la gravità "totale". Vicino all'orizzonte, r ≈ Rs ∝ M, quindi le forze di marea sull'orizzonte scalano come M/M³ = 1/M².

**Conseguenza controintuitiva:** più un buco nero è massiccio, **più deboli** sono le forze di marea sul suo orizzonte. Per un buco nero stellare (poche masse solari), le forze di marea all'orizzonte sarebbero letali molto prima di arrivarci ("spaghettificazione"). Per un buco nero supermassiccio come Sgr A* o M87*, le forze di marea sull'orizzonte sono così deboli che un astronauta potrebbe attraversarlo senza accorgersene affatto nell'immediato.

## 7. Cosa NON dice questo file / dove si rompe

- Non abbiamo derivato la metrica dalle equazioni di Einstein (arriva nel Modulo 05): qui l'abbiamo presa come dato e ne abbiamo esplorato le conseguenze.
- Questa metrica descrive solo buchi neri **statici, non rotanti, non carichi** — quasi nessun buco nero reale nell'universo è esattamente così (i buchi neri reali ruotano quasi sempre). Serve Kerr (prossimo file).
- Non spiega ancora nulla di quantistico: qui il buco nero è un oggetto puramente classico, "eterno" e immutabile. La radiazione di Hawking (file 06) cambierà questo quadro.

## 8. Per andare oltre subito
- Hartle, *Gravity*, capitoli 9-12 — tratta Schwarzschild con l'approccio "physics first" più adatto a questo stadio.
- Taylor & Wheeler, *Exploring Black Holes* — libro interamente dedicato a esplorare la metrica di Schwarzschild con esercizi guidati, pensato per essere accessibile anche prima di un corso completo di RG.
