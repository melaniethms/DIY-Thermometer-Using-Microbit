# Guide micro:bit en 10 minutes

*ver 1.0*

---

[Micro:bit](https://microbit.org) est un microcontrôleur conçu par la BBC pour que les écoliers britanniques apprennent à programmer et à créer électroniquement。


## aperçu

* : : Il faut préparer ces choses.
* : : processus de développement des microbits
* : : Quels sont les outils utilisés pour développer
	* Introduction aux outils de développement MakeCode
* Comment transférer le programme écrit sur un microbit
* : : Sur l'approvisionnement en électricité
* : : Comment partager votre travail


## Ce que vous devez préparer

Pour créer avec des microbits, il suffit de trois choses :

1. la carte mère de microbits.
2. câble micro-usb
3. des ordinateurs avec accès à Internet

![](../images/mb-01.jpg)

![](../images/usb-02.jpg)

![](../images/laptop.jpg)


## Le processus de développement des microbits

On peut considérer un microbit comme un micro-ordinateur qui peut tenir dans la poche, mais pour que cet ordinateur fonctionne, il faut écrire des programmes pour dire au microbit ce qu'il doit faire. Le programme que vous écrivez est ce que nous appelons généralement un logiciel.

Les étapes se déroulent ainsi.

1. écrivez le programme logiciel sur votre ordinateur en utilisant "l'éditeur de programme propriétaire de Microbit".
Connectez votre ordinateur et votre carte mère à l'aide du câble "microusb".
3. télécharger le logiciel écrit du câble micro-usb à la carte mère microbit.
4. le microbit fonctionnera comme vous l'écrivez (si vous l'écrivez correctement)。


## Sélectionnez un éditeur de programmes pour microbits.

Tout comme WORD est un éditeur qui vous permet d'écrire des documents et PowerPoint est un éditeur qui vous permet de créer des présentations, un "éditeur de programmes" est un éditeur dédié qui vous permet d'"écrire des programmes".

En termes de microbits, il existe actuellement deux autres éditeurs communs.

* : : [MakeCode] (https://makecode.microbit.org/)
	* : : Le processus d'"épellation" du programme à l'aide d'un puzzle de bloc
	* Spécialement recommandé pour les utilisateurs débutants
* [Python pour micro:bit](https://python.microbit.org/v/2.0)
	* Utilisation du langage Python
	* La manière dont les modèles de texte sont compilés

Nous avons choisi ici MakeCode.

### MakeCode Environnement

* Zone de simulation - vous permet de voir l'effet lorsque vous n'avez pas de carte micro:bit
* Zone de blocs - Utilisez les blocs ici pour organiser le déroulement de votre programme
* Archive - sauvegarde dans un fichier .hex (le contenu contient des informations sur les codes)
* Espace d'enseignement - ressources pédagogiques intégrées

![](../images/makecode-01.png)


## Téléchargez votre programme en microbits

1. assurez-vous que votre microbit est connecté à votre ordinateur par un câble micro-USB.
2. vous devriez constater que le microbit est utilisé par votre ordinateur comme une clé USB
3. cliquez sur le bouton "Download" de MakeCode, un fichier .hex sera téléchargé.
Glissez et déposez le fichier .hex sur le lecteur (ou copiez et collez le).
	* Pendant la transmission, le voyant orange au dos de la carte micro:bit se met à clignoter. Une fois quele clignottement s'arrête, le transfert est terminé.
Voilà, maintenant nous pouvons voir si le microbite fonctionne comme nous l'espérons.

![](../images/program.gif)


## À propos de l'Expansion Board

Un examen plus approfondi de la zone des doigts dorés du micro:bit révèle qu'à l'exception de P0, P1, P2, 3V, GND, qui sont relativement grands et pratiques à utiliser directement avec le câble de la pince crocodile, les autres largeurs de broches sont trop petites pour être utilisées.

![](../images/alligator-clips.jpg)

Par conséquent, un équipement séparé appelé carte d'extension E/S est généralement acheté lors de la réalisation d'un projet. Il suffit d'insérer le micro:bit dans la fente de la carte d'extension, et vous pouvez utiliser les broches de la carte d'extension directement pour contrôler le câblage.

![](../images/expansion-01.jpg)


## À propos de l'alimentation électrique

Vous ne voulez certainement pas tirer sur le câble USB et l'ordinateur chaque fois que vous utilisez un microbit. Un bloc-piles externe peut être utilisé pour alimenter deux piles AAA.

![](../images/battery.jpg)

Les fentes se trouvent dans le coin supérieur droit du dos.

![](../images/mb-02.jpg)


## Comment partager votre travail

Utilisez la fonction "Partager le projet" de l'éditeur MakeCode pour partager votre travail.

EX : [thermomètre infrarouge v2](ttps://makecode.microbit.org/_JxsbYaXXLLJv ou https://makecode.microbit.org/_6bR6rA9b0aKV en français

### Comment obtenir le code ?

En fait, le fichier .hex téléchargé sur le microbit contient les informations du code. Il suffit d'utiliser la fonction "Import" de MakeCode.

~ FIN ~
