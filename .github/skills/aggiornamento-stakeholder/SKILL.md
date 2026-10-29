---
name: aggiornamento-stakeholder
description: Prepara l'aggiornamento di un progetto per gli stakeholder (direzione, assistenza, team vicini) a partire dalle note del progetto, delle riunioni e delle decisioni. Una pagina, con lo stato, cosa è successo, i prossimi passi e le decisioni che servono da loro. Usala quando qualcuno chiede un aggiornamento, uno stato avanzamento o un report di progetto per gli stakeholder. Non usarla per le note di rilascio o per i verbali di una singola riunione.
---

# Aggiornamento per gli stakeholder

## Cosa fa

Legge le note di un progetto e prepara un aggiornamento di una pagina per chi non segue il progetto ogni giorno. Chi lo
riceve deve capire in un minuto se il progetto va bene e se serve una sua decisione. Non invia niente.

## Prima di iniziare

1. Chiedi di quale progetto si tratta, se non è chiaro.
2. Trova le note del progetto: la nota principale, le riunioni delle ultime due settimane, le decisioni. Se lavori in un
   vault con un `AGENTS.md`, segui le sue regole per sapere dove stanno.
3. Se non trovi la nota principale del progetto, fermati e chiedila.

## Come lavorare

1. **Stato**, una parola sola:
   - **in linea**: le scadenze reggono e non ci sono blocchi;
   - **a rischio**: una scadenza è in dubbio o c'è un blocco con una data per sbloccarlo;
   - **fermo**: c'è un blocco senza una data per sbloccarlo.
   Sotto, una frase che spiega perché.
2. **Cosa è successo**: al massimo 5 punti, dalle riunioni e dalle decisioni prese delle ultime due settimane.
3. **Prossimi passi**: le azioni aperte, con chi e entro quando, prese dalle note. Niente azioni inventate.
4. **Decisioni che servono da voi**: le decisioni rimandate che dipendono da chi riceve l'aggiornamento, o i blocchi che
   può sbloccare. Se non ce ne sono, scrivi "Nessuna".
5. **Rischi**: al massimo 3, solo se scritti nelle note.

## Cosa consegnare

Un file markdown `Aggiornamento AAAA-MM-GG.md` nella cartella del progetto, con queste sezioni nell'ordine: Stato,
Decisioni che servono da voi, Cosa è successo, Prossimi passi, Rischi. In fondo, le note da cui viene ogni punto, come
link.

## Cosa non fa

- Non inventa date, numeri o nomi: se mancano, scrive [DA VERIFICARE].
- Non usa termini tecnici o nomi interni senza spiegarli.
- Non invia l'aggiornamento.

## Prima di consegnare, ricontrolla

- [ ] Sta in una pagina.
- [ ] Lo stato è una parola sola ed è motivato.
- [ ] Ogni punto ha una nota da cui viene.
- [ ] Le decisioni richieste sono in alto, prima di tutto il resto.

## Come si verifica

> Input: un progetto fermo in attesa di una revisione esterna, con due riunioni nelle ultime due settimane.
> Risultato atteso: stato "a rischio" o "fermo" a seconda che la revisione abbia una data; la revisione tra le decisioni
> o i blocchi in alto; nessuna azione senza responsabile.
