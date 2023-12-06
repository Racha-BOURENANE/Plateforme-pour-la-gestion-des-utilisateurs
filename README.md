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
* Postman (pour la gestion des APIs)
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
   
## Guide pour la réalisation des tâches :
### Tâche 1 :
1- sélectionner un thème sous WordPress et le personnaliser comme vous voulez.
2- pour la page contacter-nous :
2.1- Télécharger d'abord l'extension WPForms :
  Extension --> ajouter une extension --> "taper dans la recherche" WPForms --> installer --> activer 
  <table align="center">
  <tr>
    <td> <img src="/images/img1.PNG" /></td> 
    <td> <img src="images/img2.PNG" /> </td>  
  </tr>
  </table>
  <table align="center">
   <tr>
    <td> <img src="/images/img3.PNG" /></td> 
    <td> <img src="images/img4.PNG" /> </td>  
   </tr>
  </table>
- Créer un formulaire personnalisé selon votre choix : 
  WPforms --> ajouter --> sélectionner un formulaire "pour notre cas, j'ai choisi formulaire de contact simple" :
  <table align="center">
   <tr>
     <td> <img src="images/img5.PNG" /> </td> 
     <td> <img src="images/img6.PNG" /> </td>  
   </tr>
  </table>
  <table align="center">
   <tr>
     <td> <img src="images/img7.PNG" /> </td>  
   </tr>
  </table>
- une fois fait, il faut le sauvegarder. Pour vérifier la bonne sauvegarde de ce dernier, on peut aller vers : 
  WPForms --> Tous les formulaires ( il faut trouvver le nom du formulaire existe dans la liste)
  <table align="center">
    <tr>
     <td> <img src="images/img8.PNG" />  </td>   
     <td> <img src="images/img9.PNG" /> </td> 
    </tr>
   </table>
2.2- Ajouter WPForms avec Elementor pour avoir un design plus frais : 
 -pages --> ajouter une page --> taper sur l'icon avec le symbole plus --> taper dans la recherche WPForms 
  <table align="center">
    <tr>
     <td> <img src="images/img10.PNG" />  </td>   
     <td> <img src="images/img11.PNG" /> </td> 
    </tr>
  </table>

  -Sélectionner sur WPForms --> sélectionner le formulaire déja travaillé (ensuite ajouter votre touche et personnalisiez-le comme souhaité avec Elementor ): 
  <table align="center">
    <tr>
     <td> <img src="images/img12.PNG" />  </td>   
     <td> <img src="images/img13.PNG" /> </td> 
    </tr>
  </table>

- Remarque importante : N'oublie pas de le publier a la fin, sinon tu risques d'avoir des erreurs lorsque tu fait un lien vers cette page (=pour accéder d'une page à cette page)
  <table align="center">
    <tr>
     <td> <img src="images/img14.PNG" />  </td>   
    </tr>
  </table>






