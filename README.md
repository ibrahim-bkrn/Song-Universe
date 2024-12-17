# Song-Universe
1. Différence entre HTML et CSS
HTML structure le contenu d’une page web (titres, paragraphes, images), tandis que CSS gère l’apparence visuelle (couleurs, tailles, positionnement). HTML est le squelette, CSS est le design.

2. Définition de la sémantique
La sémantique en HTML consiste à utiliser des balises qui décrivent clairement leur rôle. Par exemple, <header> pour l’en-tête, <article> pour un contenu qui se répète (blog), ce qui améliore l’accessibilité et le SEO.

3. Différence entre un ID et une classe
Un ID est unique et identifié par #, utilisé pour un seul élément. Une classe, précédée de ., est réutilisable pour plusieurs éléments partageant des styles communs.

4. Différence entre Flexbox, Grid et Position
Flexbox : Pour aligner des éléments dans une direction (ligne ou colonne), idéal pour des structures linéaires.
Grid : Système de grille, idéal pour des mises en page complexes.
Position : Définit la manière dont un élément est positionné (relatif, absolu ou bien fixe).

6. Fonctionnement des pseudo-classes et des transitions
Pseudo-classes : Appliquent un style à un état spécifique d’un élément, ex. :hover pour le survol.
Transitions : Permettent des animations fluides entre deux états (ex. couleur qui change progressivement).

6. Attributs HTML et leur utilité
Les attributs ajoutent des informations ou des comportements aux balises HTML (ex. href pour les liens, src pour les images). Ils sont essentiels pour définir des fonctionnalités.

7. Fonctionnement d’un formulaire HTML
Un formulaire collecte des données via des éléments comme <input>, <textarea>, ou <select>, et les envoie à un serveur à l’aide d’attributs comme method et action (URL.

8. Optimisation des images et vidéos
Convertir les medias avec des formats optimisé pour le web tel que webP pour les images et ensuite redimensionner à la taille nécessaire.

10. Fonctionnement des media queries
Les media queries appliquent des styles conditionnels en fonction de la taille de l’écran (@media (max-width: 768px)). Elles sont indispensables pour le design responsive.

---------------------------------------------------------------------------------------------------------

Explication du squellette HTML :

Le squelette HTML se divise en trois grandes parties :

Doctype et structure principale :
- Le <!DOCTYPE html> spécifie que la page utilise HTML5, la norme actuelle.
- La balise <html> enveloppe tout le document, et l'attribut lang="en" indique que le contenu est en anglais.
  
En-tête (<head>) :
  Métadonnées :
- meta charset="UTF-8" : Définit l'encodage des caractères pour une compatibilité universelle.
- meta name="viewport" : Permet un affichage responsive sur tous les écrans.
- meta name="description" : Fournit une description de la page pour le SEO.
  Ressources :
- Le fichier CSS externe (styles.css) et les polices Google sont intégrés ici.
- Titre : Définit le texte affiché dans l'onglet du navigateur.

Corps de la page (<body>)
- <header> : Contient la barre de navigation avec un logo, des liens, et un bouton pour contacter le photographe.
- <main> : Divisé en plusieurs sections :
Présentation (<section id="firstSection">) : Un titre et une phrase d'accroche.
Galerie (<section id="secondSection">) : Montre des réalisations avec des images et des dates.
À propos (<section id="thirdSection">) : Une description personnelle et un portrait.
Formulaire de contact (<section id="contact">) : Permet aux utilisateurs de laisser un message via un formulaire interactif.
- <footer> : Mentionne les droits réservés.
