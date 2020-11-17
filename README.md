# ajax-exo

Afficher la liste de tous les "Posts" au chargement de la page à partir de l'API: 
GET : https://jsonplaceholder.typicode.com/posts

Afficher un "Post" au click (bouton afficher) à partir de l'API: 
GET : https://jsonplaceholder.typicode.com/posts/{postId}

Supprimer un "Post" au click (bouton supprimer) à partir de l'API:
DELETE : https://jsonplaceholder.typicode.com/posts/{postId}

Ajouter un "Post" à l'aide de formulaire rendu visible au click (bouton ajouter) à partir de l'API:
POST : https://jsonplaceholder.typicode.com/posts
{
    title: 'Le titre',
    body: 'Le text',
    userId: 1,
}
