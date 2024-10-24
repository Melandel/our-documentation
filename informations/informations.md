# Informations
Traduction française du type de documentation `Reference guides` (en anglais) du système divio.

[[Source][divio_reference]]

Désigne une _description technique de la machine_ et de _la_ manière de l'utiliser.

La référence n’a qu'un seul objectif: décrire. Elle est ultimement déterminée par le code source, parce qu'en fin de compte, c'est ce qu’il implémente.

Exemples:
* [divio (ℹ️)][exemple_concret_1]
* [conventions de nommage (ℹ️)][exemple_concret_2]

***
***

## Notes
Les documents de référence sont axés sur l'information.

Autant que possible, la référence peut contenir des exemples pour illustrer l'utilisation, mais elle ne devrait pas tenter d'expliquer les concepts de base, ni comment accomplir des tâches communes.

Les documents de référence devraient être simples et directs.

Notez que la description comprend une description basique de la façon d'utiliser la machine - comment utiliser une fonctionnalité, ou invoquer une certaine opération, par exemple, ou des précautions à prendre lors de la transmission de quelque chose à une fonction. Toutefois, cela fait simplement partie de sa fonction de référence technique, et il ne faut pas confondre cela avec un tutoriel: décrire l'utilisation correcte du logiciel (référence technique) n'est pas la même chose que de montrer comment l'utiliser pour atteindre une certaine fin (tutoriel).

Pour certains développeurs, les guides de référence sont le seul type de documentation qu'ils peuvent imaginer. Ils comprennent déjà leur logiciel, ils savent comment l'utiliser. Tout ce qu'ils peuvent imaginer que d'autres personnes pourraient avoir besoin, ce sont des informations techniques à ce sujet.

Les documents de référence tendent à bien être écrits. Ils peuvent peut même - dans une certaine mesure - être générés automatiquement, mais cela n'est jamais suffisant à lui seul.

## Analogie avec la cuisine
Considérez un article d'encyclopédie sur un ingrédient, par exemple le gingembre.

Lorsque vous cherchez du gingembre dans un ouvrage de référence, ce que vous voulez, c'est des informations sur l'ingrédient - des informations décrivant sa provenance, son comportement, ses composants chimiques, comment il peut être cuisiné.

Vous vous attendez à ce que, quel que soit l'ingrédient que vous recherchez, les informations seront présentées de la même manière. Et vous vous attendez à être informé des faits fondamentaux, tels que le gingembre, est un membre de la famille qui comprend le curcuma et la cardamome.

C'est aussi là que vous vous attendez à être alerté sur les problèmes potentiels, tels que: le gingembre est connu pour provoquer des brûlures d'estomac dans certains individus ou : le gingembre peut interférer avec les effets des anticoagulants, tels que l'aspirine.

## Comment écrire une bonne référence
### Structurer la documentation autour du code
Structurez la documentation de référence de la même façon que la base de code, afin que l'utilisateur puisse naviguer à la fois le code et la documentation d’un même mouvement. Cela aidera également les mainteurs à déterminer où la documentation de référence fait défaut / doit être mise à jour.

### Soyez cohérent
Dans les guides de référence, la structure, le ton, le format doivent tous être cohérents - aussi cohérents que ceux d'une encyclopédie ou d'un dictionnaire.

### Ne faites rien d'autre que décrire
La seule responsabilité de la référence technique est de décrire, aussi clairement et complètement que possible. Tout le reste (explication, discussion, instruction, spéculation, opinion) n'est pas seulement une distraction, mais le rendra plus difficile à utiliser et à maintenir. Donner des exemples pour illustrer la description, le cas échéant.

Ne soyez pas tenté d'utiliser la référence technique pour apprendre comment faire des choses, au-delà des capacités de base du logiciel. Et empêchez les explications de concept ou discussions à ce niveau. Au lieu de cela, créez des liens avec des tutoriels, des explications et des premiers pas.

### Soyez précis
Les descriptions doivent être exactes et tenues à jour. Tout écart entre la machine et votre description créera de la confusion et de la méfiance chez un utilisateur.

## Exemples
Jetez un oeil à [un exemple tiré de la référence technique de divio][exemple_reference]

Il s'agit d'un guide de référence typique (dans ce cas, pour Divio CLI).

La description est tout ce que fait cette page, en indiquant dans une forme complète et précise les fonctions, les commandes et les options de l'outil.

Ce n'est pas une lecture amicale ou engageante, mais son but est de faire en sorte que la recherche d'informations sur la fonctionnalité soit aussi rapide et sans distraction que possible.

**Voir également:**
* [catalogue de termes (ℹ️)][doctype_catalogue_de_termes]
* [archives (ℹ️)][doctype_archives]
* [premiers pas (ℹ️)][doctype_premiers_pas]
* [tutoriels (ℹ️)][doctype_tutoriels]
* [discussions (ℹ️)][doctype_discussions]

[exemple_reference]: https://docs.divio.com/divio-cli/reference/
[divio_reference]: https://docs.divio.com/documentation-system/reference/
[exemple_concret_1]: ./divio.md
[exemple_concret_2]: ./conventions_de_nommage.md
[doctype_catalogue_de_termes]: ./catalogue_de_termes.md
[doctype_archives]: ./archives.md
[doctype_premiers_pas]: ./premiers_pas.md
[doctype_tutoriels]: ./tutoriels.md
[doctype_discussions]: ./discussions.md
