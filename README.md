
# Dynamisez une page web avec des animations CSS




## Documentation

[Site proposant le menu de 4 grands restaurants parisiens : 
 réservation en ligne et composition de menus.
](https://linktodocumentation)


## 🛠 Skills
- HTML

- CSS

- SASS

## Installation (terminal)

1 - Installer SASS (NODE.JS doit être installer au préalable)

```bash
  npm install sass
```
    
2 - Installer sur Visual Studio Code : extention "Live Sass Compiler"

3 - Initialiser fichier :

```bash
  npm package.json
```

puis

```bash
  npm init
```

Taper "entrer" pour accepter

4 - Dans fichier "package.json", Modifier le chemin <script> (adapter selon où se trouve votre fichier "style.css") :

```bash
"scripts": {
 "sass": "sass --watch ./main.scss:.public/css/style.css"
},
```
5 - Lancer sass :

```bash
  npm run sass
```
