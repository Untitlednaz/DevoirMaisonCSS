	1.	Mise en Page avec Bootstrap (Grid Layout)
La structure principale est réalisée à l’aide du Grid Layout de Bootstrap. Le contenu principal est géré par un layout à deux colonnes :
	•	Colonne principale : Gérée par la classe col-md-8, elle contient les informations principales de la page, telles que le tableau de bord, les cartes, etc.
	•	Colonne latérale (Aside) : Gérée par col-md-4, elle contient des informations complémentaires comme les astuces et les actualités.
Ce choix assure une mise en page bien équilibrée avec des largeurs régulières, tout en restant responsive.
	2.	Menus surgissants (CSS pur)
Les menus de navigation sont créés avec des sous-menus qui apparaissent lors du survol. Cette fonctionnalité est entièrement gérée en CSS avec les propriétés hover et des listes imbriquées. Cela assure une navigation fluide sans nécessiter de JavaScript, tout en alignant les sous-menus sur les colonnes principales de la page.
	3.	Balises sémantiques
	•	Les balises <article>, <aside>, <section> sont utilisées pour structurer correctement le contenu, facilitant ainsi l’accessibilité et la lisibilité par les moteurs de recherche.
	•	Les balises sémantiques améliorent également l’organisation du contenu pour les lecteurs d’écran.
	4.	Pagination avec Bootstrap
Une pagination Bootstrap est placée en bas du contenu principal, permettant la navigation entre plusieurs pages. Elle est stylisée à l’aide des classes pagination et page-item de Bootstrap.
	5.	Responsivité
Grâce à Bootstrap, la page est entièrement responsive. Les classes Bootstrap telles que container, row, et col-* ajustent les colonnes et les composants en fonction de la taille de l’écran, garantissant une expérience fluide sur mobile, tablette et ordinateur.
	6.	Justification des choix techniques
Le choix de Bootstrap permet une gestion simplifiée et flexible de la mise en page et de la responsivité. Le CSS pur utilisé pour les menus respecte les bonnes pratiques et optimise la performance en minimisant les scripts supplémentaires.
