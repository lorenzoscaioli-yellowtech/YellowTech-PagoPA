---
name: note-di-rilascio
description: Prepara la bozza delle note di rilascio per utenti e assistenza partendo dai lavori conclusi nello sprint. Usala alla fine di ogni sprint prima del rilascio. Non usarla per documenti di progettazione o riassunti di riunioni.
---

# Nota di rilascio

## Cosa fa

Questa skill elabora i lavori conclusi durante lo sprint per generare la bozza delle note di rilascio, strutturata in due sezioni: una per gli utenti finali (store) e una per l'assistenza clienti.

## Prima di iniziare

1. Documenti di riferimento:
   - [[3-Risorse/Procedure/Come scrivo le note di rilascio]]
   - [[2-Aree/Prodotto/Registro decisioni]]
2. Dati in ingresso:
   - Nota dello sprint in `2-Aree/Prodotto/Sprint/` (solo lavori con stato "fatto" e "visibile agli utenti: sì").

## Come lavorare

1. Identifica i lavori completati e visibili leggendo la nota dello sprint.
2. Consulta il [[2-Aree/Prodotto/Registro decisioni]] per contestualizzare i cambiamenti.
3. Redigi la versione per gli utenti (max 500 caratteri, linguaggio semplice).
4. Redigi la versione per l'assistenza ([[Paolo Grandi]]) includendo i dettagli sui cambiamenti, FAQ e problemi noti.

## Cosa consegnare

Il file della nota di rilascio in `3-Risorse/Note di rilascio/Versione X.Y.md`, completo di front-matter (`tipo: note di rilascio`, `versione`, `sprint`, `data`).

## Cosa non fa

- Non cita lavori non finiti o non visibili agli utenti.
- Non promette date o funzioni future.
- Non include problemi noti nella versione per gli utenti.

## Prima di consegnare, ricontrolla

- [ ] La versione utente è sotto i 500 caratteri?
- [ ] La versione assistenza include le risposte per gli utenti?
- [ ] La versione assistenza contiene i problemi noti?
- [ ] Il front-matter della nota è compilato correttamente?
