# Spiagge Sud Sicilia

Web app statica per GitHub Pages.

## File principali

- `index.html`: applicazione completa.
- `manifest.json`: configurazione PWA installabile.
- `service-worker.js`: cache base per apertura rapida e fallback offline parziale.
- `icons/`: icone per installazione su smartphone.

## Pubblicazione

Carica tutti i file nella root del repository GitHub e configura:

- Settings -> Pages
- Source: Deploy from a branch
- Branch: main
- Folder: / (root)

URL atteso: `https://pompeoambiente.github.io/spiagge-sud-sicilia/`
