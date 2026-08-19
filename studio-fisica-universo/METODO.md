# Metodo di studio — leggimi prima di scrivere qualsiasi contenuto

Questo file fissa il "contratto" pedagogico concordato con lo studente. Ogni AI che aggiunge materiale a questo repo deve rispettarlo.

## Chi studia

- Ha 15 anni.
- Conosce già, a livello concettuale, l'orizzonte degli eventi, la singolarità e la radiazione di Hawking dei buchi neri.
- Obiettivo dichiarato: **"arrivare a superare i professori di Oxford"** — cioè non fermarsi alla divulgazione, ma costruire una comprensione reale, tecnica, che regga nel tempo.
- Vuole **tutto il percorso**, dalla relatività alla cosmologia alla meccanica quantistica e oltre.

## Regola d'oro

> **Semplice ma vero.** Mai vero-ma-incomprensibile, mai semplice-ma-falso.

In pratica:

- Ogni spiegazione parte da un'intuizione fisica o un'analogia onesta (che viene dichiarata come tale, con i suoi limiti).
- Subito dopo, si introduce la matematica reale che descrive il fenomeno — niente "magia nera". Se una formula ha una derivazione alla portata, la si fa vedere almeno nei passaggi chiave, non solo il risultato finale.
- Non si semplifica **falsando** un concetto per renderlo più digeribile (es: non si dice "la gravità è una forza" se stiamo parlando di relatività generale, si dice che è curvatura dello spaziotempo, e si spiega perché "sembra" una forza).
- Se un argomento richiede uno strumento matematico non ancora introdotto (es. i tensori per la Relatività Generale), quello strumento viene insegnato *prima*, nel modulo di matematica (`01-matematica-per-fisici/`), non aggirato con un'analogia permanente.
- I numeri contano: quando ha senso, si fanno calcoli veri con valori reali (masse del Sole, raggio di Schwarzschild della Terra, temperatura di Hawking di un buco nero stellare, ecc.), non solo teoria astratta.

## Livello di rigore matematico

Si parte "universitario base" e si sale gradualmente verso "avanzato", modulo dopo modulo:

- Moduli 1-4 (matematica, meccanica, elettromagnetismo, relatività ristretta): livello liceo avanzato + primo anno di fisica universitaria. Qui si costruiscono gli attrezzi (vettori, calcolo differenziale, tensori elementari, elettromagnetismo di Maxwell).
- Moduli 5-8 (relatività generale, meccanica quantistica, fisica statistica, QFT): livello triennale/magistrale di fisica. Qui compaiono equazioni di campo, operatori, path integral (almeno nella forma concettuale correttamente enunciata).
- Moduli 9-11 (cosmologia, buchi neri avanzati, oltre il modello standard): si usa tutto il ferramenta costruita prima, a livello di ricerca introduttiva (quello che si vede in un primo corso di dottorato o in review articles).

## Come è organizzato ogni argomento

Ogni file di contenuto segue, quando possibile, questa struttura:

1. **Perché ci interessa** — che problema fisico risolve, dove si inserisce nel quadro generale.
2. **Intuizione** — l'idea in parole semplici, con analogie dichiarate.
3. **La fisica vera** — formalismo, formule, derivazioni chiave.
4. **Conti fatti bene** — almeno un esempio numerico concreto.
5. **Cosa NON dice questa teoria / dove si rompe** — limiti, casi patologici, collegamento all'argomento successivo.
6. **Per andare oltre** — riferimenti (libri, paper, lezioni) per chi vuole approfondire subito.

## Lingua

Tutto il materiale è in **italiano**. I termini tecnici internazionali (es. "redshift", "quench", nomi di equazioni) si tengono in originale con traduzione a fianco la prima volta che compaiono.

## Aggiornare lo stato

Ogni volta che si completa o si avanza in un argomento, va aggiornato `STATO-AVANZAMENTO.md` con data e riepilogo. Questo è ciò che permette a una sessione futura (umana o AI) di ripartire senza perdere il filo.
