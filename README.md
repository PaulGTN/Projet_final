# Je Passe Au Vert

Une plate-forme de partage/d'échange de conseils et de bonnes adresses en mode pinterest-like pour améliorer son impact environnemental et sa manière de consommer.

<img src="https://images.pexels.com/photos/106150/dewdrop-morning-sun-mirror-blade-of-grass-106150.jpeg?auto=compress&cs=tinysrgb&h=750&w=1260">

### Objectifs :

**Quoi**
- Créer une plate-forme simple pour partager, rechercher tout types de conseils et bonnes adresses

**Pour qui**
- Tous types d'utilisateurs cherchant, à son échelle, à réduire facilement son impact personnel sur l'environnement 

**Pourquoi**
- Déjà ce n'est pas une idée originale (c'est mon 4e essai et impossible de trouver quelque chose qui n'a pas encore été fait, foutu internet)
- Ensuite face au mode de consommation actuelle, arrosé par le plastique et autres produits étranges, il semble bien difficile de pouvoir réduire son impact sur l'environnement. Toutefois il existe des millions d'astuces trouvables sur internet sur ce sujet. Alors pourquoi faire un enième site me direz-vous ? Et bien parce que 90% (chiffre complètement inventé mais qui me semble pas loin de la réalité) de ces astuces se trouvent dispatchées sur des tonnes de site, souvent en mode top 10 sur un blog fixe. Vous cherchez une astuce en particulier ? Préparez vous à devoir vous baladez sur des dizaines de pages et de sites différents pour trouver la bonne ? Vous avec une problématique sur un sujet précis ? Priez pour que le site posséde un espace avec des commentaires et quelqu'un viennent vous répondre dans un délai raisonnable. 

**Ici rien de tout ça**
- Créez un profil, puis recherchez, partagez vos astuces/bonnes adresses simplement (ex: "Fabriquer du shaampoing bio", "Comment créer un potager dans un appartement")
- Un probléme, une question ? rendez-vous dans l'espace forum pour voir si quelqu'un a une solution à proposer (ex: "Je voudrais faire une lessive maison mais mon enfant est allergique à tel produits, connaissez-vous une alternative ?", "J'ai pas franchement envie de passer aux céréales en vrac dans un sac en tissu pour le petit-déjeuner sans avoir à faire mes viennoiseries tout les matins, quelqu'un connaît une marque plutôt clean et sans emballages ?")

Bref vous voyez le topo. L'idée est de tout centraliser sur un site (beau gosse de préférence), dans un concept proche de Pinterest,  pour ne pas avoir à se taper des recherches googles interminables ou de tomber sur un blog dégueulasse d'une mamie habitant à Mâcon, certes très gentille  mais pas très doué en programmation.

## Les bases :

Le site est auto-nourri par sa communauté. Donc pas de scrapping, les données étant tellement dispersées qu'il paraît impossible de faire cela dans un délai convenable. 
Il est divisé quatre grandes parties, les astuces, le forum, les adresses et le profil.

**Les pages**
- Un accueil simple permettant d'accéder aux différentes fonctionnalités et de s'inscrire ou se connecter.  Un carousel présentant les meilleurs astuces du mois (par exemple) serait le bienvenue
- Des formulaires de connexion, inscription, demande de password, etc (via Devise)
- Un index des astuces accesible par tous mais nécessitant une inscription pour aller plus loin (faut bien se vendre un peu), sur un système simple de cartes avec un moteur de recherche
- Un index du forum, accessible à tous mais nécessitant une inscription pour pouvoir poster,
avec une belle liste de cartes et encore un moteur de recherche
- Un index des bonnes adresses, carte, moteur, etc...
- Un show de chaque astuce/adresse/forum avec une possibilité de sauvegarder les astuces et/ou son auteur et adresses 
- Un create/edit pour chacun de ces objets
- Une page profil qui comprend ses informations personnelles et la possibilité de les modifier, ses astuces/adresses/questions/réponses postées (pas les commentaires sur les astuces), ses astuces/auteurs/adresses sauvegardés

**Les fonctionnalités**
- Possibilité d'inscription via Facebook pour partager facilement ses trouvailles avec ses amis
(via API Facebook)
- Géolocalisation sur une map des bonnes adresses postées dans leur show individuel (via API Google maps)
- Sauvergarder une astuce/adresse dans son profil
- S'abonner à un utilisateur 
- Un mailer, confirmation d'inscription, renouvellement password, et envoi automatique dès qu'un auteur suivi poste un nouvel article ou adresse, possibilité d'abonnement à une newsletter

**Le visuel**
- Avec les trucs écolos, la charte graphique c'est facile. Tu regardes une forêt tu as trouvé le truc
- Les couleurs : un vert pâle, un bleu pastel, un marron pastel et des nuance de blanc et de gris. Quelque chose de clair dans tous les cas
- Les polices : légéres, fines, sûrement légérements courbées, deux seulement (peut-être trois dont une spécialement pour le footer et beaucoup plus classique)
- Les formes : évidemment rien de carré
- Les visuels : chaque astuce aura sa photo ajoutée par son auteur mais si image il doit y avoir, partir sur des visuels de feuilles, de ciel, matériaux naturels brut, etc.. sachant que la macro à ce niveau rend visuellement beaucoup mieux que des plans larges et fouillis de nature ou autres

**Le champ des possibles**
- Un système de like serait naturel pour noter les astuces
- On pourrait imaginer la création d'un e-commerce en ligne pour les personnes souhaitant vendre leurs propres produits et ainsi insérer stripe pour avoir une API en plus (par contre légalement c'est assez flou)
- On pourrait intégrer un onglet recettes pour rendre le site plus complet mais cela ne constitue vraiment le coeur de l'idée pour le moment
- Rajouter un feed personnalisé dans chaque page profil selon ses auteurs suivis

C'était les grandes lignes, y'a encore beaucoup à peaufiner ce n'était qu'un premier jet.

### Pourquoi rejoindre ce projet :

Grande question. Tu as envie de faire un pinterest de l'écolo ? Bah alors viens. Je veux juste préciser que ce projet n'a pas vocation à aller plus loin que THP, après rien n'est impossible mais devoir trouver des annonceurs ou des partenariats pour pouvoir générer de l'argent est quelque chose qui ne me tente absolument pas du tout.  Ici, il sera seulement question de mettre en pratique tout ce que l'on a vu durant la formation et de rendre un projet le plus propre possible. Et évidemment si tu as des questions, des idées, je suis preneur. 

