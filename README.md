# Devoir à rendre

## Réponses de la partie 1 : "<ins>Questions de cours</ins>"

- _À quoi sert un terminal ?_
<br><ins>Réponse</ins> : Un terminal sert comme point d’accès de l’utilisateur à un ordinateur ou réseau d’ordinateurs, ou à un serveur. Même si une GUI ((Graphique User Interface)) a cette même fonction, pour certaines tâches l’accès via GUI n’est pas disponible ou même cette option GUI n’existe pas du tout. L’accès via terminal peut donc être plus complet, avec une plus grande gamme de possibilités, que celle offerte par une GUI, quand une GUI est disponible. Un autre aspect couvert par un terminal, mais pas par une GUI, est la possibilité d’automatisation de tâches, ce qui se fait à travers de la programmation et qui peut, pour se faire, faire appel à un terminal.

- _Donnez 3 exemples d'éléments de mise en page de fichier README.md et décrivez leur utilité._
<br><ins>Réponse</ins> : Voici 3 exemples d’éléments de mise en page faits avec un markdown et l’effet dans le style du texte affiché qu’en découle :
    1) Les balises astérisque ou étoile simple (\*) placées avant et après la chaîne de caractères cible remettra cette chaîne de caractères en italique. Le underscore (\_) peut être utilisé à la place de l’étoile simple pour produire le même effet. Exemple :
<br>\*cahier\* produira _cahier_
<br>\_cahier\_ produira également _cahier_
    2) Les balises astérisques ou étoiles doubles (\*\*) placées avant et après la chaîne de caractères cible remettra cette chaîne de caractères en gras. Exemple :
<br>\*\*cahier\*\* produira **cahier**
    3) Placer la balise chevron (>) avant une chaîne de caractères remettra cette chaîne dans le style de citation. Visuellement, la citation se voit par une barre verticale grise devant le texte qui apparaît également en gris avec une indentation par rapport au début de page (c'est-à-dire, par rapport à l’alignement des textes sans mise en forme particulière, par exemple sans forme de citation ou de liste). Exemple :
        <br>\> « Faites que le rêve dévore votre vie afin que la vie ne dévore pas votre rêve. »
<br>__(Antoine de Saint-Exupéry, « Le petit prince »)</font>

       produira

> « Faites que le rêve dévore votre vie afin que la vie ne dévore pas votre rêve. »
<br>__(Antoine de Saint-Exupéry, « Le petit prince »)

- _À quoi correspondent les unités suivantes : PX, VW et EM ? Donnez le plus de détails possible._
<br><ins>Réponse</ins> : PX, VW et EM sont des éléments d’un fichier CSS, qui est un fichier de modification de l’apparence des éléments d’une page web. Ces éléments du CSS sont des mesures qui ont une relation avec des modifications concernant la taille ou la longueur des éléments d’une page web. Voici la spécificité de chaque élément :
    1) PX : pixel. C’est une mesure absolue, il s’agit de l’unité « absolue » de tous les éléments d’une page web. Plus précisément, la taille d’un pixel varie pour chaque écran (elle est une mesure relative au DPI - dots per inch/ pixels par pouce et à la résolution de l’écran), mais elle est considérée absolue dans le sens où elle ne varie pas en fonction d’autres éléments ou mesures de taille.
    2) EM : C’est une mesure relative qui indique la taille d’un élément relative à celle d’un élément parent. Cette relation ou proportion entre EM et PX s’observe : 1EM = 16PX.
    3) VW : view width. C’est une mesure relative par rapport à la largeur de l’écran, qui indique une mesure de largeur de la taille de l’écran. Cette relation est observée : 100VW = 100 % de la taille de l’écran dans sa largeur.

- _Trouvez une API et expliquez-moi à quoi sert-elle et donnez-moi le lien de sa documentation (hors API vue en cours : PokeAPI)._
<br><ins>Réponse</ins> : L’API trouvée : API de TMDB (The Movie Database). Cette API est un système qui permet aux personnes intéressées d'accéder et d'utiliser de manière programmatique des données et/ou des images appartenant à TMDB : films, programmes télévisés, images d'acteurs. Les personnes intéressées pourront donc utiliser ces données dans leurs applications.
Voici le lien de sa documentation (version 3 de l’API « The Movie Database (TMDB) »): [https://developers.themoviedb.org/3/getting-started/introduction](https://developers.themoviedb.org/3/getting-started/introduction)

- _Qu'est-ce qu'un "Commit" ?_
<br><ins>Réponse</ins> : « Commit » est une des actions possibles de réaliser dans le logiciel de gestion de version « Git ». Il s’agit de l’action de mettre ou intégrer le code que l’on produit sur Git. Cette intégration de code, souvent accompagné d’un message explicatif facultatif de la part de l’utilisateur, a la caractéristique particulière d’avoir un numéro d’identification (un numéro de commit) que lui est attaché. Cela permet de constituer l’historique du code soumis dans un projet, et d’éventuellement pouvoir revenir à des versions antérieures du code si besoin (par exemple, en cas d’un code erroné dans un commit plus récent).
