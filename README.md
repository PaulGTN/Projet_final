# Je Passe Au Vert

Plate-forme de partage/d'échange de conseils et de bonnes adresses pour améliorer son impact environnemental et sa manière de consommer.

<img src="https://images.pexels.com/photos/106150/dewdrop-morning-sun-mirror-blade-of-grass-106150.jpeg?auto=compress&cs=tinysrgb&h=750&w=1260>

### Objectifs :

**Quoi**
- [ ] Créer une plate-forme simple pour partager, rechercher tout types de conseils

**Pour qui**
- Tous types d'utilisateurs cherchant à réduire facilement son impact personnel sur l'environnement

**Pourquoi**
- [ ] Déjà ce n'est pas une idée originale (c'est mon 4e essai et impossible de trouver quelque chose qui n'a pas encore été fait, foutu internet)
- [ ] Ensuite face au mode de consommation actuelle, arrosé par le plastique et autres produits étranges, il semble bien difficile de pouvoir réduire son impact sur l'environnement. Toutefois il existe des millions d'astuces trouvables sur internet sur ce sujet. Alors pourquoi faire un enième site me direz-vous ? Et bien parce que 90% (chiffre complètement inventé mais qui me semble pas loin de la réalité) de ces astuces se trouvent dispatché sur des tonnes de site, souvent en mode top 10 sur un blog fixe. Vous cherchez une astuce en particulier ? Préparez vous é devoir vous baladez sur des dizaines de pages et de sites différents pour trouver la bonne ? Vous avec une problématique sur un sujet précis ? Priez pour que le site posséde un espace avec des commentaires et quelqu'un viennent vous répondre dans un délai raisonnable. 

### Ici rien de tout ça :

- créer un profil, puis recherchez, partagez vos astuces simplement (ex: "Fabriquer du shaampoing bio", "Comment créer un potager dans un appartement")
- un problémez, une question ? rendez-vous dans l'espace forum pour voir si quelqu'un a une solution é proposer (ex: "Je voudrais faire une lessive maison mais mon enfant est allergique é tel produits, connaissez-vous une alternative ?", "J'ai pas franchement envie de passer aux céréales en vrac dans un sac en tissu pour le petit-déjeuner sans avoir é faire mes viennoiseries tout les matins, quelqu'un connaét une marque plutét clean et sans emballages ?")

Bref vous voyez le topo. L'idée est de tout centraliser sur un site (beau gosse de préférence), dans un concept proche de Pinterest,  pour ne pas avoir é se taper des recherches googles interminables ou de tomber sur un blog dégueulasse d'un dame habitant é Mécon, certes trés gentille  mais pas trés doué en programmation.

**Les bases**

Le site est auto-nourri par sa communauté. Donc pas de scrapping, les données étant tellement dispersées qu'il paraét impossible de faire cela dans un délai convenable. 
Il est divisé quatre grandes parties, les astuces, le forum, les adresses et le profil.

**Les pages**
- un accueil simple permettant d'accéder aux différentes fonctionnalités et de s'inscrire ou se connecter.  Un carousel présentant les meilleurs astuces du mois (par exemple) serait le bienvenue
- des formulaires de connexion, inscription, demande de password, etc (via Devise)
- un index des astuces accesible par tous mais nécessitant une inscription pour aller plus loin (faut bien se vendre un peu), sur un systéme simple de carte avec un moteur de recherche
- un index du forum, accessible é tous mais nécessitant une inscription pour pouvoir poster,
avec une belle liste de carte encore un moteur de recherche
- un show de chaque astuce avec une possibilité de les sauvegarder dans ses favoris/ question du forum oé l'on peut commenter/adresse avec une map
- un create/edit pour chacun de ces objets
- une page profil qui comprend ses informations personnelles et la possibilité de les modifier, ses astuces/questions/réponses postées (pas les commentaires sur les astuces), ses astuces/auteurs sauvegardés

**Les fonctionnalités**
- possibilité d'inscription via Facebook pour partage facilement ses trouvailles avec ses amis
(via API Facebook)
- géolocalisation sur une map des bonnes adresses postées dans leur show individuel (via API Google maps)
- sauvergarde une astuce dans son profil
- s'abonner é un utilisateur 
- un mailer, avec possibilité de newsletter, confirmation d'inscription, renouvellement password, et envoi automatique dés qu'un auteur suivi poste un nouvel article

**Le visuel**
Ce qui est bien avec l'écologie c'est la charte graphique est facile. Tu regarde une forét tu as trouvé le truc. 

Ca partirait sur :
- les couleurs : un vert péle, un bleu pastel, un marron pastel et des nuance de blanc et de gris. Quelque chose de clair dans tous les cas.
- les polices : légéres, fines, sérements légérement courbées, deux seulement (peut-étre trois dont une spécialement pour le footer et beaucoup plus classique)
- les formes : évidemment rien de carré, mais rien de parfaitement rond non plus cela rend la chose trop enfantine 
- les visuels : chaque astuce aura sa photo ajoutée par son auteur mais si image il doit y avoir, partir sur des visuels de feuilles, de ciel, matérieux naturels brut, etc.. sachant que la macro é ce niveau rend visuellement beaucoup mieux que des plans larges et fouillis de nature ou autres

**Les plus**
- on pourrait imaginer la création de mini-commerce en ligne pour les personnes souhaitant vendre leurs propres produits (cela me paraét trés complexe autant au niveau pratique que légal. Cela voudrait dire faire un commerce généré pour chaque user, vérifier qu'ils sont tous déclarés etc, mais cela pourrait permettre de mettre du stripe)
- on pourrait imaginer un onglet recettes pour rendre le site plus complet mais cela ne constitue vraiment le coeur de l'idée pour le moment

C'était les grandes lignes, y'a encore beaucoup é peaufiner ce n'était qu'un premier jet.

### Pourquoi rejoindre ce projet :

Grande question. Tu as envie de faire un pinterest de l'écolo ? Bah alors viens. Je veux juste préciser que ce projet n'a pas vocation à aller plus loin que THP, aprés rien n'est impossible mais devoir trouver des annonceurs ou des partenariats pour pouvoir générer de l'argent est quelque chose qui ne me tente absolument pas du tout.  Ici, il sera seulement question de mettre en pratique tout ce que l'on a vu durant la formation et de rendre un projet le plus propre possible. Et évidemment si tu as des questions, des idées, je suis preneur. 

