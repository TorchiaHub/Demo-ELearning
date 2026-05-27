# Demo Content Capture Plan

Questo documento serve a preparare i nuovi screenshot e video pubblici della demo MyLearn Enbital. L'obiettivo e mostrare il valore del progetto senza esporre codice, terminali, log interni o informazioni non sanificate.

## Obiettivo Della Capture

Creare un pacchetto media da usare nel README pubblico e, se utile, in portfolio personale o candidatura stage.

Il pacchetto consigliato e:

- 1 video walkthrough da 45-60 secondi;
- 1 video breve dedicato all'avatar da 10-15 secondi;
- 6 screenshot puliti;
- 1 thumbnail principale per il README;
- eventuale GIF breve solo se il peso resta ragionevole.

## Prima Di Registrare

Controlla che siano pronti:

- server e client avviati in modalita demo;
- browser desktop aperto sulla dashboard;
- telefono reale collegato alla stessa rete LAN, oppure viewport mobile pulito se stai registrando in locale;
- nessun terminale visibile;
- nessun percorso locale visibile;
- nessuna tab di debug aperta;
- nessun event log con dati tecnici in primo piano;
- audio dell'avatar funzionante;
- luminosita e zoom del browser coerenti.

## Screenshot Da Rifare

Salva i nuovi file nella cartella:

```text
assets/screenshots/
```

Usa questi nomi per sostituire gli attuali placeholder.

| File | Dove prenderlo | Cosa deve mostrare |
|---|---|---|
| `dashboard.png` | Dashboard iniziale | Cornice prodotto, corsi, ingresso alla demo |
| `course-home.png` | Home corso / ingresso course player | Elena visibile, CTA corso, tono premium |
| `pairing.png` | Blocco pairing | QR/codice e relazione desktop-telefono |
| `concept-map.png` | Blocco formativo lungo | Avatar, card didattiche e mappa concettuale attiva |
| `interaction.png` | Un blocco test/interazione | Scelta dal telefono visualizzata sul desktop |
| `mobile-companion.png` | Schermo telefono | Companion mobile con domanda o scelta operativa |

### Screenshot Prioritario

Il piu importante e `course-home.png`, perche puo diventare la thumbnail del video principale nel README.

## Video Walkthrough Principale

Durata consigliata: 45-60 secondi.

Formato consigliato:

- MP4;
- H.264;
- AAC;
- 1080p o 720p;
- sotto 10 MB se vuoi caricarlo facilmente come asset GitHub.

### Script Di Registrazione

1. **Dashboard, 5 secondi**  
   Mostra l'ingresso nella demo. Messaggio da comunicare: non e una slide deck, e un ambiente formativo.

2. **Avatar e course player, 8-10 secondi**  
   Avvia il corso e mostra Elena. Fai sentire un breve estratto audio.

3. **Pairing telefono, 8-10 secondi**  
   Mostra QR/codice e telefono collegato. Se registri telefono reale, tieni il telefono in un'inquadratura leggibile o registra anche lo schermo mobile.

4. **Blocco formativo, 12-15 secondi**  
   Mostra una spiegazione con card e mappa concettuale che avanzano seguendo il parlato dell'avatar.

5. **Interazione mobile, 12-15 secondi**  
   Rispondi dal telefono e mostra il desktop aggiornarsi in tempo reale.

6. **Chiusura, 5-8 secondi**  
   Mostra quiz finale, riepilogo o event log demo solo se e pulito e comprensibile. Evita viste troppo tecniche.

## Video Avatar Dedicato

Durata consigliata: 10-15 secondi.

Mostra Elena in un punto in cui:

- il volto e ben visibile;
- il lip sync e chiaro;
- l'audio e pulito;
- lo sfondo trasparente e integrato nella UI;
- non si vede il green screen o la pipeline tecnica.

Nome consigliato:

```text
assets/media/avatar-pipeline-sample.mp4
```

Nel README puoi linkarlo come sample o usarlo come supporto nella sezione Avatar Pipeline.

## Cosa Raccontare Nel Video

Se aggiungi voice-over o testo in sovrimpressione, usa questi messaggi:

- "Avatar generato con pipeline HeyGen + ElevenLabs."
- "Lezioni costruite in blocchi indipendenti."
- "Card e mappa concettuale seguono il parlato dell'avatar."
- "Il telefono diventa il dispositivo di interazione."
- "Micro-learning: spiegazione breve, verifica immediata, avanzamento progressivo."
- "Authoring futuro con human-in-the-loop su contenuti gia verificati."

## Cosa Non Mostrare

Non includere:

- editor di codice;
- terminale;
- branch git;
- percorsi locali;
- file `.env`;
- payload API;
- console browser;
- log Socket.IO;
- schermate con errori o warning;
- documenti interni non pensati per pubblicazione.

## Dove Inserire I Media

| Tipo | Cartella | Note |
|---|---|---|
| Screenshot | `assets/screenshots/` | Sostituire i PNG esistenti mantenendo gli stessi nomi |
| Video brevi | `assets/media/` | Preferire MP4 per pubblicazione |
| Video pesanti | GitHub Release/Issue o piattaforma esterna | Linkare dal README con thumbnail |
| Thumbnail | `assets/screenshots/course-home.png` o file dedicato | Usare come immagine cliccabile |

## Checklist Finale

Prima di pubblicare:

- README aperto in anteprima GitHub;
- link immagini funzionanti;
- link video funzionanti;
- nessun codice sorgente nel repository;
- nessun dato locale visibile nei media;
- video sotto peso ragionevole;
- audio comprensibile;
- Elena, blocchi e telefono chiaramente riconoscibili;
- messaggio "human-in-the-loop" presente dove si parla di generazione assistita.

