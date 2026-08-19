# 01 — Fondamenti: orizzonte, singolarità, causalità

## 1. Perché ci interessa

Prima di aggiungere formule, mettiamo in ordine e rendiamo precisi i concetti che già conosci. "Orizzonte degli eventi" e "singolarità" sono parole che si usano spesso in modo vago; qui li definiamo con precisione, perché da questa precisione dipende tutto il resto (termodinamica, radiazione di Hawking, paradosso dell'informazione).

## 2. Cos'è davvero un buco nero

Un buco nero **non è un oggetto fatto di materia**, nel senso in cui lo è una stella o un pianeta. È una **regione di spaziotempo** dalla quale nulla — nemmeno la luce — può sfuggire. La materia che lo ha formato (es. il nucleo di una stella collassata) è finita nella singolarità; quello che resta "fuori", osservabile, è pura geometria: curvatura dello spaziotempo.

Questo è il primo salto concettuale importante: **la gravità in relatività generale non è una forza, è la geometria stessa dello spaziotempo**. I corpi non "vengono attratti" da una forza: si muovono lungo le traiettorie più dritte possibili (le **geodetiche**) in uno spaziotempo che la massa/energia ha curvato. Un buco nero è la curvatura estrema: talmente forte che le geodetiche vicino ad esso puntano tutte "verso l'interno", inclusa quella della luce.

## 3. L'orizzonte degli eventi, con precisione

**Definizione operativa:** l'orizzonte degli eventi è la superficie di confine oltre la quale nemmeno un raggio di luce sparato radialmente verso l'esterno riesce ad allontanarsi.

Punti chiave che di solito NON vengono spiegati bene nella divulgazione:

- **L'orizzonte non è una superficie fisica.** Non c'è nulla lì: nessuna "membrana", nessun materiale. Un astronauta che lo attraversasse (per un buco nero abbastanza grande) non sentirebbe nulla di speciale nel momento dell'attraversamento — localmente, lo spaziotempo lì è liscio (questo è una conseguenza diretta del principio di equivalenza, che vedremo nel Modulo 05).
- **L'orizzonte è definito globalmente, non localmente.** Per sapere con certezza se un dato punto è "dentro" l'orizzonte, devi conoscere l'intera storia futura dello spaziotempo (tecnicamente è definito come il confine del "passato causale dell'infinito futuro nullo", 𝓙⁻(𝓘⁺)). In pratica: potresti trovarti già oltre l'orizzonte senza nessun modo, localmente, di accorgertene subito.
- **Da dentro, tutti i cammini nello spazio portano verso la singolarità.** Questo è il punto più sottile e più importante: dentro l'orizzonte, la direzione "verso il centro" smette di essere una direzione spaziale che puoi scegliere di non percorrere, e diventa **una direzione temporale**. Cadere verso la singolarità, dentro l'orizzonte, è tanto inevitabile quanto per te ora è inevitabile "andare avanti nel tempo verso domani". Non è che "non hai la spinta per allontanarti": è che tutto il tuo futuro, in ogni direzione tu vada, punta verso la singolarità. Torneremo su questo con i coni di luce (sezione 5).

## 4. La singolarità, con precisione

La singolarità di uno buco nero di Schwarzschild (non rotante) è un **punto nello spazio in un istante nel tempo** (più precisamente: è un punto in ogni istante futuro, per chi è caduto dentro) dove:

- la curvatura dello spaziotempo diverge (tende all'infinito);
- le equazioni della relatività generale smettono di dare previsioni sensate;
- le grandezze fisiche come densità e forze di marea diventano formalmente infinite.

**Importante:** "infinito" qui è il segnale che **la teoria sta fallendo**, non che la natura produca davvero infiniti. Il consenso della fisica teorica è che la relatività generale classica non è la parola ultima vicino alla singolarità: lì, a scale piccolissime (scala di Planck, ~10⁻³⁵ m), servirebbe una teoria di gravità quantistica che ancora non abbiamo completa (Modulo 11). La singolarità è quindi, con tutta probabilità, un artefatto dei limiti della teoria, non un oggetto fisico reale nel senso pieno del termine.

Nota terminologica: per un buco nero **rotante** (Kerr, vedi file 03) la singolarità non è un punto ma un **anello** — un dettaglio sorprendente che ha conseguenze enormi (in linea di principio esisterebbero traiettorie che lo evitano, anche se restano su territorio speculativo per via dell'instabilità di quelle soluzioni).

## 5. Coni di luce e causalità (il modo giusto per capire l'orizzonte)

In relatività (ristretta e generale) ogni evento nello spaziotempo ha un **cono di luce**: l'insieme di tutte le direzioni in cui la luce può propagarsi da quel punto. Nessun segnale, nessuna informazione, nessun oggetto può viaggiare più veloce della luce, quindi il futuro di un evento è sempre contenuto dentro il suo cono di luce futuro.

- **Lontano da un buco nero**: i coni di luce sono "dritti", come nello spazio piatto: hai libertà di muoverti in tutte le direzioni spaziali, e il tuo cono futuro punta "in alto" nel tempo in modo simmetrico.
- **Avvicinandosi all'orizzonte**: la curvatura dello spaziotempo "inclina" progressivamente i coni di luce verso il buco nero.
- **Esattamente sull'orizzonte**: il cono di luce si inclina al punto che uno dei suoi bordi punta esattamente lungo l'orizzonte stesso. Un fotone sparato radialmente verso l'esterno proprio sull'orizzonte resta "fermo" lì per sempre (in un senso preciso, che formalizzeremo con la metrica di Schwarzschild).
- **Dentro l'orizzonte**: il cono di luce è inclinato così tanto che *anche il suo bordo più "esterno"* punta verso la singolarità. Ecco perché la caduta è inevitabile: non esiste più nessuna direzione, dentro il cono di luce futuro, che porti all'esterno.

Questa è la spiegazione geometricamente corretta del perché "nemmeno la luce può uscire": non è che la luce venga "rallentata e poi tirata indietro" come una palla lanciata in aria — è che la nozione stessa di "verso l'esterno" cessa di esistere all'interno del cono di luce futuro, una volta dentro l'orizzonte.

## 6. Censura cosmica (cosmic censorship)

Una domanda naturale: possono esistere singolarità **senza** un orizzonte che le nasconda ("singolarità nude")? Se esistessero, la fisica vicino a loro (dove le leggi note falliscono) potrebbe influenzare causalmente il resto dell'universo in modo imprevedibile.

Roger Penrose (Nobel 2020, proprio per i suoi lavori sui buchi neri) ha proposto la **congettura di censura cosmica**: in condizioni fisicamente ragionevoli di collasso gravitazionale, ogni singolarità che si forma è sempre "vestita" da un orizzonte degli eventi, che la nasconde per sempre alla vista di osservatori esterni. È una congettura, non un teorema dimostrato in generale: è tra le domande aperte più importanti della relatività generale classica (ne parleremo ancora nel Modulo 05 e nel Modulo 11).

## 7. Cosa NON dice ancora questo file

- Non abbiamo ancora una formula per il raggio dell'orizzonte: arriva nel prossimo file con la metrica di Schwarzschild.
- Non abbiamo derivato nulla dalle equazioni di Einstein: qui abbiamo solo usato concetti (curvatura, geodetiche, coni di luce) definiti con precisione ma senza il macchinario matematico completo — quello è nel Modulo 05.
- Non abbiamo ancora parlato di rotazione o carica elettrica: arriva nei file 03 e 04.

## 8. Per andare oltre subito
- Kip Thorne, *Il buco nero e il tempo curvo*, capitoli iniziali — spiegazione intuitiva eccellente dei coni di luce.
- Hartle, *Gravity*, cap. 1-2 e cap. 9 — introduzione "physics first" a orizzonte e singolarità con equazioni.
