# OC-ASRS-Projet-2-Gerez-les-demandes-au-quotidien
OpenClassrooms : Administrateur Systèmes, Réseaux et Sécurité 2024-2025
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Mission - Présentation

Ce projet a été mis à jour le 16 décembre 2022 pour vous permettre de travailler avec l'outil agent GLPI et d'installer le serveur. Fusion Inventory a été retiré. Un ticket des demandes a également été ôté. 
Bannière de scénario

Vous êtes administrateur systèmes et réseaux chez OpenShowroom, une entreprise de e-commerce en plein essor spécialisée dans la vente de vêtements et de chaussures.
Logo d'OpenShowroom

Vous travaillez depuis quelques mois au sein du service Informatique dans le pôle Infrastructure composé de Marina, votre responsable, et Malek, également administrateur systèmes et réseaux. Vous faites donc partie du support de niveau 2, et traitez les incidents qui n’ont pas pu être résolus par les techniciens (niveau 1).
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Mission - Détails

En arrivant ce matin au bureau, vous tentez de visualiser les demandes en cours sur l’outil GLPI, en vain.

Vous découvrez un mail de votre responsable, Marina.  

 

De : Marina

À : Vous

Date : Hier à 21h27

Sujet : Urgent - Serveur GLPI

Salut !

 

Je ne sais pas si tu es au courant mais cet après-midi, le serveur GLPI est tombé en panne.

Malheureusement, nous n’avons plus de sauvegarde de ce serveur. 

Il faut absolument refaire le serveur dans les plus brefs délais. Je t’ai laissé une documentation de la configuration du serveur en pièce jointe. 

Toutes les demandes d’aujourd’hui n’ont pu être ni entrées ni traitées dans la base GLPI. Malek a répertorié toutes les demandes dans un tableur (en PJ également) afin de laisser une trace.

 

Malek sera en congé demain, et ce pour une semaine. Je te laisse donc finaliser, s’il te plaît, le reste des tâches, à savoir :

    créer le serveur GLPI sous Debian (dans leurs dernières versions stables) ;
    créer dans GLPI tous les tickets répertoriés dans le tableur ;
    attribuer les tickets de niveau 1 aux techniciens ;
    t’attribuer les demandes de niveau 2 (Malek a inséré le plus d’informations possible pour t’aider sur le traitement) ;
    traiter les tickets de niveau 2 dans l’ordre de priorité (du plus urgent au moins urgent).

Sois vigilant sur le nommage, voici le standard : “action_ticket_nX.pdf” (X étant le numéro du ticket dans GLPI).

 

Il faudrait organiser les demandes qui nous concernent en les triant et en les priorisant et, comme tu as l’habitude de le faire, proposer les meilleures solutions pour chacune des demandes. 

 

J'ai ajouté un dernier document en pièce jointe qui inclut toutes les demandes. C’est important que les réponses soient toujours formulées avec professionnalisme et courtoisie. N’oublie pas de checker la boîte vocale du service ! On a sûrement dû rater des appels aujourd’hui…

 

Pourrais-tu me montrer ton export de la base de données de GLPI au format dump MySQL après avoir saisi et traité toutes les demandes d’assistance de niveau 2 ?

 

Merci ! À demain !

 

Marina

Pièces jointes : 

    Machine virtuelle GLPI
    Documentation GLPI
    Demandes

 

Bannière quelques minutes plus tard 

Vous êtes en train de consulter les pièces jointes quand un nouveau message de Marina arrive.

 

De : Marina

À : Vous

Date : aujourd'hui à 9h15

Sujet : Complément d’informations pour le GLPI

Hello,

Pour faire suite à mon mail d’hier soir, voici quelques éléments à prendre en compte également.

Parmi les tickets, je me suis rendue compte qu’il y en a 3 qui nécessitent la rédaction de documentation technique ou de mails. J’ai besoin que tu me transmettes ces éléments au format PDF, et que tu les mettes en lien avec la base de connaissances GLPI.

