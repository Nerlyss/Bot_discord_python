# Bot_discord_python

### Fonctionnalitées bot 

## Commande basique

- !hello = salut le joueur en retour
- on_member_join = affiche dans un channel donné l'arrivé d'un nouveau membre
- !del chiffre = efface le nombre de ligne indiquer
- !helpi = pour voir les commandes et leur descriptif (ne fonctionne pas)



## Sondage

- !sondage "question" | "option1" | "option2" | ... | "optionN"
- Vous pouvez fournir entre 2 options et au maximum 10 options.
- Le bot enverra un message contenant la question du sondage et les options numérotées.
- Les utilisateurs pourront réagir en utilisant les émojis numérotés (1️⃣, 2️⃣, 3️⃣, etc.) pour exprimer leur choix.
- Les réactions des utilisateurs seront enregistrées et comptabilisées.


## Rappel

- !rappel temps motif (exemple : !rappel 30 Rendez vous)
- Le bot attendra le nombre de secondes spécifié dans le premier argument.
- Après le délai, le bot enverra un message privé à l'utilisateur contenant le message spécifié dans le deuxième argument.

## Pierre-feuille-ciseaux

- !pfc pierre
- Fournissez un argument pour choisir votre coup : 'pierre', 'feuille' ou 'ciseaux'.
- Le bot choisira également un coup au hasard parmi les options.
- Le bot comparera les coups et affichera le résultat.

## Gif

- !chat
- Le bot enverra un gif dans le tchat.

## Blague

- !blague
- Le bot choisira une blague aléatoire parmi la liste prédéfinie et l'affichera dans le canal où la commande a été utilisée.
- Après avoir utilisé toutes les blagues de la liste, la liste sera réinitialisée pour recommencer.


## Recherche Google (ne fonctionne pas)

- !google requête
- Ajoutez votre requête de recherche après la commande google. Par exemple, si vous voulez rechercher "chat mignon", vous pouvez utiliser la commande !google chat mignon.
- Le bot effectuera la recherche sur Google en utilisant l'API Google Search.
- Les 5 premiers résultats de la recherche seront renvoyés sous forme de texte dans le canal où la commande a été utilisée.

## Historique général 

- Utilisez la commande !full_history
Le bot récupérera toutes les commandes enregistrées dans l'historique.
Les commandes seront renvoyées sous forme de texte dans le canal où la commande a été utilisée.

- Utilisez la commande !last_command
Le bot récupérera la dernière commande enregistrée dans l'historique.
La dernière commande sera renvoyée sous forme de texte dans le canal où la commande a été utilisée.

- Utilisez la commande !clear_command
L'historique des commandes sera effacé.
Aucune confirmation ne sera renvoyée.

## Historique personnel hashmap

Historique à partir du hashmap permettant de lié des données à un user id. Sauvegarder et récupérer dans un fichier Json.
- !historique 
Le bot vérifiera s'il existe un historique des commandes pour l'utilisateur.
Si aucun historique n'est trouvé, le bot enverra un message indiquant que vous n'avez pas encore utilisé de commande.
Si un historique est trouvé, le bot générera un message contenant la liste des commandes utilisées.
Le message sera renvoyé dans le canal où la commande a été utilisée.

## Tree

Permet une discussion avec le bot.

- Utilisez la commande !discussion pour commencer une nouvelle discussion. Le bot réinitialisera la discussion et vous enverra une réponse initiale.
- Utilisez la commande !answer suivie de votre réponse pour répondre à la dernière question ou demande du bot. Le bot traitera votre réponse et vous enverra une nouvelle question ou demande.
- Utilisez la commande !reset pour réinitialiser la discussion et recommencer depuis le début. Le bot vous enverra un message indiquant que la discussion a été réinitialisée.
- Utilisez la commande !speak_about suivie d'un sujet pour demander au bot de parler de ce sujet spécifique. Le bot générera une réponse en fonction du sujet donné.

