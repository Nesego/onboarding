 Table des matières  



[Titraille](#titraille)  
[Emphases](#emphases)  
[Listes](#listes)  
&nbsp;&nbsp;&nbsp;[Listes ordinnées](#listes-ordinnées)  
&nbsp;&nbsp;&nbsp;[Listes à puces](#listes-à-puces)  
&nbsp;&nbsp;&nbsp;[Checkboxes](#checkboxes)  
[Liens](#liens)  
[Images](#images)  
[Code](#code)  
[Tableaux](#tableaux)  
[Citations](#citations)  
[Règles horizontales](#règles-horizontales)  
[Sauts de ligne](#sauts-de-ligne)  







***



<br />
<br />
<br />



## Titraille



Pour faire des titres, un certain nombre de dièses `#` devant le titre puis un `ESPACE` indiquent son niveau de titre :

```

# Titre 1
## Titre 2 (à privilégier pour les intertitres)
### Titre 3
#### Titre 4
##### Titre 5
###### Titre 6

```

Voici le résultat :

# Titre 1
## Titre 2 (à privilégier pour les intertitres)
### Titre 3
#### Titre 4
##### Titre 5
###### Titre 6




<br />
<br />
<br />





## Emphases



```
Pour l'*italique* on utilise un *astérisque* avant et un après. 
Pour le gras, ce sont deux **astérisques**.
On peut combiner **gras et *italique***.
Pour barrer, on fait ~~deux tildes~~.
Hé oui, on ne peut pas souligner en markdown.
```



Pour l'*italique* on utilise un *astérisque* avant et un après.<br />
Pour le gras, ce sont deux **astérisques**.<br />
On peut combiner **gras et *italique***.<br />
Pour barrer, on fait ~~deux tildes~~.<br />
Hé oui, on ne peut pas souligner en markdown.<br />



<br />

```
ASTUCE
On peut aussi utiliser suivant le même principe un underscore ( _ ) pour l'italique
ou deux ( __ ) pour le gras si ça peut vous permettre d'y voir plus clair
quand vous voulez mélanger les deux.
```
<br />

```
Voici pour **l'exemple une phrase qui _combine du 
gras et de l'italique_ mais en utilisant deux 
méthodes différentes**. Ici la première...

...Et ici la seconde. Voici pour __l'exemple une 
phrase qui *combine du gras et de l'italique* mais 
en utilisant deux méthodes différentes__.
```


Ce qui donne :



Voici pour **l'exemple une phrase qui _combine du <br />
gras et de l'italique_ mais en utilisant deux <br />
méthodes différentes**. Ici la première...<br />


...Et ici la seconde. Voici pour __l'exemple une <br />
phrase qui *combine du gras et de l'italique* mais <br />
en utilisant deux méthodes différentes__.<br />


Le résultat est identique, cherchez pas. Remarquez qu'un retour à la ligne n'affecte par le résultat.




<br />
<br />
<br />



## Listes



### Listes ordinnées



```
1. Ecrivez 1. puis faites un RETOUR CHARIOT
2. Pour une sous-liste, faites RETOUR CHARIOT puis TABULATION 
	a. Sous-liste ordonnée puis RETOUR CHARIOT
	b. Sous-liste ordonnée b.

DEUX RETOURS CHARRIOTS et c'est la fin des haricots
```

Voilà le résultat :



1. Ecrivez `1.` puis faites un `RETOUR CHARIOT`
2. Pour une sous-liste, faites `RETOUR CHARIOT` puis `TABULATION` <br />
	a. Sous-liste ordonnée puis `RETOUR CHARIOT` <br />
	b. Sous-liste ordonnée b.

`DEUX RETOURS CHARIOT` et c'est la fin des haricots


<br />



### Listes à puces



```
* Une liste non ordonnée peut utiliser des astérisques
- Ou des moins (autrement appelés "le tiret du 6")
+ Ou des plus
```



* Une liste non ordonnée peut utiliser des astérisques
- Ou des traits d'union (autrement appelés "le tiret du 6")
+ Ou des plus

<br />

### Checkboxes



```
[] On peut aussi faire des cases à cocher avec deux crochets
[x] Ou déjà cochées avec un x au milieu
```

Ca ne marche pas trop sur Github alors on ne peut pas vous montrer le résultats. C'est comme ça !





<br />
<br />
<br />




## Liens



Il y a trois façons de créer des liens.



```
1. Mettre le texte à lier entre crochets puis l'url entre parenthèses à la suite sans espace : 
   Je suis [un lien en ligne](https://www.google.com) dans le texte.
2. Coller directement une URL complète : http://www.example.com
3. Faire un "lien de référence", comme une note de bas de page :
   [Ce lien fait référence à un chiffre][1]
   Que l'on peut mettre touuuut en bas de page si on veut et qui est invisible.

[1]: https://anotherexample.com
```




Résultat :


1. Mettre le texte à lier entre crochets puis l'url entre parenthèses à la suite sans espace : 
   Je suis [un lien en ligne](https://www.google.com) dans le texte.
2. Coller directement une URL complète : http://www.example.com
3. Faire un "lien de référence", comme une note de bas de page :
   [Ce lien fait référence à un chiffre][1]
   Que l'on peut mettre touuuut en bas de page si on veut et qui est invisible.

[1]: https://anotherexample.com


<br />
<br />
<br />


## Images



Une image, en fait, c'est juste un lien avec un `!` devant. Le texte entre crochets est obligatoire, et on peut rajouter une légende entre guillemets après l'URL dans la parenthèse, elle apparaît au survol de la souris : `![texte d'accessibilité pour malvoyants](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Titre facultatif")`



Résultat :



![texte d'accessibilité pour malvoyants](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Titre facultatif")



Pour les images "internes", c'est à dire les médias de la fiche : 

<img src="https://dl.airtable.com/.attachmentThumbnails/xxxxxx" class="img-fluid" alt="Caractéristiques du robot" />



"alt" = texte alternatif à remplacer par une description de l'image

remplacer le lien après src ="xxx" par l’adresse à remplacer par l’image qu’on veut insérer. Comment on la trouve ?

Il faut que l’image soit enregistrée dans les médias de la fiche. Si elle l’est, alors on clique dessus, ça ouvre la fiche “médias”, on clique sur l’image qui est dans la pièce jointe, ça affiche l’image, et là clic droit, “informations sur l’image”, et on copie/colle le lien qui commence par “https://dl.airtable.com/.attachmentThumbnails/xxxxxxxxx”


<br />
<br />
<br />


## Code



C'est en fait ce qu'on fait de puis le début, il suffit de mettre trois accents graves ` ``` ` à la suite au début du code, puis trois accents après pour refermer.

Il y a aussi le code dans un ligne pour `un bout de phrase` avec un seul accent grave ` de part et d'autre.

```
C'est en fait ce qu'on fait de puis le début,
il suffit de mettre trois accents graves ``` à la
suite au début du code, puis trois accents après
pour refermer.

Il y a aussi le code dans un ligne pour `un bout de phrase`
avec un seul accent grave ` de part et d'autre.
```


<br />
<br />
<br />


## Tableaux



Un tableau commence par une barre droite `|` . La barre est *facultative à la fin d'une ligne*, mais il en faut une entre chaque cellule.


**La première ligne** correspond aux titres
**La deuxième ligne** détermine la largeur des colonnes avec des tirets `---`  , il en faut au moins trois. <br />
__Les deux-points__ `:` peuvent être utilisés pour justifier le texte dans les colonnes.
**Toutes les lignes suivantes** contiennent les données des cellules



```
| Un Tableau | C'est juste | des colonnes |
| ------------- |:-------------:| -----:|
| colonne 3 est | aligné à droite | $1600 |
| colonne 2 est | centrée | 12
| Les rayures zébrées | sont nettes | 1 $ |
```

Ca donne :



| Un Tableau | C'est juste | des colonnes |
| ------------- |:-------------:| -----:|
| colonne 3 est | aligné à droite | $1600 |
| colonne 2 est | centrée | 12
| Les rayures zébrées | sont nettes | 1 $ |





<br />
<br />
<br />



## Citations



```
> Les citations en bloc sont très pratiques pour faire de jolies exergues de gens qui racontent des trucs très sérieux
> Cette ligne fait partie de la même citation.
> Chaque retour à la ligne doit commencer par un signe supérieur >

Cette ligne est en dehors de la citation

> *« Devinez quoi ? On peut même combiner tout ça avec de l'italique
> et du **gras pour faire une exergue dans l'exergue**
> et [avec un lien](https://gogle.com) s'il vous plaît ! »*. 
```


> Les citations en bloc sont très pratiques pour faire de jolies exergues de gens qui racontent des trucs très sérieux
> Cette ligne fait partie de la même citation.
> Chaque retour à la ligne doit commencer par un signe supérieur `>`

Cette ligne est en dehors de la citation

> *« Devinez quoi ? On peut même combiner tout ça avec de l'italique
> et du **gras pour faire une exergue dans l'exergue**
> et [avec un lien](https://gogle.com) s'il vous plaît ! »*. 

<br />
<br />
<br />


## Règles horizontales



```
Trois underscores font une règle (autrement appelés tirets du 8)...
___

OU trois traits d'union
---

OU trois astérisques
***
```





Trois underscore font une règle (autrement appelés tirets du 8)...

___



OU trois traits d'union



---



OU trois astérisques

***

<br />
<br />
<br />

## Sauts de ligne



Pour apprendre comment fonctionnent les sauts de ligne, le plus simple est d'expérimenter et de découvrir -- appuyez sur Entrer une fois (c'est-à-dire insérez une nouvelle ligne), puis appuyez deux fois (c'est-à-dire insérez deux nouvelles lignes), pour voir ce qui se passe. Vous apprendrez vite à obtenir ce que vous voulez. 



```
Voici une ligne pour commencer.


Cette ligne est séparée de celle ci-dessus par deux nouvelles lignes, il s'agira donc d'un *paragraphe séparé*.



Cette ligne est également un paragraphe séparé, mais...

Cette ligne n'est séparée que par une seule nouvelle ligne, donc c'est une ligne séparée dans le *même paragraphe*.

```



Voici une ligne pour commencer.


Cette ligne est séparée de celle ci-dessus par deux nouvelles lignes, il s'agira donc d'un *paragraphe séparé*.



Cette ligne est également un paragraphe séparé, mais...

Cette ligne n'est séparée que par une seule nouvelle ligne, donc c'est une ligne séparée dans le *même paragraphe*.

<br />
Pour des sauts de ligne multiples, il vous faudra utiliser la balise HTML br autofermée plusieurs fois à la suite :

<br />
<br />
<br />

***
