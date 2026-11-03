# ZDOS — portfolio e progetti

Landing statica in italiano per presentare il codice sperimentale ZDOS e quattro progetti dell’autore, con collegamenti verificati ai siti e ai repository. Il testo non fa offerte finanziarie e non attribuisce prezzo, ticker, supply, quotazione o rendimento non documentati.

## Contenuto

- `site/` — artefatto statico da distribuire su GitHub Pages.
- `.github/workflows/pages.yml` — deploy Pages su push a `main` e tramite `workflow_dispatch`.
- `SOURCES.md` — fonti e note di verifica.
- `TODO.md` — stato di completamento e blocco di pubblicazione.

## Preview locale

```sh
python3 -m http.server 3000 --bind 127.0.0.1 --directory site
```

## GitHub Pages

Il workflow pubblica `site/` e usa GitHub Actions come origine Pages. Nel repository ospitante, abilita GitHub Pages selezionando **Build and deployment → GitHub Actions**; quindi il push su `main` avvia la distribuzione. Se il repository è `high-cde.github.io`, il sito è previsto alla radice di `https://high-cde.github.io/`. Il sorgente della pagina resta in `site/` ed è autonomo, con grafica SVG locale come fallback.

La pagina usa link relativi per foglio di stile, JavaScript e favicon. Le schede mostrano sia il sito pubblicato sia il repository sorgente di ciascun progetto. Per modificare descrizioni o riferimenti, aggiorna `site/index.html` e `SOURCES.md` mantenendo distinte le informazioni dichiarate dai fatti verificati.
