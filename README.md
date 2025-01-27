
# Faire sa Première application Web - C#/Django/HTML-CSS-JS

Bonjour à tous,

Aujourd'hui nous allons voir tous ensembles comment faire sa Première application Web. On va utiliser les Framework C#.net, django python, et enfin du language web classique. Dans ce premier workshop nous allons voir comment utiliser le language C# pour créer une Api.
 
Le C# et un language de programmation créer par Microsoft. Il permet gràce à sa facilité d'utilisation de créer une application rapide, simple et tres maintenable sans difficulte surtout grace a son Framework .net qui simplifie grandement son utilisation. Vous coderer uniquement sur Windows. Pour les utilisateurs de Visual Studio Code je vous invite a regarder sur ce liens comment faire "https://code.visualstudio.com/docs/languages/dotnet"

# Partie 1 - Configurer le Framework et l'ordinateur

Pour la Première partie nous vous demanderons de créer un nouveaux projet sur l'application Microsoft Visual Studio 2022 ou sur Visual Studio Code avec l'extension. Vous créer un projet Web Api avec comme Configuration le Framework .net8. Une fois que c'est fait vous le lancer le projet avec le boutons start vert ou la commande "dotnet run"et Swagger se lancera.

# Partie 2 - Swagger

Comme vous avez pue le constater une page Web s'est lancer devant vous du nom de Swagger. Swagger est un langage de description d'interface permettant de décrire des API exprimées à l'aide de JSON. Swagger est utilisé avec toute une série d'outils logiciels open source pour concevoir, créer, documenter et utiliser des services Web. 

Il vous permetteras de voir et tester vos requetes Api ainsi que de voir vos resultat pour la prochaines partie.

# Partie 3 - Les requetes

Maintenant que vous etes sur Swagger vous pouvez voir devant vous une requete forecast Weather qui et une requete de test. Elle et generer automatiquement par votre Api qui est une requetes de test.

Vous allez devoir a votre tour créer les requetes suivantes:

    Exercice 0 : Faire une requête

Objectif : Faire une requete API avec un ou plusieurs paramêtres.

Tache : Faire une requete APi qui prend deux entier en paramêtres et renvoie le resultat.

    Exercice 1 : Faire une requête GET simple

Objectif : Comprendre comment envoyer une requête GET à une API publique et afficher la réponse.

API à utiliser : API JSONPlaceholder pour un faux blog.

Tâche : Récupérer la liste des publications.

Conseils : Utilise HttpClient pour faire la requête et HttpResponseMessage pour recevoir la réponse. Assure-toi d'utiliser async et await.

    Exercice 2 : Traiter des données JSON

Objectif : Apprendre à désérialiser les données JSON en objets C#.

Tâche : Convertir les publications récupérées dans l'exercice 1 en une liste d'objets C#.

Conseils : Utilise JsonConvert.DeserializeObject de la bibliothèque Newtonsoft.Json pour transformer le JSON en objets.

    Exercice 3 : Envoyer des données avec une requête POST

Objectif : Comprendre comment envoyer des données à une API.

API à utiliser : JSONPlaceholder.

Tâche : Créer une nouvelle publication en envoyant des données JSON.

Conseils : Utilise HttpContent et StringContent pour envoyer des données JSON, et définis le MediaType à application/json.
    
    Exercice 4 : Gérer les erreurs et les exceptions

Objectif : Apprendre à gérer les erreurs réseau et les réponses d'erreur de l'API.

Tâche : Ajouter une gestion d'erreurs pour les exercices 1 à 3 pour traiter les cas où l'API ne répond pas comme prévu.

Conseils : Utilise des blocs try-catch pour attraper les exceptions de HttpRequestException et vérifie le StatusCode de HttpResponseMessage.


    Exercice 5: Str_to_word_array en Requètes API

Objectif: Faire Str_to_word_array

Conseils: gerer les erreurs comme l'exos 4 et force a vous.

    Exercice 5 : Assembler une petite application

Objectif : Utiliser les compétences acquises pour construire une petite application console qui interagit avec une API.
API à utiliser : Choix libre, par exemple, une API météo comme OpenWeatherMap.

Tâche : Construire une application qui demande à l'utilisateur de saisir une ville, récupère la météo via l'API et affiche les résultats.

Conseils : Organise le code en fonctions pour chaque type de requête, et utilise des classes pour modéliser les données.
Ces exercices te permettront de pratiquer les appels API en C# de manière incrémentielle, en commençant par les bases et en progressant vers des tâches plus complexes. Bon apprentissage !
