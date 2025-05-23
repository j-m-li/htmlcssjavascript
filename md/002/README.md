# <img src="../../logo.svg" height="32"> [HTML CSS JavaScript en français](https://j-m-li.github.io/htmlcssjavascript/)

## Un exemple complet de page HTML pur

**`` <!DOCTYPE html> ``**
Balise [SGML](https://www.w3.org/TR/html4/sgml/dtd.html) qui indique que notre document est de type HTML5.


**`` <html lang="fr"> ``**
Balise racine et indication que la langue du texte est le français.


**`` <head> ``**
Début de l'entête.


**`` <meta charset="utf-8"> ``**
L'encodage du jeu de caractères de ce fichier est Unicode [UTF-8](https://fr.wikipedia.org/wiki/UTF-8).


**`` <meta name="viewport" content="width=device-width, initial-scale=1.0"> ``**
Définition de la vue optimale pour téléphone mobile.


**`` <title>Mon premier site</title> ``**
Titre de la page qui est affiché dans l'onglet du navigateur.


**`` <link rel="icon" href="favicon.ico" type="image/x-icon"> ``**
Icône affiché par le navigateur.


**`` </head> ``**
Fin de l'entête.


**`` <body> ``**
Début du corps du document.


**`` <h1>Ma première page HTML</h1> ``**
Entête de de chapitre la plus grande. Valeurs possible h1 à h7.


**`` <img alt="Mon logo" src="gilet.svg" width="64"> ``**
Affiche une image de 64 pixels de large ou si le navigateur de peut pas la charger, affiche le texte "Mon logo".
A noter que img est une balise vide.


**`` <p> ``**
Début de paragraphe.


**`` <a href="https://home.cern/fr/science/computing/birth-web">Un lien vers le CERN</a>...  ``**
Liens cliquable vers une autre page HTML.


**`` </p> ``**
Fin de paragraphe.


**`` <hr> ``**
Ligne horizontale.
A noter que hr est une balise vide.


**`` <div contenteditable="true"> ``**
Début d'un bloc. Le contenu de ce bloc peut être modifié par l'utilisateur.


**`` <span>Un segment de texte</span> et <span>un autre</span>...  ``**
2 segments de texte. Nous verrons leur utilité en CSS.


**`` </div> ``**
Fin de bloc.


**`` <h2>Un formulaire</h2> ``**
Entête de chapitre secondaire.


**`` <form action="https://lienher.org/jean-marc/echo.php" method="get" target="_blank"> ``**
[Formulaire](https://developer.mozilla.org/fr/docs/Learn/Forms/Your_first_form) qui envoie les données entrées ci-dessous au script PHP de mon site WEB. Un nouvel onglet est ouvert.


**`` <input type="text" name="v1" value="" size="20" placeholder="Entrez du &quot;texte&quot;"> ``**
Champ d'entrée texte pour le formulaire. Notez les entités dans l'attribut placeholer.


**`` <br> ``**
Nouvelle ligne.
A noter que br est une balise vide.


**``&nbsp; <input type="submit" value="&gt;Envoyer&lt;"> ``**
Bouton de type "envoi" précédé de 2 caractères d'espace.

Si nous remplaçons ``&nbsp;`` par un caractère d'espace, le bouton ne sera précédé d'aucun espace.

En HTML les espaces, les tabulations et les retours à la ligne consécutifs [ne comptent que pour un seul espace](https://developer.mozilla.org/fr/docs/Web/CSS/white-space).

Les espaces en début de ligne sont ignorés.


**`` </form> ``**
Fin du formulaire.


**`` <hr> ``**
Ligne horizontale.


**`` </body> ``**
Fin du corps du document.


**`` </html> ``**
Fin du document.

***
```
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mon premier site</title>
<link rel="icon" href="favicon.ico" type="image/x-icon">
</head>
<body>
<h1>Ma première page HTML</h1>
<img alt="Mon logo" src="gilet.svg" width="64">
<p>
<a href="https://home.cern/fr/science/computing/birth-web">Un lien vers le CERN</a>...
</p>
<hr>
<div contenteditable="true">
<span>Un segment de texte</span> et <span>un autre</span>...
</div>
<h2>Un formulaire</h2>
<form action="https://lienher.org/jean-marc/echo.php" method="get" target="_blank">
<input type="text" name="v1" value="" size="20" placeholder="Entrez du &quot;texte&quot;">
<br>
&nbsp; <input type="submit" value="&gt;Envoyer&lt;">
</form>
<hr>
</body>
</html>
```
***

[&#x1F578; voir le résultat](../../html/exemple_002.html)

### [&#x2B95; suite du cours &#x2B95;](../003/) 

***

[&#x1F517; liens utils](../900/) -- Domaine Public MMXXII par Jean-Marc Lienher

