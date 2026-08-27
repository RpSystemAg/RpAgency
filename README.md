# RpAgency

Repository di distribuzione della **RP STUDIO Unified Suite**.

## Contenuto

| File | Descrizione |
| --- | --- |
| `RP-STUDIO-Unified-Suite-1.0.0-10000-Workflows-LATEST-ALIGNED-2026-08-25.zip` | Pacchetto completo della suite 1.0.0, allineato al 25/08/2026, con 10.000 workflow enterprise. |

Lo ZIP contiene l'intero albero `PR-STUDIO-Unified-Suite-1.0.0/`:

- `prstudio-unified-control/` — plugin WordPress di controllo (PHP)
- `prstudio-unified-browser-agent/` — estensione browser agent
- `.github/` — workflow CI, script di certificazione e build
- `docs/`, `evidence/`, `quality/`, `tests/`, `bench/` — documentazione, evidenze e verifiche

## Documentazione

| Documento | Cosa contiene |
| --- | --- |
| [`docs/GUIDA.md`](docs/GUIDA.md) | Guida completa: prerequisiti, installazione plugin WordPress, collegamento del plugin ChatGPT, modalita sviluppatore Chrome, pairing dei tre componenti, riferimento delle capacita, 50 prompt ottimizzati, troubleshooting e limiti dichiarati. |
| [`docs/index.html`](docs/index.html) | Stessa guida in versione grafica, con riproduzioni passo passo delle schermate. Aprila in locale dopo il clone, oppure abilita GitHub Pages sulla cartella `/docs`. |

## Uso

Scaricare lo ZIP dalla pagina del repository ed estrarlo:

```bash
unzip RP-STUDIO-Unified-Suite-1.0.0-10000-Workflows-LATEST-ALIGNED-2026-08-25.zip
```

Le istruzioni di installazione e architettura si trovano dentro il pacchetto
(`ARCHITECTURE-1.0.0.md`, `CHANGELOG-1.0.0.md`, `AGENTS.md`).
