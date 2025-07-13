Note de Musique - Projet Ajax (Demande 2)
Présentation
Ce projet est une amélioration du projet de la demande 1, consistant à afficher la correspondance entre les notations musicales classiques (françaises) et américaines.

Cette version intègre une communication asynchrone entre le JavaScript (client) et le PHP (serveur) grâce à AJAX. Elle respecte les principes de JavaScript unobstrusive.

Objectifs pédagogiques
Manipuler le DOM en JavaScript sans HTML inline.

Réaliser des appels AJAX vers un fichier PHP.

Générer dynamiquement un formulaire côté serveur avec une boucle PHP.

Contrôler dynamiquement l’affichage des éléments HTML (formulaire / boutons).

Fonctionnalités
Bouton "Notation" : affiche le formulaire via AJAX.

Bouton "Fermer" : masque le formulaire et réaffiche "Notation".

Formulaire HTML généré dynamiquement via PHP.

Envoi d’une note sélectionnée au serveur.

Le serveur retourne la notation américaine.

Affichage dynamique de la réponse dans la page.

Test de fonctionnement
Ouvrir index.html dans un navigateur.

Cliquer sur Notation.

Sélectionner une note (do, ré, mi...) dans la liste déroulante.

Le message s’affiche dynamiquement sans rechargement de page.

Cliquer sur Fermer pour masquer le formulaire.

Technologies utilisées
HTML5 / CSS3

JavaScript Vanilla (unobstrusive)

PHP (traitement de requêtes et génération HTML)

AJAX via XMLHttpRequest

Concepts clés
JavaScript Unobstrusive : aucun JavaScript inline dans le HTML.

AJAX : chargement et envoi de données au serveur sans rechargement.

Séparation front / back claire : index.html côté client, get_form.php et process_note.php côté serveur.
cf doc-consigne
