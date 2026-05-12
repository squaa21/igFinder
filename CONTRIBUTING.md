# Come contribuire a igFinder

Grazie per l'interesse nel progetto! Ecco come puoi aiutare.

## 🐛 Segnalare un bug

Apri una [Issue](https://github.com/squaa21/igFinder/issues/new) includendo:

- **Descrizione** del problema
- **Passi per riprodurlo** (es. "Ho caricato il file X, poi...")
- **Comportamento atteso** vs **comportamento reale**
- **Browser e sistema operativo** usati
- Se possibile, uno screenshot

## 💡 Proporre una funzionalità

Apri una Issue con il tag `enhancement` e descrivi:

- Cosa vorresti aggiungere
- Perché sarebbe utile
- Come immagini che funzioni

## 🔧 Inviare una Pull Request

1. Fai un **fork** del repository
2. Crea un branch descrittivo:
   ```bash
   git checkout -b fix/parser-json
   git checkout -b feature/esporta-csv
   ```
3. Fai le modifiche su `index.html` (tutta l'app è in un file solo)
4. Testa nel browser prima di fare commit
5. Commit con un messaggio chiaro:
   ```bash
   git commit -m "Fix: parser JSON following per nuovo formato Instagram"
   git commit -m "Feature: aggiunge esportazione CSV"
   ```
6. Push e apri la Pull Request su GitHub

## 📐 Linee guida sul codice

- Tutto il codice sta in `index.html` — HTML, CSS e JS nello stesso file
- CSS con variabili custom (`--accent`, `--bg`, ecc.) per i colori
- JS vanilla, nessuna dipendenza esterna
- Commenti in italiano o inglese vanno bene entrambi
