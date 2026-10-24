# Very SIMPLE Project

Sito delle consegne del gruppo SIMPLE per Fondamenti di Human-Computer Interaction (Politecnico di Milano, A.A. 2026/27).

Sito: https://ilyun34.github.io/progetto-hci-simple/

## Come si aggiorna

Il sito si aggiorna da solo: basta caricare i file nella cartella giusta.

- **Slide**: il PDF messo direttamente in `C1/`, `C2/`, ... diventa la slide della consegna (se ce n'è più di uno, vale il primo in ordine alfabetico).
- **Materiali**: ogni file in una sottocartella (es. `C2/Foto/`, `C2/Video/`) compare nella pagina, raggruppato col nome della sottocartella.
- **Nuova consegna**: aggiungi un blocco in `sito/_data/consegne.yml` e crea `C3/index.html` copiando `C2/index.html` e cambiando `codice` e `title`.
- **Dati personali** (consensi firmati, risposte grezze del sondaggio): vanno in `_riservato/`, che il sito non pubblica.

## Struttura

Nella radice del repository restano solo le cartelle delle consegne, `_riservato/` e i due file che GitHub Pages vuole lì: `index.html` (la home) e `_config.yml` (impostazioni). Tutto il resto del sito è in `sito/`:

- `sito/_data/consegne.yml`: elenco delle consegne (titolo, descrizione, scadenza, sezioni)
- `sito/_layouts/`: modelli delle pagine; `consegna.html` elenca da solo slide e materiali
- `sito/_includes/`: pezzi di pagina riusati
- `sito/assets/style.css`: stile comune
