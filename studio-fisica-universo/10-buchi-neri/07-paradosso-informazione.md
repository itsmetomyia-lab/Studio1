# 07 — Il paradosso dell'informazione

## 1. Perché ci interessa

È probabilmente **il** problema aperto più famoso all'intersezione tra relatività generale e meccanica quantistica. Non è un dettaglio tecnico: mette in discussione se una delle due teorie fondamentali della fisica moderna debba essere modificata.

## 2. Il principio che viene messo in crisi: unitarietà

In meccanica quantistica esiste un principio fondamentale, l'**unitarietà**: l'evoluzione nel tempo di uno stato quantistico è sempre reversibile in linea di principio. Conoscendo perfettamente lo stato finale di un sistema quantistico isolato, si può (in linea di principio, con potenza di calcolo sufficiente) ricostruire esattamente lo stato iniziale. **L'informazione non si crea né si distrugge mai**, si mescola e si nasconde, ma resta sempre recuperabile in linea di principio. Questo è tanto fondamentale in meccanica quantistica quanto la conservazione dell'energia lo è in meccanica classica: violarlo comprometterebbe l'intero impianto della teoria.

## 3. Il conflitto, passo per passo

1. Prendi un sistema fisico con un contenuto informativo definito — per esempio, un libro (in linea di principio, anche solo un fascio di fotoni preparati in uno stato quantistico puro molto specifico).
2. Fallo cadere in un buco nero.
3. Per il **teorema no-hair** (file 04), da fuori il buco nero, dopo, appare identico a un buco nero della stessa massa/carica/momento angolare formato in un modo completamente diverso: **tutta l'informazione dettagliata sembra sparita alla vista**, ma potremmo comunque credere che sia "nascosta dentro", oltre l'orizzonte, in attesa — non necessariamente distrutta, solo inaccessibile per ora.
4. Ma per la **radiazione di Hawking** (file 06), il buco nero **evapora completamente**, in un tempo finito (per quanto lunghissimo). Lo spettro della radiazione emessa, nel calcolo semiclassico originale di Hawking, è **esattamente termico** — cioè dipende solo dalla temperatura (quindi in ultima analisi solo da M, J, Q), non dai dettagli di cosa sia caduto dentro.
5. Quando il buco nero è completamente evaporato, non resta nulla: né il buco nero, né (apparentemente) alcuna traccia recuperabile dell'informazione originale del libro. **L'informazione sembra essere stata distrutta per sempre.**

Questo contraddice direttamente l'unitarietà quantistica. Hawking stesso, nel 1976, arrivò esattamente a questa conclusione e la considerò per decenni una vera rottura della meccanica quantistica in presenza di gravità.

## 4. Perché non si può liquidare facilmente il problema

Ci sono varie "vie di fuga" ovvie a cui si pensa subito, e vale la pena vedere perché nessuna, presa da sola, funziona senza problemi:

- **"L'informazione resta dentro, in un residuo che non evapora del tutto."** Problema: servirebbe un numero enorme di stati quantistici distinti tutti compressi in un residuo di massa (quasi) nulla o di dimensione (quasi) nulla — situazione considerata patologica da molti fisici (violerebbe altri principi generali, come limiti sul numero di stati per data energia).
- **"L'informazione viene distrutta davvero, la meccanica quantistica va modificata in presenza di gravità."** Presa sul serio da Hawking per molti anni; il problema è che modificare l'unitarietà tende a introdurre altre patologie nella teoria quantistica (es. violazione della conservazione dell'energia in modo incontrollato, secondo un argomento di Banks, Peskin e Susskind del 1984).
- **"L'informazione esce gradualmente, codificata in sottilissime correlazioni nella radiazione di Hawking, che quindi non è perfettamente termica come sembra nel calcolo semiclassico."** Questa è oggi la posizione dominante (vedi sotto), ma richiede capire *come* queste correlazioni emergano — un problema tecnico enorme, perché il calcolo semiclassico di Hawking, preso alla lettera, dà davvero uno spettro esattamente termico, senza correlazioni.

## 5. La svolta: la curva di Page e l'olografia

Un argomento chiave, dovuto a **Don Page (1993)**, mostra *quantitativamente* cosa dovrebbe succedere se l'informazione si conserva davvero: l'**entropia di entanglement** tra il buco nero e la radiazione già emessa dovrebbe prima crescere (mentre il buco nero emette radiazione apparentemente casuale) e poi, a un certo "tempo di Page" (circa a metà dell'evaporazione), **iniziare a diminuire**, tornando a zero quando il buco nero è completamente evaporato (segno che a quel punto la radiazione, nel suo complesso, è tornata a essere uno stato puro, con tutta l'informazione recuperabile). Questo andamento a "collina" si chiama **curva di Page**, ed è oggi considerato il comportamento corretto che qualunque teoria consistente deve riprodurre.

Il calcolo semiclassico originale di Hawking, invece, predice che l'entropia **cresca sempre**, senza mai scendere — in netto contrasto con la curva di Page. Questa discrepanza è la formulazione tecnica precisa del paradosso.

**Sviluppo recente importante (2019-2020):** usando tecniche di **teoria quantistica dei campi + gravità + "wormhole repliche" (replica wormholes)** e il concetto di **"isole entropiche" (entanglement islands)**, diversi gruppi di ricerca (Penington; Almheiri, Engelhardt, Marolf, Maxfield; Almheiri, Mahajan, Maldacena, Zhao) sono riusciti, in modelli semplificati (buchi neri in 2 dimensioni, e sotto certe assunzioni), a **riprodurre effettivamente la curva di Page** partendo da un calcolo di gravità, senza inserirla a mano. Questo è considerato uno dei progressi più importanti degli ultimi anni sul paradosso — un forte segnale (anche se non ancora una soluzione completa, generale, dimostrata per buchi neri realistici a 4 dimensioni) che **l'informazione si conserva davvero**, ed emerge dalla struttura più fine della gravità quantistica, non da una violazione della meccanica quantistica.

## 6. Stato attuale (per quanto ne sappiamo, 2026)

Il consenso della maggioranza dei fisici teorici oggi è: **l'informazione probabilmente si conserva** (l'unitarietà quantistica vince), e la radiazione di Hawking, calcolata correttamente includendo effetti di gravità quantistica non catturati dal calcolo semiclassico originale, deve contenere sottilissime correlazioni che la rendono, nel suo complesso, non perfettamente termica. **Non è però ancora del tutto risolto** come questo avvenga in generale per un buco nero astrofisico realistico in 4 dimensioni: i risultati più solidi restano in modelli semplificati. È un'area di ricerca teorica estremamente attiva.

## 7. Cosa NON dice ancora questo file

- Non spiega il "firewall paradox", una versione ancora più tagliente del problema formulata nel 2012 — prossimo file.
- Non spiega cosa siano tecnicamente le "isole entropiche" o i "replica wormholes" in dettaglio — richiedono il path integral gravitazionale (Modulo 08/11), li riprenderemo quando pronti.

## 8. Per andare oltre subito
- Hawking, S. (1976), *Breakdown of Predictability in Gravitational Collapse* — l'articolo che formulò il paradosso.
- Page, D. (1993), *Information in Black Hole Radiation* (arXiv) — la curva di Page.
- Un'ottima rassegna divulgativa-ma-seria: Almheiri, Hartman, Maldacena, Shaghoulian, Tajdini, *The entropy of Hawking radiation*, Rev. Mod. Phys. (2021) — livello avanzato ma con introduzione accessibile.
