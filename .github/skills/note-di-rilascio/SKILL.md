---
name: note-di-rilascio
description: Prepara la bozza delle note di rilascio per utenti e assistenza clienti a partire dai lavori fatti nello sprint. Usala alla fine di ogni sprint prima del rilascio della versione. Non usarla per comunicazioni generiche o annunci di marketing.
---

# Skill: note-di-rilascio

## Cosa fa

Genera la bozza delle note di rilascio in formato Obsidian, includendo la sezione per gli utenti (testo per gli store) e quella per l'assistenza clienti ([[Paolo Grandi]]), basandosi sui task completati nello sprint.

## Prima di iniziare

1. Documenti di riferimento:
   - [[Registro decisioni]] (per il contesto dei cambiamenti).
   - [[Come scrivo le note di rilascio]] (la procedura originale con le regole di stile).
2. Dati in ingresso:
   - Nota dello sprint in `2-Aree/Prodotto/Sprint/`.
3. Se non trovi la nota dello sprint o non è chiaro quali task siano "fatti" e "visibili agli utenti", chiedi prima di procedere.

## Come lavorare

1. Identifica i task con stato "fatto" e "visibile agli utenti: sì" nella nota dello sprint.
2. Incrocia i task con il [[Registro decisioni]] per integrare il "perché" dietro i cambiamenti.
3. Scrivi la versione per gli utenti: max 500 caratteri, frasi brevi, "Ora puoi...", niente tecnicismi.
4. Scrivi la versione per l'assistenza: spiega cosa cambia per l'utente, quali domande arriveranno, cosa rispondere, e aggiungi i problemi noti.
5. Usa il template `Template/Note di rilascio.md` (o il formato di [[Versione 4.7]]).

## Cosa consegnare

Una nota in `3-Risorse/Note di rilascio/Versione X.Y.md` con front-matter: `tipo: note di rilascio`, `versione`, `sprint`, `data`.

## Cosa non fa

- Non includere lavori non finiti o non visibili agli utenti.
- Non promettere date o funzionalità future.
- Non inserire i problemi noti nella versione destinata agli utenti finali.

## Prima di consegnare, ricontrolla

- [ ] I task citati sono tutti contrassegnati come "fatto" e "visibile agli utenti".
- [ ] La versione utente è sotto i 500 caratteri e usa un linguaggio semplice.
- [ ] La versione assistenza contiene risposte alle probabili domande e i problemi noti.
- [ ] Non sono presenti promesse su rilasci futuri.
