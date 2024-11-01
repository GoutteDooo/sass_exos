# Tester Sass et comprendre

- Sass est un **préprocesseur CSS**. (lien du site : [SASS](https://sass-lang.com/guide/))
- Il est **nécessaire d'installer Sass** pour s'en servir via npm avec la commande : `npm i -g sass` (on l'installe en **global** comme ça on a pas besoin d'y retoucher à chaque projet)
- Pour faire fonctionner le preprocesseur, on va utiliser la commande `--watch` pour **compiler** (input) le fichier Sass et le **retourner** (output) en CSS.
- Pour l'utiliser, on peut installer un plugin VS Code qui fera le watch à notre place, juste en appuyant sur un **bouton**. Ou sinon, on peut passer par la compilation via le terminal :
  - `sass --watch input.scss output.css` -> avec input.scss qu'on va généralement nommer **index.scss** et output.css en **style.css**.
