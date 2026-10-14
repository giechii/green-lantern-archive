# Lanterna Verde Archive

Archivio cronologico personale delle storie di Lanterna Verde, con tre linee temporali: **Green Lantern**, **Green Lantern Corps** ed **Eventi DC**.

## Pubblicazione con GitHub Pages

1. Apri **Settings** del repository.
2. Seleziona **Pages** nel menu laterale.
3. In **Build and deployment**, scegli **Deploy from a branch**.
4. Seleziona il branch **main** e la cartella **/(root)**, quindi premi **Save**.
5. Attendi qualche minuto: GitHub mostrerà l'indirizzo pubblico del sito nella stessa pagina.

## File del sito

- `index.html`: struttura della pagina.
- `style.css`: aspetto grafico.
- `app.js`: interazione e disegno della timeline.
- `arcs.json`: dati degli story arc.

## Aggiungere uno story arc

Modifica `arcs.json`, aggiungendo un oggetto nell'array `arcs`. I valori ammessi per `lanes` sono:

- `main`: Green Lantern
- `corps`: Green Lantern Corps
- `dc`: Eventi DC

Se un arco coinvolge più linee temporali, inserisci più valori in `lanes`: lo stesso arco verrà mostrato nelle colonne pertinenti. Le date e i dettagli del database sono una base iniziale da verificare e ampliare.

## Contenuti iniziali

- Flashpoint
- Twilight of the Guardians
- Last Charge

La testata *Hal Jordan and the Green Lantern Corps* è collocata nella colonna **Green Lantern**, come richiesto.