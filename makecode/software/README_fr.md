# Description des éléments du dossier

## Thermomètre frontal version finale

* microbit-mlx90614-nocal_v2_fr.hex -- (Version française)
* microbit-mlx90614-nocal_v2_fr.hex -- (Version anglaise)
* microbit-mlx90614-nocal_v2.hex -- (Version chinoise)

La version finale est celle que nous avons utilisée dans l'atelier. Cette version continuera à afficher les informations sur la température après la mesure, et ne quittera pas le mode d'affichage tant que l'utilisateur n'aura pas appuyé sur le bouton B à droite. Le comportement est conçu pour l'appareil dont le capteur et l'affichage ne sont pas du même côté (car l'utilisateur peut devoir se retourner pour voir les informations de température).


## Version test rapide

* microbit-mlx90614_test.hex -- test rapide pour voir si le module fonctionne correctement

C'est le programme de détection de la température le plus simple. Après la mise sous tension, il lit la température et l'affiche toutes les secondes. Ce programme peut vous aider à vérifier rapidement si le module de détection de la température fonctionne correctement ou non.


## Autre version expérimentale / test

* microbit-mlx90614-cal.hex -- utiliser les boutons pour effectuer le calibrage (version expérimentale)

Utilisez les boutons pour effectuer la correction de la température pendant l'exécution. Appuyez sur les touches A et B en même temps pour entrer dans le mode d'étalonnage. En mode d'étalonnage, appuyez sur la touche A ou B pour augmenter ou diminuer la température. Appuyez à nouveau sur les touches A et B en même temps pour sortir du mode d'étalonnage.

Veuillez noter que le microbit n'a pas de dispositif de stockage pour stocker vos valeurs de calibrage. Vous devez recalibrer chaque fois que l'appareil est allumé.

* microbit-mlx90614-nocal_v1.hex -- La différence entre v1 et v2 est que, dans v1, après avoir appuyé sur la touche A pour détecter, la température ne s'affiche qu'une seule fois.

Cette version est similaire à la version v2 que nous avons utilisée dans l'atelier. La principale différence est que v1 n'affiche la température qu'une seule fois après la mesure. Le comportement est conçu pour l'appareil dont le capteur et l'affichage sont du même côté.

*** Traduit avec www.DeepL.com/Translator (version gratuite) ***

