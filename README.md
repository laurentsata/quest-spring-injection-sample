# quest-spring-injection-sample
Prend le temps de parcourir toutes les classes : tu verras que les Repository ont aussi une injection de dépendances des instances de ArticleReview et VideoReview (qui ont maintenant l'annotation @Component).

Tu peux tester sur le lien http://localhost:8080/review : pense à renseigner dans l’url un paramètre "game", avec le nom d’un jeu à tester.

Ensuite, modifie la valeur du qualifier contenu dans NewsroomController afin de réaliser des tests au format vidéo, puis relance le serveur afin de tester les changements.
