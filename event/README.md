# Guida alle mostre d'artista (Event Room)

Questa cartella contiene le immagini delle mostre che non sono ancora su OpenSea.
La mostra si gestisce dalla pagina **event-admin.html** del sito.

---

## Preparare una nuova mostra

1. **Immagini nuove, non ancora su OpenSea** (facoltativo)
   - Apri questa cartella `event` su GitHub → **Add file → Upload files**.
   - Trascina le immagini e premi **Commit changes**.
   - Usa nomi semplici, senza spazi, per esempio `new-muse.jpg`.

2. **Apri la pagina di amministrazione**
   - Indirizzo: lo stesso della galleria, con `event-admin.html` al posto di `gallery3d.html`.
   - La prima volta scrivi la **parola segreta** e premi **Unlock**. Il browser la ricorda.

3. **Compila la mostra**
   - **Title**: il titolo della mostra.
   - **Short presentation**: una frase di presentazione.
   - **Opens / Closes**: data e ora di apertura e di chiusura.
   - **Artworks** (massimo 12):
     - *OpenSea link*: incolla il link della pagina dell'NFT.
     - *Image on the site*: scrivi `event/` e il nome del file, esattamente uguale, maiuscole comprese. Per esempio `event/new-muse.jpg`.
   - **Animation**: *one artwork on all the walls*, *a mix of artworks* oppure *alternate*.
   - **Music**: scegli 2 o 3 brani. Con ▶ puoi ascoltarli.

4. **Controlla il risultato**
   - Premi **👁 Save & preview**: la mostra si apre subito, anche prima della data.

5. **Accendi la mostra**
   - Spunta **Exhibition ON** e premi **💾 Save**.

6. **Annuncia la mostra**
   - Copia il **link da annunciare** in fondo alla pagina (`…/gallery3d.html?event`) e pubblicalo su Discord e X.

---

## Cosa succede da solo

- **Prima dell'apertura**: la mostra è la prima stanza di tutte le gallerie e mostra il conto alla rovescia.
- **All'ora di apertura**: parte lo spettacolo immersivo.
- **Alla data di chiusura**: la mostra sparisce da sola.

## Spegnere prima del previsto

Nella pagina di amministrazione premi **Turn the exhibition off**.

---

## Se qualcosa non funziona

- **"Wrong secret word"**: la parola deve essere identica a quella scritta nell'Apps Script, nella riga `const EVENT_ADMIN_KEY = "…";`.
- **Un'immagine non compare**: controlla che il nome scritto nella pagina sia identico al file nella cartella `event`, maiuscole ed estensione comprese (`.jpg`, `.png`…).
- **Hai appena caricato qualcosa su GitHub**: aspetta 1–2 minuti, poi ricarica la pagina con **Ctrl+F5**.
- **Hai aggiornato l'Apps Script**: ricorda di riscrivere la parola segreta, poi **Gestisci deployment → ✏️ → Nuova versione**. Mai "Nuovo deployment".

---

## Musiche delle mostre

| File | Brano |
|---|---|
| gallery-music.mp3 | Towards the Light (ambient) |
| gallery-music-2.mp3 | Placeit World |
| gallery-music-3.mp3 | Pop Track 03 |
| gallery-music-4.mp3 | Hazy After Hours |
| gallery-music-5.mp3 | Smooth Meditation |
| gallery-music-6.mp3 | Cyberpunk City |
| gallery-music-7.mp3 | Chill Bro |
| gallery-music-8.mp3 | Romantic 01 |
| gallery-music-9.mp3 | Cyberpunk Futuristic Background |
| gallery-music-10.mp3 | Cyberpunk Futuristic Music |
| gallery-music-11.mp3 | Anime Cyberpunk |

Le musiche del tour (`tour-music-1…4.mp3`) sono separate e non si usano nelle mostre.
