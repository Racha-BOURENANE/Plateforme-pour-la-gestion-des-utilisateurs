# Plateforme-pour-la-gestion-des-utilisateurs
## Documentation
- Le cahier de charge : [Le cahier de charge]()
- Le manuel d'utilisation : [Le manuel d'utilisation]()
- La documentation technique : [La documentation Technique]()
- Le fichier Trello : [Trello]()
- Le fichier de plannification du projet Excel : [La plannification du projet]()
- Le projet .zip : [Le projet.zip]()

## Description 
Dans le cadre de la stratégie des entreprises dans le domaine de la transformation numérique, CM Consulting a pour objectif de numériser le secteur et de rendre les informations des clients plus accessibles ainsi que leur gestion plus souple. Afin de réaliser cet objectif, ils m'ont demandé de créer une plateforme pour la gestion des différents utilisateurs.

## Les bénéfices procurés par l'application
* Avoir un lien direct, fort et valable quelles que soient les conditions de travail (confinement total, etc.).
* Réduire la paperasse et les e-mails, et gagner beaucoup de temps.
* Permettre à l’utilisateur de contacter l’administration facilement.
* Permettre à l’administration d’avoir une vision claire sur tous les utilisateurs ainsi que leur gestion.

## Les fonctionnalités de l'application 
Un site web basé sur des API REST qui permet les scénarios suivants :
*	Enregistrer un nouvel utilisateur.
*	Modifier les informations de l’utilisateur.
*	Rechercher des utilisateurs.
*	Afficher le détail d’un compte utilisateur.
*	Ajouter un utilisateur.
*	Connexion et déconnexion à un compte utilisateur.
*	Contacter l'administration.

## Les outils et les environnement de développement
<table align="center">
  <tr>
  	<th>
		Gestion de projet :
	</th>
 	<th>
		Editeur de code :
	</th>
	<th>
		Gestion de code :
	</th>
	<th>
		Backend :
	</th> 
	<th>
		Frontend :
	</th>
  </tr>
  <tr>
  	<td>
		- Trello <br>
		- Word <br>
     		- Excel
	</td>
 	<td>
		- VsCode
	</td>
 	<td>
		- Github 
	</td>
 	<td>
		- Php <br>
    		- Une base de données : MySQL
	</td>
	<td>
 		- HTML <br>
    		- CSS  <br>
       		- JavaScript <br>
	  	- Bootstrap <br>
     		- Adobe Ps
	</td>
  </tr>
</table>
   
## Installation 
Pour installer ce projet depuis GitHub, vous pouvez suivre ces étapes. 


# Plateforme wordpress :
## Respoonsable : Mr KLAIB Abdelkader

## Pourquoi choisir WordPress : 
* Un système de gestion de contenu gratuit et open source.
* Facile à utiliser et à apprendre.
* Pour creér votre propre site WordPress, vous pouvez sélectionner l'un des modèles disponibles et le modifier ou conecevoir directement le vôtre.
* Dispose de milliers de thèmes et d'extenstions gratuites.

## Tâches à réaliser : 
* Tâche 1 : Réaliser un site WordPress simple en utilisant Elementor, avec une page "contacter-nous" en utilisant WPForms + WP Mail SMTP et qui soit multilingue.
* Tâche 2 : Faire un clonage de ce site vers un autre site nommé WordPressTest.
* Tâche 3 : le travail (y'a inclut le projet, le fichier ReadMe.md , la base de donnée, et ainsi tous autres documents utilies) doit etre mis dans notre espace de travail: Azure DevOps "Repos".
* Tâche 4: Réaliser et modifer au fur et à mesure la planification des tâches sous notre espace de travail: Azure DevOps "Board".

## Les outils à installer : 
* Git
* Disposer d'un compte en ligne DevOps.
* PostgreSQL
* XAMPP
* WordPress
* VS code


## Organisation des outils et les environnement de développement
<table align="center">
  <tr>
  	<th>
		Gestion de projet :
	</th>
 	<th>
		Editeur de code :
	</th>
	<th>
		Gestion de code :
	</th>
	<th>
		System de gestion de contenu :
	</th> 
    <th>
		Une base de données :
	</th> 
  </tr>
  <tr>
  	<td>
		- DevOps <br>
		- Word <br>
     	- Excel
	</td>
 	<td>
		- VsCode
	</td>
 	<td>
		- Git <br>
		- DevOps --> Repos
	</td>
 	<td>
		- wordPress
	</td>
	<td>
		- XAMMP + PostgreSQL: MySql
	</td>
  </tr>
</table>
   
## Installation 
Pour installer ce projet depuis GitHub, vous pouvez suivre ces étapes: 
il faut avoir sur votre machine xampp et postgresql.
il faut avoir aussi vs code ( pour une mieux visibilités du code).
il faut avoir aussi Git.
1- la premiere étape consiste a copier le projet et le mettre dans u dossier a htdoces --> qui se trouve sous xampp --> qui se trouve dans le disque c:/
2- la seconde étape consiste a copier la base de données en suivants les étapes suivants : 

3- les étapes de la date 05/12/2023:
3.1- télécharger l'extension WPForms :
  Extension --> ajouter une extension --> "taper dans la recherche" WPForms --> installer --> activer 
  <table align="center">
  <tr>
   <td> <img src="/images/a1.PNG" />  </td> <td> <img src="images/a2.PNG" /> </td>  
  </tr>
  </table>
- créer un formulaire personaliser selon votre choix : 
  WPforms --> ajouter --> sélectionner un formulaire :
  <table align="center">
  <tr>
   <td> <img src="images/a3.PNG" />  </td> <td> <img src="images/a4.PNG" /> </td>  
  </tr>
  </table>
- une fois faits il fautes le sauvegarder et pour vérifier qu"il est sauvegarder il faut aller : 
  WPForms --> Tous les formulaires
    <table align="center">
   <tr>
    <td> <img src="images/a5.PNG" />  </td>   
   </tr>
   </table>
3.2- Ajouter WPForms avec elementor pour le personaliser comme tu veux : 
 pages -- ajouter une page --> "taper sur" le buton plus --> "taper dans la recherche " WPForms 
   <table align="center">
    <tr>
     <td> <img src="images/a6.PNG" />  </td> <td> <img src="images/a7.PNG" /> </td>  
    </tr>
   </table>

- Remarques importantes : n'oublie pas de faire publier a la fin sinon tu vas avoir d'erreur lorsque tu fait un lien vers cette pages (=pour accéder d'une page à cette page)
   <table align="center">
    <tr>
     <td> <img src="images/a8.PNG" />  </td> 
    </tr>
   </table>






