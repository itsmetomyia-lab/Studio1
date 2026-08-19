# Esercizi svolti — Buchi Neri

Esercizi numerici veri, con soluzione commentata. Servono a verificare di aver capito i concetti dei file 01-06, non solo di averli letti. Aggiungere nuovi esercizi qui man mano.

---

### Esercizio 1 — Raggio di Schwarzschild di un buco nero stellare

Un buco nero ha massa pari a 8 masse solari (M☉ = 1.989 × 10³⁰ kg). Calcola il suo raggio di Schwarzschild.

**Soluzione:**
```
Rs = 2GM/c²
M = 8 × 1.989×10³⁰ kg = 1.591×10³¹ kg
Rs = 2 × (6.674×10⁻¹¹) × (1.591×10³¹) / (3×10⁸)²
Rs = (2.124×10²¹) / (9×10¹⁶)
Rs ≈ 23.6 km
```
Un buco nero di 8 masse solari ha un orizzonte degli eventi di circa 23.6 km di raggio — più piccolo del diametro di molte città.

---

### Esercizio 2 — Densità media "apparente" di un buco nero

Usando il risultato dell'Esercizio 1, calcola la densità media che avrebbe un buco nero se pensassimo la sua massa "spalmata" uniformemente dentro la sfera di raggio Rs (attenzione: fisicamente la massa è nella singolarità, non distribuita nel volume — è un calcolo concettuale per capire come cambia la densità con la massa).

**Soluzione:**
```
V = (4/3)πRs³ = (4/3)π(23600 m)³ ≈ 5.5×10¹³ m³
ρ = M/V = 1.591×10³¹ / 5.5×10¹³ ≈ 2.9×10¹⁷ kg/m³
```
Per confronto, la densità di un nucleo atomico è ≈ 2.3×10¹⁷ kg/m³ — sorprendentemente simile! Ma prova a rifare il conto con M87* (M ≈ 6.5×10⁹ M☉, Rs ≈ 1.9×10¹³ m dal file 02): troverai una densità **enormemente più bassa** dell'acqua. Questo mostra un fatto controintuitivo: **i buchi neri più massicci hanno densità media apparente più bassa**, perché Rs ∝ M mentre il volume ∝ Rs³ ∝ M³, quindi ρ ∝ M/M³ = 1/M². Rifallo tu stesso come esercizio aggiuntivo e verifica il risultato.

---

### Esercizio 3 — Dilatazione temporale gravitazionale vicino a un buco nero

Un'astronave è ferma a una distanza r = 1.5 Rs da un buco nero di Schwarzschild. Di quanto scorre più lentamente il tempo a bordo, rispetto a un osservatore molto lontano?

**Soluzione:**
```
dτ/dt = √(1 - Rs/r) = √(1 - Rs/(1.5 Rs)) = √(1 - 0.667) = √0.333 ≈ 0.577
```
Per ogni secondo che passa per l'osservatore lontano, a bordo dell'astronave passano solo 0.577 secondi. Se l'astronave resta lì per un'ora del proprio tempo, sulla Terra saranno passate 1/0.577 ≈ 1.73 ore. Nota: a r = Rs esatto, dτ/dt = 0 — il tempo si "ferma" completamente rispetto all'osservatore lontano (coerente col file 02, sezione 5).

---

### Esercizio 4 — Temperatura di Hawking di un buco nero appena rilevato

Calcola la temperatura di Hawking di un buco nero di 62 masse solari (circa la massa del buco nero finale prodotto dalla fusione GW150914, vedi file 09).

**Soluzione:**
```
T_H = ħc³ / (8πGMk_B)
ħ = 1.0546×10⁻³⁴ J·s,  c = 3×10⁸ m/s,  G = 6.674×10⁻¹¹,  k_B = 1.381×10⁻²³ J/K
M = 62 × 1.989×10³⁰ kg ≈ 1.233×10³² kg

T_H = (1.0546×10⁻³⁴ × (3×10⁸)³) / (8π × 6.674×10⁻¹¹ × 1.233×10³² × 1.381×10⁻²³)
```
Numeratore: 1.0546×10⁻³⁴ × 2.7×10²⁵ ≈ 2.847×10⁻⁹
Denominatore: 8π × 6.674×10⁻¹¹ × 1.233×10³² × 1.381×10⁻²³ ≈ 8π × 1.137×10⁰ ≈ 28.57
```
T_H ≈ 2.847×10⁻⁹ / 28.57 ≈ 1.0×10⁻¹⁰ K
```
Circa un decimo di miliardesimo di kelvin: assolutamente non misurabile con la tecnologia attuale, e comunque molto più freddo della radiazione cosmica di fondo (2.7 K) — questo buco nero sta assorbendo energia dalla CMB molto più velocemente di quanta ne emetta, coerentemente col file 06.

---

### Esercizio 5 — Entropia di Bekenstein-Hawking del Sole (se collassasse)

Se il Sole collassasse in un buco nero (non può accadere realmente: non ha massa sufficiente, ma è un utile esercizio di calcolo), quale sarebbe la sua entropia, in unità di k_B?

**Soluzione:**
```
S/k_B = 4π G M² / (ħ c)
M = 1.989×10³⁰ kg
S/k_B = 4π × 6.674×10⁻¹¹ × (1.989×10³⁰)² / (1.0546×10⁻³⁴ × 3×10⁸)
```
Numeratore: 4π × 6.674×10⁻¹¹ × 3.956×10⁶⁰ ≈ 4π × 2.640×10⁵⁰ ≈ 3.317×10⁵¹
Denominatore: 1.0546×10⁻³⁴ × 3×10⁸ = 3.164×10⁻²⁶
```
S/k_B ≈ 3.317×10⁵¹ / 3.164×10⁻²⁶ ≈ 1.05×10⁷⁷
```
Un'entropia di circa 10⁷⁷ k_B — un numero incomprensibilmente grande, che conferma quanto detto nel file 05: i buchi neri sono gli oggetti a più alta entropia per unità di massa nell'universo conosciuto.

---

## Esercizi proposti (da svolgere, soluzione da aggiungere)

1. Calcola il raggio di Schwarzschild e la temperatura di Hawking di un ipotetico buco nero con la massa della Luna.
2. Un buco nero di Kerr ha a\* = 0.9. Calcola r+ e r− in unità di GM/c² (suggerimento: usa la formula del file 03 con a = 0.9 GM/c²).
3. Usando il tempo di evaporazione t ∝ M³ e sapendo che un buco nero di 1 massa solare impiega circa 10⁶⁷ anni a evaporare, stima il tempo di evaporazione di un buco nero di massa pari a quella della Terra (M ≈ 3×10⁻⁶ M☉). Confronta con l'età dell'universo.
4. Verifica che l'area dell'orizzonte del buco nero finale di GW150914 (62 M☉) è effettivamente maggiore della somma delle aree dei due buchi neri iniziali (36 M☉ e 29 M☉) — questa è una verifica diretta del teorema dell'area di Hawking (file 05).
