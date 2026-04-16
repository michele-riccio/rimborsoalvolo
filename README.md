# Cruscotto Strategico — RimborsoalVolo × Ribrain Studio

Aprile 2026 · Uso confidenziale

## Struttura

| File | Contenuto |
|------|-----------|
| `index.html` / `m0.html` | Executive Summary — punto di entrata |
| `m1.html` | Mercato & Gap di Consapevolezza |
| `m2.html` | Competitor Map |
| `m3.html` | Voice of Customer (Trustpilot) |
| `m4.html` | Personas |
| `m5.html` | Mappa del Momento |
| `m6.html` | Benchmark Creativi |
| `m7.html` | Regolamentazione Aeroporti |

## Deploy su Vercel

1. Carica questa cartella su GitHub come repository
2. Vai su [vercel.com](https://vercel.com) → New Project → Import da GitHub
3. Vercel rileva automaticamente i file statici — zero configurazione necessaria
4. URL root → `index.html` (Executive Summary)

## Navigazione

Ogni pagina contiene:
- **Menu hamburger** (☰ in alto a destra) — overlay fullscreen con tutti i moduli
- **Navbar fissa** in basso — accesso diretto a tutti i moduli
- **Pulsante Fonti** (in basso a destra) — drawer con tutti i riferimenti cliccabili

## Note tecniche

Tutti i file sono **self-contained** — nessuna dipendenza esterna oltre ai font Google e GSAP CDN.
Le navigazioni tra moduli funzionano solo se tutti i file sono nella stessa cartella/dominio.
