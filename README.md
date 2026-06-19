# Site professionnel - Komivi BADOHOUN

Pour publier ce site sur Vercel ou GitHub Pages, les fichiers suivants doivent être à la racine du projet publié :

```text
index.html
services.html
cv.html
contact.html
vercel.json
assets/
  styles.css
  script.js
  health-data-hero.png
```

Si les textes apparaissent mais pas le design, cela signifie que `assets/styles.css` n'est pas publié ou n'est pas au bon endroit.

Sur Vercel :

- Framework Preset : `Other`
- Build Command : laisser vide
- Output Directory : laisser vide
- Root Directory : choisir le dossier qui contient directement `index.html`

