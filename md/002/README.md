# <img src="../../logo.svg" height="32"> [HTML CSS JavaScript en français](https://jeanmarclienher.github.io/htmlcssjavascript/)

## Un exemple complet de page HTML dynamique

```
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mon premier site</title>
<link rel="icon" href="../favicon.ico" type="image/x-icon">
<link rel="stylesheet" href="style.css">
<style>
.vert {color: #00FF00;}
.rouge {color: red;}
.fond-gris {background-color: lightgray;}
.centrer {display:block; margin-left: auto; margin-right: auto;}
#cadre {border:1px solid #000000;}
</style>
</head>
<body>
<img src="gilet.svg" style="width:200px;" class="centrer">
<h1>Mon premier site WEB</h1>
<p>
<a href="https://google.ch">Un lien vers google</a>...
</p>
<hr>
<div class="fond-gris" contenteditable="true">
<span class="rouge">Un segment de texte</span> et <span id="elem1" class="vert">un autre</span>...
</div>
<canvas width="100" height="100" id="cadre"></canvas>
<p>
<input type="text" id="inBleu" value="55" size="4">
<button onclick="changerCouleur()" id="but1">Cliquez ici</button>
</p>
</body>
<script>
function changerCouleur() {
  let elem = document.getElementById("elem1");
  let bleu = document.getElementById("inBleu");
  elem.style.color = "rgb(" + ((Math.random() > 0.5) ? 255 : 0) + ",255," + bleu.value + ")";
  document.getElementById("but1").innerHTML = "<strong>Aïe!!</strong>";
}
</script>
<script src="script.js"></script>
</html>
```

[&#x1F578; voir le résultat](../../html/exemple_002.html)

### [&#x2B95; suite du cours &#x2B95;](../003/) 

[&#x1F517; liens utils](../900/)
