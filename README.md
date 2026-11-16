# Collezioni

App personale (PWA) per gestire le collezioni: vini, whisky, rum, carte Pokémon e Magic, francobolli, monete (antiche, storiche, moderne), libri, film, giochi da tavolo e videogiochi.

## Come funziona
- **Dati sul dispositivo**: tutto è salvato nel browser (IndexedDB), foto comprese. Nessun server, nessun account.
- **Artifact su Claude**: la stessa app gira come artifact su Claude, dove ci sono le funzioni con l'IA (scheda da foto, quotazioni con ricerca web). I dati passano tra artifact e app con **Backup → Esporta / Importa** (file JSON, foto incluse). L'import unisce i dati tenendo la versione più recente di ogni pezzo.
- **Cataloghi carte** (solo app): Pokémon da [TCGdex](https://tcgdex.dev), Magic da [Scryfall](https://scryfall.com). Elenco set, completamento, aggiunta di set interi, carte mancanti nei desideri e prezzi Cardmarket aggiornati.

## File
- `index.html` — l'app (lo stesso file è pubblicato anche come artifact su Claude)
- `manifest.webmanifest`, `sw.js`, `icon-*.png` — installazione come app

## Pubblicazione
GitHub Pages: Settings → Pages → Source: *Deploy from a branch* → Branch `main`, cartella `/ (root)`.
