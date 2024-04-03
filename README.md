# Contexte

My Moviz est un site qui va vous permettre d’afficher les derniers films sortis avec la possibilité de créer une wishlist, placer un compteur de vues et d’évaluer chacun des films présentés. 
La particularité de cette appli est qu’elle est développée en React !

# Backend

Dynamisation du contenu de l'application grâce à l’API The Movie Database.
Grâce aux hooks d’effet, vous allez pouvoir charger la liste des derniers films suggérés par l’API et les afficher sur votre site web.

# Frontend

Le frontend est développé en React : les composants et le style ont été codées en amont afin de préparer le terrain avant de dynamiser toute l’application avec un webservice et des événements.
Mise en application de la notion de propriétés et dynamisation du style du projet.
Dynamisation de l'application grâce aux états & aux événements en personnalisant les informations sur chaque film : 
  - La ligne d’étoiles bleues correspond à votre vote
  - La caméra est un bouton qui vous permet de mentionner si vous avez vu le film (à chaque clic, le compteur de vue s’incrémente)
  - Le cœur est également un bouton qui renseigne vos films préférés.
Utilisation de la méthode d’inverse data flow pour dynamiser votre liste de films favoris.
Une nouvelle page dédiée à la connexion utilisateur y est intégrée et gérée.
