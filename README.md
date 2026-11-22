# Studio Trad — opnameboeking

Publieke boekingspagina + regel-gebaseerde beschikbaarheidsdata voor Studio Trad.

- `index.html` — de boekingspagina (kalender + checkout-flow)
- `availability.json` — beschikbaarheid, 2x per dag ververst door Vibe (regels uit de studioplanning)

De pagina haalt `availability.json` op bij het laden; de ingebakken fallback is alleen voor noodsituaties.
