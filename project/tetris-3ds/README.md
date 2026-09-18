# Tetris 3DS (.3dsx)

Tetris homebrew per Nintendo 3DS con grafica GPU (citro2d):
blocchi colorati con highlight, ghost piece, preview prossimo pezzo,
punteggio/livello su schermo superiore, aiuto su schermo inferiore.

```bash
source ../../tools/env.sh
make        # output/tetris-3ds.3dsx + .smdh
make clean
```

Installazione su 3DS: copia `output/tetris-3ds.3dsx` e `output/tetris-3ds.smdh`
in `sd:/3ds/tetris-3ds/`, avvia da Homebrew Launcher (hbmenu).

Comandi: D-Pad muovi / Giu veloce, A/Su ruota, B hard drop, START esci.
A su GAME OVER = ricomincia. Punteggio stile guideline
(100/300/500/800 × livello, livello ogni 10 linee), bag 7 pezzi.
