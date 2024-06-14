Notes : 

Installation

Prérequis : 

Un serveur web (apache) avec PHP et Bases de données

Une base de données (BDD) (au choix mais MySQL/MariaDB ça marche)

Un utilisateur BDD avec au moins les droits suivants : 
SELECT, INSERT, UPDATE, DELETE, 
CREATE, DROP, FILE, INDEX, ALTER, 
CREATE TEMPORARY TABLES, CREATE VIEW, 
EVENT, TRIGGER, SHOW VIEW, CREATE ROUTINE, 
ALTER ROUTINE, EXECUTE

Un répertoire pour accueillir les fichiers de drupal, 
situé dans le répertoire qui représente le localhost de votre serveur web.
WAMP dans Disque d'installation de wamp\wamp64\www
Mamp dans Disque d'installation de MAMP:\MAMP puis chercher un répertoire HTDOCS
XAMPP dans Disque d'installation de XAMPP:\xampp\htdocs 

Conseils

Si l'installation est sur un ordinateur local ou un serveur un peu casse pieds (protégé, firewall, etc)
Préférer l'installer en anglais, on met en place la langue ensuite.

Si au contraire le fichiert cacert.pem et le SSH est configuré, 
il est possible de directement installer Drupal en français
(la doc est en lien si l'installation en français plante)

Extensions native a activer
- Media
- Media library
- Configuration Translation
- Interface Translation
- Language

Extensions pratiques recommandées pour commencer

- Admin toolbar
	Activer les modules suivants : 
	- Admin Toolbar
	- Admin Toolbar Extra Tools
	- Admin Toolbar Search
- ctools (chaos tools)
	Activer les modules suivants : 
	- Chaos Tools
	- Chaos Tools Blocks
	- Chaos Tools Views
- token
- pathauto

Changer la langue

1 - 	ajouter la langue
		Accueil > Administration > Configuration > Régionalisation et langue > Langues
2 - 	configurer la langue par défaut
		Accueil > Administration > Configuration > Régionalisation et langue > Ajouter une langue

3 - 	Si la langue ne se charge pas (faible pourcentage de traductions de l'interface)
		Télécharger le fichier adapté en extention .fr.po (pour français par exemple)
		https://localize.drupal.org/translate/languages/fr
	
3.a - 	Accueil > Administration > Configuration > Régionalisation et langue > Traduction de l'interface utilisateur
		Onglet "Importer"
		Importer le fichier pour la langue choisie

