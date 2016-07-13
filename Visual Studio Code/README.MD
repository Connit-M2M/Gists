# Configuration Visual Studio Code

## keybindings.json

Correspond aux raccourcis claviers personnalisés. Les plus pratiques :

* `CTRL+ALT+RIGHT` : focus du curseur sur l'éditeur suivant (vers la droite)
* `CTRL+ALT+LEFT` : focus du curseur sur l'éditeur précédant (vers la gauche)
* `CTRL+SHIFT+W` : ferme l'éditeur courant

## settings.json

Paramètres personnalisés. Utilise la police monospace avec ligatures [Hasklig](https://github.com/i-tu/Hasklig). Pour utiliser une police sans ligatures, penser à passer `editor.fontLigatures` à `false`.

A noter également, l'enregistrement automatique des modifications est activé (`"files.autoSave": "afterDelay"`), ainsi que la suppression automatique des espaces en fin de ligne (`"files.trimTrailingWhitespace": true`).
