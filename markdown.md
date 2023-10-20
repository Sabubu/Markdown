# Markdown

## Titres

- Un dièse # pour le titre pricipal du document
- Deux dièses ## pour les titres des chapitres
- Trois, quatre, cinq, six dièses pour les sous-titres

### Titre Niveau 3

#### Titre Niveau 4

##### Titre Niveau 5

###### Titre Niveau 6

## Mise en forme de texte

- `_italique_` : _italique_
- `**gras**` : **gras**
- `**_gras italique_**` : **_gras italique_**
- `~~barré~~` : ~~barré~~

Une ligne vide permet de créer un nouveau paragraphe.
Le paragraphe reste sur une seule ligne.
Ajouter deux espace `` en fin de ligne pour sauter une ligne  
au milieu d'un paragraphe.

Le symbole > permet d'insérer une citation.

> Markdown est une manière simple de formater du texte qui apparaît correctement sur tous les appareils.

## Listes

### Listes simples

Utiliser le trait d'union (tiret du 6) pour une liste

- Un point
- Un point
- Un point

### Listes numérotées

1. Un
1. Deux
1. Trois

### Cases à cocher

[ ] À faire  
[X] Fait

## Code

Un seul backstick en début et en fin d'expression à mettre en évidence :
`code`.  
Deux backsticks pour afficher un backstick au milieu :
`` C’est tout le `code`. ``

Trois backsticks avec le nom du langage pour mettre du code en forme :

```markdown
# Titre Markdown

**gras** Markdown
```

## Liens

Vers un site web : `[Wikipedia](https://www.wikipedia.org)`
[Wikipedia](https://www.wikipedia.org)

Avec un titre : `[Wikipedia](https://www.wikipedia.org) 'Lien vers Wikipedia'`
[Wikipedia](https://www.wikipedia.org 'Lien vers Wikipedia')

Lien interne : [Haut de page](#markdown) [Titre 6](#titre-niveau-6)

## Images

Pour insérer une image :
`![Texte alternatif décrivant l'image](image.png)`

![Markdown](markdown.png)

<div class="page">

### Notes de bas de page

`[^1] Note 1
beaucoup de texte  
[^1] Réf. 1`

[^1] Note 1 [^2] Note 2
beaucoup de texte  
[^1] Réf. 1
[^2] Réf. 2

### Tableaux

| Titre Col 1 | Titre Col 2 |
| ----------- | ----------- |
| L1 Col 1    | L1 Col 2    |
| L2 Col 1    | L2 Col 2    |

### Autres

Ligne horizontale : `---`

---
