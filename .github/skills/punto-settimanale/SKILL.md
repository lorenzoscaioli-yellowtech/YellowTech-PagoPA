---
name: punto-settimanale
description: Prepara il punto settimanale sui progetti in corso per il/la responsabile di prodotto partendo dalle note del vault. Usala quando chiedo di preparare il punto settimanale, il riepilogo del venerdì o lo stato della settimana. Non usarla per aggiornare le singole note di progetto da Slack o mail, per sistemare riunioni dall'Inbox o per scrivere one-pager e note di rilascio.
---

# Punto settimanale

## Cosa fa

Raccoglie gli aggiornamenti degli ultimi sette giorni dai progetti attivi o in attesa nel vault e prepara il punto settimanale sintetico (massimo dieci righe) per il/la responsabile di prodotto, pronto da salvare in `2-Aree/Prodotto/Punti settimanali/`.

## Prima di iniziare

1. Leggi i documenti di riferimento nel vault (se presenti) senza ricopiarli:
   - la procedura in `3-Risorse/Procedure/Come preparo il punto settimanale.md`;
   - la nota della persona destinataria in `3-Risorse/Persone/`.
2. Raccogli i dati in ingresso:
   - le note dei progetti in `1-Progetti/` che hanno nel front-matter `stato: attivo` o `stato: in attesa`;
   - tutte le note di riunione e gli aggiornamenti degli ultimi sette giorni nelle cartelle di quei progetti;
   - le azioni `@io` ancora aperte (`- [ ]`).
3. Se la data di riferimento non è chiara o mancano le note della settimana per i progetti attivi, fermati e chiedilo.

## Come lavorare

1. Leggi la procedura in `3-Risorse/Procedure/Come preparo il punto settimanale.md` e la nota della persona destinataria in `3-Risorse/Persone/` (se presenti).
2. Individua in `1-Progetti/` tutti i progetti con `stato: attivo` o `stato: in attesa`.
3. Esamina per ciascun progetto la nota principale, le riunioni e gli aggiornamenti degli ultimi sette giorni e le azioni `@io` aperte (`[ ]`) o chiuse nella settimana (`[x]`).
4. Estrai le decisioni che servono dal/dalla responsabile, le attività concluse nella settimana e i prossimi passi della settimana successiva con il relativo responsabile.
5. Scrivi il punto settimanale in massimo dieci righe seguendo l'ordine e le regole previste, citando per ogni punto la nota da cui proviene come link `[[...]]` e indicando chiaramente eventuali dati da verificare.
6. Salva la nota nel percorso previsto con il front-matter richiesto.

## Cosa consegnare

Un file salvato in `2-Aree/Prodotto/Punti settimanali/AAAA-MM-GG Punto settimanale.md` (con la data nel formato `AAAA-MM-GG`), strutturato così:

```markdown
---
tipo: punto settimanale
data: AAAA-MM-GG
---

# Punto settimanale AAAA-MM-GG

1. **Serve una decisione:** cosa deve decidere il/la responsabile, se c'è qualcosa (con link `[[...]]` alla nota di origine).
2. **Fatto:** quello che si è chiuso nella settimana (con link `[[...]]` alle note di origine).
3. **Prossimi passi:** quello che parte la settimana dopo, con chi lo fa (inclusi i compiti `@io` e i link `[[...]]` alle note di origine).
```

Il testo del punto deve restare entro le dieci righe complessive e citare sempre persone e progetti come link `[[Nome Cognome]]` e `[[Nome progetto]]`.

## Cosa non fa

- Non aggiunge mai date o stime che non sono scritte nelle note del vault.
- Non inserisce punti privi del link `[[...]]` alla nota da cui provengono.
- Non dà per certi dati marcati come da verificare: segnala sempre se un dato è da verificare.
- Non include progetti con stato `in chiusura` o `archiviato`.
- Non invia messaggi su Slack né mail.

## Prima di consegnare, ricontrolla

- [ ] Il file è salvato in `2-Aree/Prodotto/Punti settimanali/AAAA-MM-GG Punto settimanale.md` con il front-matter `tipo: punto settimanale` e `data`.
- [ ] Il testo rispetta il limite di massimo dieci righe e l'ordine delle tre sezioni (**Serve una decisione**, **Fatto**, **Prossimi passi**).
- [ ] Ogni punto ha il link `[[...]]` alla nota da cui viene, e persone e progetti sono citati come link esistenti.
- [ ] Non ci sono date o stime inventate e i punti incerti sono segnalati come da verificare.
