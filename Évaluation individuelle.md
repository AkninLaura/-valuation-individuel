# Évaluation individuelle

## Programmation - Coaching

```
Nom : Aknin
Prénom : Laura
URL de votre compte Github : https://github.com/AkninLaura
```

## Déroulé et fonctionnement. 

L'évaluation est à faire sur [Typora](https://typora.io/). Les réponses sont à écrire dans les blocks de code. 
Pour la partie Ruby, testez votre code sur [repl.it](https://repl.it/) et copiez le dans les blocks de code prévu à cet effet. 
Une fois fini, pushez votre feuille sur Github, dans un nouveau repository que vous appelerez "evaluation-inseec".
L'évaluation est individuelle et durera 1h30. Elle intègre des notions d'HTML, CSS, Ruby et computer science. 

![alt](https://media.giphy.com/media/26xBBfd0ii1khakpy/giphy.gif)

## Quelques mises en garde.

Je connais très bien ce merveilleux site qu'est Wikipédia. Je vous saurais gré de ne pas me remplir certaines questions avec les définitions de Wikipédia. Accessoirement, je sais aussi faire une recherche Google. Si j'ai un doute, je n'hésiterais pas rechercher "Qu'est-ce qu'une API" et comparer les définitions en tête de recherche avec les votre. Si je trouve une similarité trop grande et que je doute de votre bonne foi, je n'hésiterais pas à mettre 0 à la question. 
Pareil pour la copie sur les voisins. Si c'est trop gros et que j'ai un doute trop prononcé... 🔫

![alt](https://media.giphy.com/media/BtedgmzGNCiuk/giphy.gif)



------

### 1. Avec vos mots, expliquez l'interaction client-serveur

```t
Un client est un programme qui envoi un requête, une demande de service et qui obtient une réponse grâce au serveur, qui va donc donner le service demander.
```



 ### 2. HTML est un langage côté... 	

```
client
```



### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<!-- Completez après cette ligne -->
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

  <title>Titre</title>    
      <link href="stylesheet1.css" rel="stylesheet" type="text/css">
      
  </head>
  <body>

    </body>
</html>
```



### 4. Changez la couleur du texte "J'adore la programmation" en vert en utilisant du CSS.

```html
<div class="titre">
   <p>J'adore la programmation</p>
</div>
```

```css
/* Ecrire le code CSS sous cette ligne */
.titre {
    color:green;
}
```



### 5. Qu'est-ce que Bootstrap ?

```
C'est une structure de code qui permet d'utiliser HTML, CSS et aussi JavaScript, c'est se qu'on appel un Framework. Bootstrap permet notammment d'avoir les outils pour créer des sites internet, de les remplir, les animées, et les designer. 
```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.2.1/css/bootstrap.min.css" integrity="sha384-GJzZqFGwb1QTTN6wy59ffF1BuGJpLSa9DkKMp0DgiMDm4iYMj70gZWKYbI706tWS" crossorigin="anonymous">

    <title>Titre</title>
  </head>
  <body>
    <h1>Bonjour</h1>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.6/umd/popper.min.js" integrity="sha384-wHAiFfRlMFy6i5SRaxvfOCifBUQy1xHdJ/yoi7FRNXMRBu5WHdZYu1hA6ZOblgut" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.2.1/js/bootstrap.min.js" integrity="sha384-B0UglyR+jN6CkvvICOB2joaf5I4l3gm9GU6Hc1og6Ls7i6U/mkkaduKaBhlAXv9k" crossorigin="anonymous"></script>
  </body>
</html>
```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
   
   <div class=container>
    <div class="row">
        <div class="col-sm">
<div>
   <h2>Google</h2> 
</div>

        <div class="col-sm">
<div>
   <h2>Microsoft</h2> 
</div>

        <div class="col-sm">
<div>
   <h2>Apple</h2> 
</div>
        </div></div></div></div></div>div>
    Google
</div>

<div>
    Microsoft
</div>

<div>
    Apple
</div>
```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
  
<p><img src="https://www.google.fr/search?q=google+logo&source=lnms&tbm=isch&sa=X&ved=0ahUKEwjRuvHlktTfAhXOyIUKHUw4Bl0Q_AUIDigB&biw=1280&bih=567#imgrc=cmeT6Gl5pAMt9M:" alt="Google" style="float:right;width:42px;height:42px;">
Google</p>

<p><img src="https://www.google.fr/search?tbm=isch&sa=1&ei=clQvXN7nH4WsadC8kvgK&q=microsoft+logo&oq=micros+logo&gs_l=img.3.1.0i19j0i7i30i19l9.13534.14760..15753...0.0..0.164.807.0j6......1....1..gws-wiz-img.......0j0i7i30.LN1WOXMphZA#imgrc=nv2j_Q06nnSvTM:" alt="Microsoft" style="float:right;width:42px;height:42px;">
Microsoft</p>

<p><img src="https://www.google.fr/search?q=apple+logo&tbm=isch&source=iu&ictx=1&fir=InpoHbAht1lMHM%253A%252CO0qzUhntNeOlFM%252C_&usg=AI4_-kTQgpLG2duAzccP3q_Bq9ajynXmzQ&sa=X&ved=2ahUKEwjksJ6Rk9TfAhVNdhoKHaPlD64Q9QEwAHoECAQQBA#imgrc=InpoHbAht1lMHM:" alt="Apple" style="float:right;width:42px;height:42px;">
Apple</p>
```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html

<div>
    Google
</div>

<div>
    Microsoft
</div>

<div>
    Apple
</div>
```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
serveur
```



### 11. Listez-moi tous les types de données que vous connaissez en donnant le nom et la syntaxe.

```
 # Ceci est un 
string = chaine de caractère 
hash = une clé et valeur
boolean = true or false
float = un décimaux
integer = un chiffre entier positif ou négatif 
```





### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
first_name="Aknin"
puts first_name
last_name="Laura"
puts last_name
my_account= "https://github.com/AkninLaura"
puts my_account

```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby
a = 674
puts a
b = 311
puts b
c = a % b
puts c 
# Le résultat attendu est 52. 
```



### 14. Qu'est-ce qu'une gem ? 

```texte
Les gem sont des librairies qu’on rajoute à ruby.

```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
Un API est un interface de programmation qui s’oppose aux interfaces graphiques.

Tout les sites on une API et il y en a qui decider de les mettres publiques ou privées.Pour avoir une interface pour utiliser Ruby on utilise un gem qui va s'occuper de recréer les méthodes d’API et faire une couche sur Ruby.

```



### 16. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
# <- Demander le prénom de l'utilisateur

hour = 15

# Si hour est inférieur à 12
	# j'écris mon code permettant de dire Bonjour prénom

# sinon
	# j'écris mon code permettant de dire Bonsoir prénom


 def Bonjour Anthony
bonjour_if_hour_before_12
 assert_equal("Bonjour", message_bienvenue)
end
 
def Bonsoir Anthony
bonsoir_if_hour_after_12
 assert_equal("Bonsoir", message_bienvenue)
end

```



### 17. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
handles = ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]


```



### 18. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

