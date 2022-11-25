## Projet réalisé dans le cadre de 2e année de BUT informatique

Le contexte : NetVOD, une application de vidéo à la demande
On souhaite développer une application de diffusion de vidéos à la demande. L'application propose un catalogue de vidéos disponibles pour visionnage par les utilisateurs inscrits sur la plateforme. Le catalogue comporte des films, des séries et des films documentaires. Tous ces éléments sont classés par genre (action, thriller, anime ...), par type de public (enfants, jeunes, famille, adultes ...). Bien entendu, les séries son composées d'épisodes regroupés par saisons.
Un utilisateur inscrit possède un profil qui contient notamment des coordonnées et ses informations de paiement. Un utilisateur inscrit peut créer plusieurs comptes nommés (au plus 4).
Chaque compte nommé associé à un utilisateur possède plusieurs listes :
 une liste de vidéos préférées,
 une liste de vidéos déjà visionnés,
 une liste de vidéos en cours : films ou docus non visionnés en intégralité, séries non
complétées.
Un compte peut commenter et donner un avis sur une vidéo après visionnage.

##L’objectif est de développer une version réduite de l’application complète, en se restreignant à une sous-partie des fonctionnalités destinées aux utilisateurs finaux de la plateforme NetVOD (voir tableau ci-dessous).

# NetVod est une application web fonctionnelle développée en appliquant les principes abordés dans notre cours de Développement web,
# Utilisation d'un framework css pour l'interface
### Réalisé par ARNAUD Elian, BRESSON Jules, CARLIER Maxime, PELLIZZARI Théo et RENARD Tanguy

## Fonctionnalités de base :
| Fonctionnalité                                                                                                | Auteur        | Statut   |
|---------------------------------------------------------------------------------------------------------------|---------------|----------|
| 1. Identification/Authentification – Formulaire de login                                                      | Théo          | ok       |
| 2. Inscription sur la plateforme                                                                              | Elian         | ok       |
| 3. Affichage du catalogue de séries                                                                           | Maxime,Theo   | ok       |
| 4. Affichage détaillé d’une série et de la liste de ses épisodes                                              | Maxime,Theo   | ok       |
| 5. Affichage/visionnage d’un épisode d’une série                                                              | Maxime        | ok       |
| 6. Ajout d’une série dans la liste de préférence d’un utilisateur                                             | Théo          | ok       |
| 7. Page d’accueil d’un utilisateur : afficher ses séries préférées                                            | Elian         | ok       |
| 8. Lors du visionnage d’un épisode, ajouter automatiquement la série à la liste « en cours » de l’utilisateur | Maxime        | ok       |
| 9. Lors du visionnage d’un épisode d’une série, noter et commenter la série                                   | Jules, Maxime | ok       |
| 10. Lors de l’affichage d’une série, indiquer sa note moyenne et donner accès aux commentaires                | Tanguy, Jules | En cours |

## Fonctionnalités étendues :
| Fonctionnalité                                                                                               | Auteur       | Statut   |
|--------------------------------------------------------------------------------------------------------------|--------------|----------|
| 11. Activation de compte                                                                                     | ?            | Non      |
| 17. gestion du profil de l’utilisateur : ajouter des informations (nom, prénom, genre préféré ...)           | Tanguy       | ok       |
| 12. Recherche dans le catalogue par mots clés                                                                | Théo         | ok       |
| 13. Tri dans le catalogue                                                                                    | Théo         | En Cours |
| 14. filtrage du catalogue par genre, par public                                                              | ?            | Non      |
| 15. gestion de la liste de préférence : retrait                                                              | Jules        | ok       |
| 16. Gestion de la liste « déjà visionnées »                                                                  | ?            | Non      |
| 18. accès direct à l’épisode à visionner lorsque l’on visualise une série qui est dans la liste « en cours » | ?            | Non      |
| 19. Tri dans le catalogue selon la note moyenne                                                              | ?            | Non      |
| 20. mot de passe oublié                                                                                      | ?            | Non      |
