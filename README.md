# ZDOS — portfolio e progetti

Landing statica in italiano per presentare il codice sperimentale ZDOS e quattro progetti dell’autore, con collegamenti verificati ai siti e ai repository. Il testo non fa offerte finanziarie e non attribuisce prezzo, ticker, supply, quotazione o rendimento non documentati.

## Contenuto

- `docs/` — sito statico da distribuire su GitHub Pages.
- `SOURCES.md` — fonti e note di verifica.
- `TODO.md` — stato di completamento e pubblicazione.

## Anteprima locale

```sh
python3 -m http.server 3000 --bind 127.0.0.1 --directory docs
```

## GitHub Pages

La pagina non richiede GitHub Actions. Dopo il trasferimento del sorgente, in **Settings → Pages** scegli **Deploy from a branch**, poi il branch `main` e la cartella `/docs`. Su `high-cde.github.io`, il sito sarà disponibile alla radice di `https://high-cde.github.io/` dopo la prima pubblicazione. `docs/.nojekyll` mantiene gli asset statici invariati.

I link a CSS, JavaScript, favicon e artwork locale sono relativi. Le schede mostrano sia il sito pubblicato sia il repository sorgente di ciascun progetto. Per aggiornare descrizioni o riferimenti, modifica `docs/index.html` e `SOURCES.md`, mantenendo distinte le informazioni dichiarate dai fatti verificati.
