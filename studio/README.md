# Studio — Dashboard

Questa cartella contiene tutte le materie. **Ogni materia ha una cartella indipendente** con i materiali originali e i file necessari a riprendere lo studio tra chat diverse.

## Materie

| Materia | Cartella | Stato |
|---|---|---|
| Computer Logic | [Computer Logic](Computer%20Logic/README.md) | In corso |
| Calculus 1 | [Calculus 1](Calculus%201/README.md) | In attesa dei materiali |

Per aggiungere una materia, copia la struttura da [_TEMPLATE_MATERIA](_TEMPLATE_MATERIA/README.md), modifica i nomi e carica i file originali nella nuova cartella.

## Prima di ogni sessione

ChatGPT deve leggere, nella cartella della materia scelta:
1. README.md — materiali e panoramica;
2. AI_INSTRUCTIONS.md — metodo di lavoro;
3. AI_CONTEXT.md — checkpoint per la prossima chat;
4. PROGRESS.md — stato di ogni argomento;
5. TOPIC_MAP.md — ordine degli argomenti e pagine verificate;
6. STUDY_NOTES.md — appunti utili;
7. SESSION_LOG.md — cronologia, se serve.

## Regole

- Studiare un argomento per volta e verificare la comprensione prima di proseguire.
- Usare i materiali del corso come fonte primaria.
- Non dichiarare di aver esaminato file o pagine non realmente aperti.
- Non inventare pagine o argomenti: segnalare le ipotesi come da verificare.
- Conservare gli originali.
- Dopo ogni sessione, aggiornare la memoria se GitHub consente la scrittura; se non può salvare, ChatGPT deve fornire i testi aggiornati da copiare.
- La memoria deve contenere informazioni didattiche e operative, non ragionamenti interni.

## Workflow PDF

Il workflow si trova in .github/workflows/pdf-preview.yml. Per richieste di pagine specifiche usa study-request.json nella root del repository. Controlla sempre sia l'esito della run sia l'accessibilità e la visualizzazione dell'artefatto.
