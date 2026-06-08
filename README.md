# 🏃 Running Lab — DaiKapo → Hyrox Loading

Dashboard personale di allenamento verso la **mezza maratona sub-2h** (ottobre 2026), base per un futuro **Hyrox**.

## 🔗 Dashboard live

**→ [lucamatteuzzi99-arch.github.io/Running-Lab](https://lucamatteuzzi99-arch.github.io/Running-Lab/)**

> Se il link non si apre, attiva GitHub Pages: **Settings → Pages → Source: Deploy from a branch → `main` / root**. Online in 1-2 minuti.

## Cosa c'è dentro

- `index.html` — dashboard self-contained (HTML/CSS/JS, nessuna dipendenza). Si apre anche in locale con doppio click.

## La dashboard mostra

- **Il viaggio** — km totali, passo medio, sessioni, FC media (calcolati dai dati, mai hardcodati)
- **Progressione settimanale** — barre km + linea di trend
- **Calendario** — ogni corsa tappabile per il dettaglio (passo, split, zone, FC)
- **Settimane del piano** — sessioni pianificate con target di passo e zona
- **Le 5 zone di passo + FC** e **le 4 fasi** (Base → Build → Specifico → Taper)
- **Recap** completo con distribuzione zone vs target ideale

## Piano in breve

| Fase | Periodo | Focus |
|------|---------|-------|
| Base | 15 giu → 19 lug | Costruire il fiato, tutto lento (Z2) |
| Build | 20 lug → 23 ago | Entra il ritmo gara (~5'40"/km) |
| Specifico | 24 ago → 27 set | Passo mezza, lunghi, picco volume |
| Taper | 28 set → gara | Scarico, gambe fresche |

**Regola d'oro:** il lungo della domenica è non negoziabile. L'80% del volume va lento. Mattoni, non razzi. 🧱

## Come si aggiorna

I dati vivono in 3 oggetti JS dentro `index.html` (`workouts` / `splits` / `ROUTES`), uno per data. Si aggiunge una sessione innestando una voce — la struttura e i totali si ricalcolano da soli. Dopo il commit su `main`, GitHub Pages ripubblica in 1-2 minuti.

---

*Accento arancione Strava `#fc4c02` · font Syne + DM Mono · fonte dati: Strava → Garmin → screenshot.*
