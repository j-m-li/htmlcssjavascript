# <img src="../../logo.svg" height="32"> [HTML CSS JavaScript en français](https://j-m-li.github.io/htmlcssjavascript/)

## Ajout des feuilles de style en cascade CSS

***

```
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mon premier site</title>
<link rel="icon" href="favicon.ico" type="image/x-icon">
<link rel="stylesheet" href="style.css">
<style>
* { font-family: "courier"}
h2 {font-family: "arial"; 
    font-style: italic; 
    font-weight:bold; 
    text-decoration: underline;}
div {border:3px solid #00FF80;}
.vert {color: #00FF00;}
.rouge {color: red;}
.fond-rouge {background-color: #FF0000;}
.centrer {display:block; margin-left: auto; margin-right: auto;}
#autre {font-style:italic; text-decoration:underline;}
@media screen and (min-width: 620px) {
    body {margin-right: 20%; margin-left:20%; 
        margin-top: 20px; margin-bottom:5px;}
}
</style>
</head>
<body>
<h1 style="text-align: right;">Ma première page HTML</h1>
<img alt="Mon logo" src="gilet.svg" width="64" class="centrer fond-rouge">
<p>
<a href="https://home.cern/fr/science/computing/birth-web">Un lien vers le CERN</a>...
</p>
<hr>
<div contenteditable="true">
<span class="fond-rouge">Un segment de texte</span> et <span id="autre">un autre</span>...
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


![petit](../../img/small.png)


![grand](../../img/large.png)


[&#x1F578; voir le résultat](../../html/exemple_004.html)

### [&#x2B95; suite du cours &#x2B95;](../005/) 

***

[&#x1F517; liens utils](../900/) -- Domaine Public MMXXII par Jean-Marc Lienher

