
# Micro:bit Logiciels.

Cet article explique comment mettre à jour le logiciel nécessaire pour l'atelier, vers une micro:bit board。Tous les logiciels sont développés en utilisant [Microsoft MakeCode pour micro:bit](https://makecode.microbit.org/) avec le nom de fichier .hex.。


## Logique de programmation

Appuyez sur le bouton A sur le côté gauche du micro:bit pour afficher la température mesurée.。

La touche B à droite permet d'afficher la valeur de correction de la température, qui est par défaut 0, c'est-à-dire qu'aucune correction n'est nécessaire。


## Description du fichier

Il y a plusieurs fichiers .hex dans le répertoire du logiciel. C'est le logiciel pour micro:bit, vous pouvez passer ces fichiers .hex dans micro:bit via un câble USB et vous avez terminé la mise à jour du logiciel. Tous les logiciels peuvent être remplacés à tout moment, et vous pouvez toujours choisir le logiciel à mettre à jour en fonction de vos besoins. Pour plus de détails, voir README.md dans [répertoire des logiciels](software/).


## Comment mettre à jour un logiciel

En fait, pour micro:bit, mettre le logiciel à jour est aussi simple que de copier un fichier sur une clé USB.

Utilisez d'abord un micro usb pour connecter le micro:bit à votre ordinateur. Vous devriez constater qu'une fois que le micro:bit est connecté à l'ordinateur, il est immédiatement reconnu par l'ordinateur comme une clé USB. Si vous utilisez le système Windows, en ouvrant le gestionnaire de fichiers, vous remarquerez qu'il y a un lecteur MICROBIT supplémentaire sur le système。

Maintenant, sélectionnez un fichier logiciel .hex et copiez le fichier .hex sur le lecteur intitulé MICROBIT. micro:bit acceptera automatiquement le logiciel, le mettra à jour, puis redémarrera et exécutera votre programme.


![](images/program-win.gif)


## Référence.

Vous voulez une introduction rapide à micro:bit ? Veuillez vous référer au manuel de l'atelier dédié [Ten Minutes to Understand Micro:bit] (docs/10-minute-microbit-guide.md).


~ FIN ~
