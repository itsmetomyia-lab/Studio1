# Stato di avanzamento — leggimi sempre per primo

> Questo file è la "memoria" del progetto. Ogni sessione (umana o AI) deve aggiornarlo dopo aver lavorato.

## Chi sta studiando

Studente di 15 anni, forte motivazione, obiettivo dichiarato molto alto ("superare i professori di Oxford"). Vedi `METODO.md` per lo stile con cui scrivere i contenuti — **è vincolante, leggerlo prima di scrivere qualunque cosa**.

## Punto di partenza (prima di questo repo)

Lo studente conosceva già, a livello concettuale/divulgativo:
- Orizzonte degli eventi
- Singolarità
- Radiazione di Hawking (idea generale)

Nessun materiale scritto esisteva ancora: questa è la prima messa a sistema di questi argomenti.

## Sessione 1 — 2026-08-19

**Cosa è stato fatto:**
1. Creata la struttura completa del repo (`studio-fisica-universo/` con 11 moduli numerati, dalla matematica di base fino a oltre il Modello Standard). Vedi `00-ROADMAP.md`.
2. Scritto `METODO.md`: livello di rigore, stile, target dello studente. **Vincolante per contenuti futuri.**
3. Scritto `BIBLIOGRAFIA.md` con risorse organizzate per livello (divulgativo → avanzato → paper originali → corsi video).
4. Iniziato `GLOSSARIO.md` (verrà popolato ad ogni nuovo argomento).
5. **Modulo 10 — Buchi Neri: completato un primo giro completo**, partendo da ciò che lo studente già sapeva e approfondendo molto oltre:
   - `01-fondamenti.md` — orizzonte, singolarità, censura cosmica, causalità, coni di luce, cenni ai diagrammi di Penrose.
   - `02-metrica-di-schwarzschild.md` — metrica, raggio di Schwarzschild con calcoli numerici reali (Sole, Terra, Sagittarius A*), coordinata tempo vs coordinata propria, redshift gravitazionale.
   - `03-buchi-neri-rotanti-kerr.md` — metrica di Kerr, ergosfera, frame dragging, processo di Penrose.
   - `04-buchi-neri-carichi.md` — Reissner-Nordström, Kerr-Newman, teorema no-hair.
   - `05-termodinamica.md` — le 4 leggi della termodinamica dei buchi neri, entropia di Bekenstein-Hawking, paradosso apparente della violazione della seconda legge risolto dall'entropia generalizzata.
   - `06-radiazione-di-hawking.md` — approfondimento serio oltre l'idea da "coppie virtuali vicino all'orizzonte" (che viene anche criticata come immagine imprecisa), con la vera origine quantistica-di-campo, temperatura di Hawking, tempo di evaporazione, buchi neri primordiali.
   - `07-paradosso-informazione.md` — cos'è di preciso il paradosso, perché è un problema serio, tentativi di soluzione.
   - `08-frontiere-firewall-er-epr.md` — firewall paradox, ER=EPR, cenni a olografia/AdS-CFT.
   - `09-osservazioni.md` — Event Horizon Telescope (M87*, Sgr A*), onde gravitazionali LIGO/Virgo, come si osservano davvero i buchi neri.
   - `00-indice.md` — indice del modulo con percorso di lettura consigliato.

**Cosa NON è stato ancora fatto (a proposito, non per dimenticanza):**
- Il Modulo 10 è scritto usando relatività ristretta/generale spiegata "quel tanto che basta" dentro ai file stessi (per non lasciare buchi), ma **i Moduli 01-09 e 11 sono ancora scheletri (solo roadmap, senza contenuto)**. Sono il prossimo passo naturale per rendere la comprensione dei buchi neri completa e rigorosa "dal basso" (con tensori veri, equazioni di campo di Einstein derivate, QFT in spaziotempo curvo per Hawking rigoroso).
- Nessun esercizio numerico strutturato ancora (previsto in `10-buchi-neri/ESERCIZI.md`, da creare).

## Prossimi passi consigliati (in ordine di priorità)

1. **Modulo 04 — Relatività Ristretta**: costruire da zero (postulati, trasformazioni di Lorentz, spaziotempo di Minkowski). È il prerequisito diretto per leggere la Relatività Generale con vero rigore.
2. **Modulo 05 — Relatività Generale**: qui si deriva davvero la metrica di Schwarzschild dalle equazioni di Einstein invece di prenderla "già pronta" come fatto nel Modulo 10.
3. Tornare al Modulo 10 e riscrivere/estendere `02-metrica-di-schwarzschild.md` con la derivazione completa, ora che il Modulo 05 fornisce gli strumenti.
4. **Modulo 01 — Matematica per fisici**, in parallelo/prima se servono strumenti specifici (tensori, geometria differenziale) non ancora posseduti.
5. Poi Moduli 06-07-08 (QM, statistica, QFT) per arrivare a capire la radiazione di Hawking nella sua forma tecnica vera (calcolo di Bogoliubov, modi in/out).
6. Modulo 09 (Cosmologia) e Modulo 11 (frontiera/gravità quantistica) come traguardo.

## Come continuare (istruzioni operative per la prossima sessione)

- Apri `00-ROADMAP.md`, guarda quale casella spuntare dopo.
- Rispetta lo stile in `METODO.md`.
- Ogni nuovo file di contenuto: aggiungilo al posto giusto nella struttura di cartelle già creata, aggiorna l'indice del modulo (`00-indice.md` se esiste) e il `GLOSSARIO.md`.
- **Alla fine della sessione, aggiungi una nuova sezione "Sessione N — data" qui sopra**, con lo stesso formato: cosa fatto, cosa manca, prossimi passi.
