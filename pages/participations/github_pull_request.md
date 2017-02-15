---
layout: pages
title: Didacticiel - Comment participer à ce projet ?
category : github, guide
comments: true
---


Cet article va vous aider à comprendre et créer des "Pull Requests" sur Github, vous permettant ainsi de participer en contribuant au projet.
Sommaire

    1 Qu'est ce qu'un Pull Request ?
    2 Identifier le changement que vous souhaitez faire
    3 Trouver le fichier à modifier sur GitHub
    4 Effectuez vos modifications
    5 Ajouter un titre et une description
    6 Soumettre le Pull Request
    7 Et maintenant ?

##Qu'est ce qu'un Pull Request ?

Un Pull Request est une demande de pull (ajout) d'un peu de code au répertoire, à un projet sur GitHub.

Il arrive que vous vous demandiez si certaines modifications ou ajouts de code que vous réalisez peuvent être utilisés et intégrés au projet. GitHub dispose d'une interface web simple, qui facilite la possibilité de proposer des modifications de code. Il n'est pas nécessaire de devoir installer un logiciel ou de faire autre chose que de s'inscrire pour avoir un compte GitHub.


##Identifier le changement que vous souhaitez faire

Tout d'abord, repérer où réaliser les modifications que vous souhaitez faire.

Par exemple, nous souhaiterions ajouter un un manuel d'utilisation pour une nouvelle déclinaison de notre imprimante 3D.

###Trouver le fichier à modifier sur GitHub

Si vous n'avez pas encore de compte GitHub, inscrivez-vous sur GitHub. C'est gratuit et très facile. Une fois enregistré, rendez-vous sur le répertoire du [projet] "{{ site.github.repository_url }}" ! et trouvez le fichier que vous souhaitez modifier. Vous pouvez naviguer en cliquant sur le dossier et nom de fichier.

Dans notre exemple, nous devons modifier le fichier suivant : /_data/manuals.yml.

### Effectuez vos modifications

Naviguez jusqu'au fichier et modifiez le fichier en cliquant sur l'icône en forme de crayon, sur la droite.

Dans notre exemple, nous allons ajouter le code suivant à la fin du fichier : manuals.yml

- model: Nouveau modèle
  installation_guide: "files/manuels/nouveau_model_guide.pdf"


Remarque : vous avez peut-être remarqué le message en bleu en haut de la page. Ce message vous indique que GitHub a fait une copie du projet, sur laquelle vous pouvez apporter des modifications. Cette copie est appelée un Fork. Les modifications apportées à cette copie peuvent être utilisées dans le projet initial. Si vous souhaitez en apprendre plus sur la façon dont GitHub fonctionne, vous pouvez consulter cet article.


###Ajouter un titre et une description

Sous l'éditeur, il est possible d'ajouter des informations à votre Pull Request en ajoutant un titre et une description.

Le titre doit être court et doit préciser l'objectif du Pull Request.

La description va présenter des informations plus détaillées sur le Pull Request et d'autres informations permettant de le tester. Il est impératif de rendre ces informations les plus complètes et claires que possible. Lorsque vous proposez un Pull Request, il est également conseiller de mentionner le numéro d'ID GitHub du rapport d'anomalie et un lien dans la description. Vous pouvez facilement le faire en faisant précéder le numéro d'ID de l'anomalie par un # (dièse), le lien sera alors automatiquement créé. Vous pouvez trouver ce numéro à la suite du titre de l'anomalie.

###Soumettre le Pull Request

Cliquez sur le bouton Propose file changes et ensuite sur le bouton Create pull request. Votre Pull Request est dès lors créé !


##Et maintenant ?

La seule chose qu'il vous reste à faire maintenant est d'attendre que quelqu'un teste votre PR. Lorsqu'un testeur fera un commentaire sur le PR, vous serez notifié par email. Il peut arriver qu'une personne demande un complément d'informations alors essayez de rester attentif aux actions réalisées sur votre PR.

Si un Pull Request est testé avec succès à deux reprises, un modérateur se chargera de le passer en RTC (pour Ready To Commit) ce qui signifie que le code peut être ajouté et fusionné (merge) au répertoire principal comme partie intégrante du code principal. Dans le langage courant cela signifie que la personne ayant les droits nécessaires, que le correctif ou la nouvelle fonctionnalité ont été testés avec succès et qu'ainsi, ils peuvent être ajoutés de façon définitive au répertoire du projet Imprimantes 3D P802 Series. Votre Pull Request est désormais définitif et sera présent aussitôt sur le site !
