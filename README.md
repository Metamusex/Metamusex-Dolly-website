# MetaMuseX & Dolly — sito + Collector Album

## Cosa c'è in questa cartella
- `index.html` — la homepage del sito (About, collezioni, social, link al Collector Album)
- `collector-album.html` — la dapp che legge il wallet e mostra l'album da collezione
- `images/` — le immagini NFT usate nelle card Summer Vibes e Crazy Dolly

## Come pubblicarlo con GitHub Pages
1. Crea un repository su GitHub (es. `metamusex-dolly-site`).
2. Carica **tutto il contenuto di questa cartella** nella root del repository (non la cartella stessa: i file `index.html`, `collector-album.html`, `images/`, `README.md` devono stare direttamente nella root, altrimenti i link tra le pagine e i percorsi delle immagini non funzionano).
3. Vai su **Settings → Pages** del repository.
4. In "Source" seleziona il branch (es. `main`) e la cartella `/ (root)`.
5. Salva: GitHub ti darà un URL tipo `https://<tuo-utente>.github.io/<nome-repo>/` — quello è il sito live.

## Note
- I link ai social/OpenSea nel sito puntano già ai profili/collezioni ufficiali — se cambiano in futuro vanno aggiornati a mano dentro `index.html`.
- `collector-album.html` contiene la tua OpenSea API key in chiaro nel codice sorgente (è inevitabile per una pagina puramente client-side) — vedi il commento in cima al file per i dettagli.
- Se aggiungi altre immagini in futuro, mettile dentro `images/` e usa un percorso relativo tipo `images/nome-file.png` per restare coerente col resto del sito.