J’ai appris que l’équipe IT du siège de Bruxelles utilisait un agent GLPI pour automatiser la remontée des postes de travail et en était très satisfait. Nous avons une réunion d’équipe prévue la semaine prochaine, ce serait cool que tu nous fasses des recherches sur cette solution, et que tu nous fasses une présentation de l’outil, de ses avantages et de sa mise en place sur l’infrastructure, en créant par exemple une machine virtuelle sous Windows 10 ou 11 et en installant l’agent dessus. 

Enfin, dernière chose. Pour améliorer la formation des nouveaux techniciens de support niveau 1, est-ce que tu pourrais faire un logigramme clair et simple qui leur explique comment se passe le processus de création et de gestion des tickets, depuis la prise en compte de l’incident jusqu’à sa résolution, en passant par l’attribution et le traitement ? 

 

Évidemment, il faudra bien prendre en considération le référentiel ITIL pour concevoir ce logigramme.

 

Le but est qu’ils comprennent que certains tickets peuvent nous être transférés dans certains cas, car on a remarqué que beaucoup de tickets restaient en attente, alors qu’ils étaient clairement du ressort de notre équipe. D’ailleurs, j’ai trouvé un outil plutôt pratique pour faire des schémas, n’hésite pas à l’utiliser. Le voici : https://app.diagrams.net/  

Je te remercie pour ton aide.

 

À plus tard !

 

Marina

 

Bannière quelques minutes plus tard

Vous consultez la boîte vocale du service pour vérifier que vous n’avez pas manqué d’appels suite au bug. Vous avez deux messages en attente.

Voici la retranscription de ces messages.

 

Vous notez de bien ajouter un ticket relatif à ces 2 messages, dans lequel vous rédigerez une proposition de réponse, que vous présenterez au format PDF, et qui permettra de résoudre le problème de Steeve.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Livrables et soutenance
Livrables du projet

    Un export de la base de tickets sur le logiciel de ticketing au format dump MySQL, avec toutes les demandes d’assistance saisies.
    Les 4 documents au format PDF mentionnés dans les demandes :
        médiation entre Raphaël et Steeve
        prise de contact avec le partenaire Ocito pour le VPN
        demande d'équipement au service achat
        réponse personnalisée à Steeve

        Vous les insérerez également dans GLPI.
    Le support de présentation de l’outil agent GLPI demandé par Marina, au format PDF.
    Le logigramme pour la formation de l’équipe Support niveau 1, au format PDF. 

Pour faciliter votre passage devant le jury, déposez sur la plateforme, dans un dossier zip nommé “Titre_du_projet_nom_prénom”, tous les livrables du projet comme suit : Nom_Prenom_n° du livrable_nom du livrable_date de démarrage du projet.

Cela donnera : 

    Nom_Prénom_1_export_mmaaaa
    Nom_Prénom_2_documents_mmaaaa
    Nom_Prénom_3_agent_GLPI_mmaaaa
    Nom_Prénom_4_Logigramme_mmaaaa

Par exemple, le premier livrable peut être nommé comme suit : Dupont_Jean_Export_012022.

 
Bannière annonçant la soutenance du projet

    Présentation des livrables (15 minutes) : 
        Vous justifierez l’ordre de vos priorités ;
        Vous présenterez vos résolutions de problèmes en justifiant vos choix ;
        Vous présenterez les 4 documents rédigés répondant aux demandes ;
        Vous présenterez votre bilan à l’aide du support de présentation de votre choix.
    Discussion (10 minutes) :
        L'évaluateur jouera le rôle de Marina et vous challengera sur les possibilités de l’outil GLPI, les notions d’ITIL et l'étude de la mise en place de l'agent GLPI.
    Débriefing (5 minutes) :
        À la fin de la soutenance, l'évaluateur arrêtera de jouer le rôle de Marina pour vous permettre de débriefer ensemble. 

Votre présentation devra durer 15 minutes (+/- 5 minutes). Puisque le respect de la durée des présentations est important en milieu professionnel, les présentations en dessous de 10 minutes ou au-dessus de 20 minutes peuvent être refusées.
 

Vous disposez désormais de l’intégralité des éléments nécessaires à la bonne gestion des différentes demandes, à vous de jouer ! 
