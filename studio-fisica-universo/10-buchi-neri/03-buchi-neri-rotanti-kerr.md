# 03 — Buchi neri rotanti: la metrica di Kerr

## 1. Perché ci interessa

Nella realtà, **quasi tutti** i buchi neri ruotano — ereditano il momento angolare della stella o della nube di gas da cui si sono formati, e spesso ruotano molto velocemente. La soluzione di Schwarzschild (file 02) è un'idealizzazione utile ma incompleta. La soluzione esatta per un buco nero rotante fu trovata da Roy Kerr solo nel **1963**, quasi 50 anni dopo Schwarzschild — è matematicamente molto più complessa perché la simmetria sferica si perde (resta solo la simmetria assiale, attorno all'asse di rotazione).

## 2. I parametri di un buco nero di Kerr

Un buco nero di Kerr è descritto da **due soli numeri**:
- la massa M (come Schwarzschild)
- il momento angolare **J** (o, equivalentemente, il parametro di spin **a = J/(Mc)**, con dimensioni di lunghezza)

Si definisce lo spin adimensionale **a\* = a/Rs_metà = cJ/(GM²)**, che va da 0 (non rotante, = Schwarzschild) a 1 (massima rotazione possibile, "estremale"). I buchi neri osservati nell'universo hanno spesso a\* molto vicino a 1 (alcuni buchi neri supermassicci osservati hanno a\* > 0.9).

## 3. Due orizzonti, non uno

Risolvendo le equazioni per la metrica di Kerr, si trovano **due** raggi speciali (in coordinate di Boyer-Lindquist, l'analogo delle coordinate sferiche per Kerr):

```
r± = GM/c² ± √[(GM/c²)² − a²]
```

- **r+** è l'orizzonte degli eventi vero e proprio (la superficie di non ritorno).
- **r−** è un "orizzonte di Cauchy" interno, oltre il quale la relatività generale classica perde persino la capacità di prevedere il futuro in modo univoco a partire dai dati iniziali (è una regione dove la teoria classica smette di essere predittiva in senso proprio — un altro segnale che qui serve nuova fisica).

Se a > GM/c² (rotazione "troppo veloce" per la massa data), la formula sotto radice diventa negativa: non esiste alcun orizzonte reale, e si avrebbe una **singolarità nuda**, violando la censura cosmica (file 01, sezione 6). È un forte indizio (non ancora una dimostrazione generale) che la natura "non permetta" mai di superare questo limite: qualunque tentativo di far ruotare un buco nero oltre a = GM/c² finora studiato nei modelli fisici viene automaticamente impedito da altri effetti.

## 4. L'ergosfera: la regione dove nessuno può stare fermo

Questo è il concetto più sorprendente e più nuovo rispetto a Schwarzschild. Attorno a un buco nero rotante esiste una regione, **esterna** all'orizzonte degli eventi, chiamata **ergosfera**, delimitata dalla "superficie di ergo" (ergosurface):

```
r_ergo(θ) = GM/c² + √[(GM/c²)² − a²cos²θ]
```

(θ è l'angolo rispetto all'asse di rotazione; l'ergosfera tocca l'orizzonte ai poli e si allarga massimamente all'equatore).

**Frame dragging (trascinamento dei sistemi di riferimento):** un buco nero rotante "trascina" lo spaziotempo attorno a sé nella direzione della propria rotazione, un po' come un cucchiaio che gira nel miele trascina il miele vicino con sé. Dentro l'ergosfera, questo trascinamento è così forte che **è impossibile restare fermi rispetto alle stelle lontane**, qualunque sia la potenza del razzo che si usa: si è costretti a ruotare nella stessa direzione del buco nero. Questo non è ancora "non poter uscire" (fuori dall'orizzonte si può ancora, in linea di principio, allontanarsi radialmente) — è che la nozione stessa di "stare fermi" cessa di esistere lì dentro.

## 5. Il processo di Penrose: estrarre energia da un buco nero

Poiché nell'ergosfera è possibile, sorprendentemente, che una particella abbia **energia negativa** (rispetto a un osservatore all'infinito — un effetto puramente dovuto al trascinamento), Roger Penrose (1969) ha mostrato che si può sfruttare questo per estrarre energia:

1. Si lascia cadere un oggetto nell'ergosfera.
2. Dentro l'ergosfera, l'oggetto si divide in due frammenti.
3. Uno dei due frammenti viene mandato su una traiettoria a energia negativa che cade oltre l'orizzonte.
4. L'altro frammento **esce dall'ergosfera con più energia di quella con cui era entrato l'oggetto originale**.

L'energia in più viene sottratta all'energia rotazionale del buco nero, che di conseguenza rallenta leggermente. Questo meccanismo (e la sua variante elettromagnetica più realistica, il **processo Blandford-Znajek**, che usa campi magnetici invece di particelle) è oggi considerato il motore più plausibile dei **getti relativistici** osservati uscire dai buchi neri supermassicci al centro delle galassie attive (i quasar).

## 6. La singolarità di Kerr è un anello, non un punto

Un altro fatto sorprendente: risolvendo con attenzione la geometria di Kerr, la singolarità non è puntiforme ma ha la forma di un **anello** di raggio a, sul piano equatoriale. Questo apre (solo matematicamente, dentro la soluzione idealizzata ed eterna di Kerr) scenari esotici come traiettorie che passerebbero "attraverso l'anello" verso regioni di spaziotempo con curvatura temporale chiusa (violazioni di causalità) o verso un'altra regione asintoticamente piatta. **Attenzione**: questi scenari sono conseguenze matematiche della soluzione di Kerr eterna e idealizzata; non si crede rappresentino ciò che accade realmente in un buco nero formatosi da collasso gravitazionale reale, perché la parte interna della soluzione di Kerr è instabile (piccole perturbazioni la cambiano radicalmente) — è un tema di ricerca tuttora aperto.

## 7. Cosa NON dice questo file

- Non abbiamo trattato buchi neri carichi elettricamente (prossimo file: Reissner-Nordström e Kerr-Newman).
- Non abbiamo dimostrato che a ≤ GM/c² sia sempre vero in natura: è un'osservazione empirica/teorica forte, non un teorema assoluto.
- La stabilità della regione interna di Kerr è un problema di ricerca attivo (collegato alla congettura di censura cosmica *forte*, diversa da quella *debole* citata nel file 01).

## 8. Per andare oltre subito
- Kip Thorne, *Il buco nero e il tempo curvo*, i capitoli sul frame dragging e Gravity Probe B (che ha misurato il trascinamento anche attorno alla Terra, effetto Lense-Thirring, molto più debole).
- Visser, *The Kerr spacetime: A brief introduction* (arXiv, disponibile online) — ottimo riepilogo tecnico ma accessibile.
