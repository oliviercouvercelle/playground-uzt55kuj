# Base CSS

Les exercices ci-après doivent permettre d'utiliser les sélecteurs de base du CSS et de découvrir quelques propriétés courantes.

## Base HTML

Tous les exercices de cette page utilisent le code HTML ci-après comme base.

::: Code HTML

```html
<section>
	<h1>Mon titre 1</h1>
	<article>
		<h2>Mon Titre 2</h2>
		<p>Premier paragraphe</p>
		<p class="maclasse">Deuxième paragraphe</p>
		<p>Troisième paragraphe</p>
		<p id="monid">Quatrième paragraphe</p>
	</article>
	<article>
		<h2 class="maclasse">Mon Titre 3</h2>
		<p id="superid" class="maclasse">Cinquième paragraphe</p>
		<p>Sixième paragraphe</p>
	</article>
</section>
```

:::

## Exercice 1

Pour cet exercice, il faut compléter le code css pour que
- Les articles aient une  [couleur de fond](https://www.w3schools.com/css/css_background.asp) "sylver", une [marge intérieure](https://www.w3schools.com/css/css_padding.asp)  et [extérieure](https://www.w3schools.com/css/css_margin.asp) de 10 pixels. 
- Le tecte des paragraphes aient une couleur [couleur](https://www.w3schools.com/css/css_text.asp) "green" et une [taille](https://www.w3schools.com/css/css_font_size.asp)  de 14px.
- Les titres de niveau 1 aient une [taille](https://www.w3schools.com/css/css_font_size.asp) de 25 pixels.
- Les titres de niveau 2 aient une [taille](https://www.w3schools.com/css/css_font_size.asp) de 20 pixels et une police [police](https://www.w3schools.com/css/css_font.asp) "Helvetica".
- La classe `maclasse` ait une [couleur de fond](https://www.w3schools.com/css/css_background.asp) "grey".
- L'élément d'identifiant `monid` une [bordure](https://www.w3schools.com/css/css_border.asp) "solid" et [couleur de fond](https://www.w3schools.com/css/css_background.asp) "white".

@[Exerice 1]({"stubs": ["css/styleexercice.css"], "command": "/bin/bash run.sh base.html css/styleexercice.css css/exercice.css"})

