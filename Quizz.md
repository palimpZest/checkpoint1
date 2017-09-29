## Qu'est ce qu’un navigateur ?

```Un navigateur est un logiciel permettant de se connecter à internet, visualiser des sites web et de faire des requêtes vers des serveurs.

```

________________________________________________________________________________________

## Définissez l’ensemble HTML/CSS/JavaScript et leur utilités.


```HTML, CSS et JavaScript sont des langages informatiques permettant de créer la partie visuelle (front-end) des sites web.
   Le HTML permet de structurer la page et le CSS donne du style à celle-ci. Le javaScript permet d'ajouter des effets interactifs à la pqge.


```
________________________________________________________________________________________


## Qu’est-ce qu’un élément HTML ? Un attribut ?

``` Un élément HTML est une balise permettant de créer de régions définies sur un site web.
    Un attribut est une option permettant de modifier une balise.



```
________________________________________________________________________________________


## Dans quels cas utilisez-vous des id au lieu des classes (et vice-versa) ?


``` Les id se différencient des classes dans la mesure où il ne peut y avoir qu'un id par balise. Alors au'on peut ajoute plusieurs classes par balise.
    Les id peuvent être utilisés comme ancres d'une page. Elles sont utiles afin de lier les effets javaScript aux balises HTML. Les classes servent plutôt à changer le style des balises via le CSS.




```
________________________________________________________________________________________


## Qu’est-ce que EcmaScript ?

```
EcmaScript sont les spécifications dont le javaScript est issu.



```

________________________________________________________________________________________

## Pourquoi est-il important de bien indenter vos fichiers ?

```
    Il est très important d'indenter les fichiers afin de donner une hiérarchie au code et aussi afin d'améliorer la lisibilité.



```
________________________________________________________________________________________


## Quelle est la différence entre margin et padding ?

```

Margin s'utilise pour ajouter de l'espace en dehors d'un div, alors que padding ajoute de l'espace dedans le div.


```

________________________________________________________________________________________


## Citez au moins 3 types de positionnement en CSS et expliquer leurs rôles.

```




```
________________________________________________________________________________________

## Qu’est-ce qu’une variable ?

```

Une variable est une donnée qui peut être ammenée à changer.


```
________________________________________________________________________________________


## Citez le plus de types JavaScript possible et définissez les rapidement.


```

string : chaîne de caractères

number : chiffre

object : objet JS (array, ...)



```
________________________________________________________________________________________


##  À quoi sert le mot-clef “if” ?

```

if permet d'établir une condition.



```

________________________________________________________________________________________

##  Définissez l’objet XHR en JavaScript, son abréviation. À quoi sert-il ?


```




```

________________________________________________________________________________________

## Qu’est-ce qu’une requête HTTP ?

```

Une requête dirigée vers un serveur.


```
________________________________________________________________________________________


## Quelle sont les deux types de requêtes permettant de récupérer et d’envoyer de la donnée sur un serveur HTTP ?

```

récupérer du contenu (GET) ou en poster (POST).


```

________________________________________________________________________________________

## À quoi sert le Header d’une requête ? Le “Content-Type” ?

```

Il permet de configurer plusieurs données lors de l'échange entre le navigateur et le serveur.
On peux par exemple, spécifier la taille et les caractéristiques de cookies. Il permet aussi d'envoyer des informations sur le type d'appareil utilisée ainsi que l'OS.


```
________________________________________________________________________________________


## Donnez au moins 3 codes de réponse HTTP et définissez les.


```

Code 300 : Succès

Code 404 : Problème côté navigateur

Code 500 : Problème côté serveur
```
________________________________________________________________________________________


## Définissez les rôles de Scrum Master et Product Owner.


```

Le Product Owner est le lien (porte-parole) entre le groupe de travail et le client.
Le Scrum Master est en charge de l'application des méthodes SCRUM dans l'équipe.


```
________________________________________________________________________________________


## Citer 4 commandes utilisées avec GIT et expliquer leurs rôles.
```

git push  > pour renvoyer du contenu vers le repository

git pull  > pour recevoir du contenu vers le repository

git add > ajouter les fichiers changés vers la staging area

git status > pour vérifier l'état des fichiers


```
________________________________________________________________________________________


## Expliquer le code suivant et indiquer le résultat retourné par la fonction.

```
function counter(){
        const sentence = "Validation de la première phase";
        const words = sentence.split(' ');
        let count = 0;


        for (let i = 0; i < words.length; i++) {
            var word = words[i];
            count += word.length;
        }
        return count;
}
```
```




```
________________________________________________________________________________________


## Algo

Ecrire l’algorithme d’une fonction prenant en paramètre 2 arguments : le premier est une chaîne de caractère et le second correspondant au caractère recherché. Cette fonction retourne le nombre de fois que le caractère recherché est rencontré dans la chaîne de caractères.
Ex.
   * chaîne : ‘examen’, caractère : ‘x’ => 1
   * chaîne : ‘wild code school’, caractère : ‘w’ => 1



```




```


