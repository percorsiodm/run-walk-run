# Run Walk Run — la settimana

Piano settimanale personale di run walk run, con esercizi leggeri di corpo libero. Sito statico a file singolo, nessuna build richiesta.

## Contenuto

- **I sette giorni**: sequenza dettagliata di cammino/corsa per ogni giorno (facile, piramide, resistenza, riposo), con il giorno corrente aperto automaticamente
- **Corpo libero**: routine di 15-20' (plank, flessioni, squat, ponte glutei, side plank, stretching) da fare martedì o giovedì, con checklist che si salva sul telefono e si resetta ogni lunedì
- Domenica sempre riposo fisso

## Come pubblicarlo

### GitHub Pages
1. Carica `index.html` nella root del repository
2. Settings → Pages → Source: Deploy from branch → `main` → `/ (root)`
3. Il sito sarà raggiungibile su `https://<utente>.github.io/<repository>`

### Netlify
Collega il repository a Netlify per il deploy automatico ad ogni push.

## Tecnologie

HTML, CSS e JavaScript vanilla, nessuna dipendenza esterna a parte i font da Google Fonts. Le spunte degli esercizi vengono salvate in `localStorage`.
