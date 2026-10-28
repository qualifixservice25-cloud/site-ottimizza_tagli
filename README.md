# Qualifix Service - Ottimizza Tagli

Repository ufficiale per l'hosting della landing page e della privacy policy dell'app **Ottimizza Tagli**.

## Contenuti del Repository
- `index.html`: landing page dell'app.
- `privacy-policy.html`: informativa sulla privacy richiesta da Google Play (l'indirizzo non va cambiato: è quello registrato in Play Console).
- `stile.css`: la grafica di entrambe le pagine, con i colori dell'app (blu notte, arancio, blu acciaio).
- `font/`: Inter e Inter Display, ridotti ai caratteri latini e ospitati qui (nessuna richiesta a Google Fonts); licenza in `font/OFL.txt`.
- `img/`: i telefoni con le schermate dell'app (WebP), il foglio PDF di esempio, l'icona e le favicon.
- `feature-graphic-1024x500.png`: l'immagine in evidenza della scheda Play, usata anche per le anteprime dei link condivisi.
- `icona.png`, `favicon-180.png`, `store-icon-512.png`: l'icona dell'app in varie misure.
- `sitemap.xml`: le due pagine, da segnalare in Google Search Console.
- `play-store-testi.md`: testi per la scheda Play Store (non pubblicato).
- `.nojekyll`: dice a GitHub Pages di pubblicare i file così come sono.

Le immagini dei telefoni si rifanno dal repository dell'app (`store/sorgenti/README.md`): `cattura.js` fotografa le schermate dalla build web, `telefoni.js` le mette nei telefoni e `finitura-sito.py` le salva in WebP nella cartella `img/` di questo repository.

## Link Utili
- [Scarica l'app su Google Play](https://play.google.com/store/apps/details?id=org.qualifix.service.ottimizza_tagli)
- [Sito Ufficiale](https://qualifixservice25-cloud.github.io/site-ottimizza_tagli/)

## Pubblicazione (GitHub Pages)

Il sito pubblicato è quello del branch `main` (`Settings → Pages` → Source: branch `main`, cartella `/ (root)`). Per aggiornarlo si unisce in `main` il branch con le modifiche.

Il badge "Disponibile su Google Play" è l'immagine ufficiale caricata dal sito di Google, come chiedono le regole del marchio.

---
*Gestito da Qualifix Service - 2026*
