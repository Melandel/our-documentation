# Discussions
Traduction française du type de documentation `Explanations` (en anglais) du système divio.

[[Source][divio_explanation]]

Egalement appelées explications ou bien background

Désigne un texte qui clarifie et éclaire un sujet particulier. Les explications élargissent la manière dont la documentation couvre un sujet.

Exemples:
* [arborescence (💭)][exemple_concret_1]
* [conventions_de_nommage (💭)][exemple_concret_2]

***
***

## Notes
Elles sont orientées vers la compréhension.

Les explications peuvent tout aussi bien être décrites comme des discussions ; elles sont de nature discursive. Elles sont l'occasion pour la documentation de prendre du recul, en adoptant une vision plus large, en l'éclairant d’une hauteur supérieure ou points de vue différents. Vous pouvez imaginer qu'un document de discussion soit lu à loisir, plutôt que par-dessus du code.

Cette section de la documentation est rarement créée explicitement et, à la place, les extraits d’explications sont dispersés par-ci par-là dans les autres types de documents. Parfois, l’information existe, mais a un nom tel que Egalement ou Autres - dont le nommage n’est pas assez indicatif.

Les discussions sont moins faciles à créer qu'il n'y paraît - les choses qui sont simples à expliquer lorsque vous connaissez le point de départ de la question sont moins faciles lorsque vous partez d’une page blanche.

Un sujet n'est pas défini par une tâche spécifique que vous voulez accomplir, comme un tutoriel, ni ce que vous voulez que l'utilisateur apprenne, comme un premiers pas. Il n'est pas défini par un morceau de la machine, comme un document d'informations. Il est défini par ce que vous pensez être un domaine raisonnable à essayer de couvrir à un moment, de sorte que la division des sujets de discussion peut parfois être un peu arbitraire.

## Analogie avec la cuisine
Pensez à une oeuvre qui traite de la nourriture et de la cuisine dans le contexte de l’Histoire, de la science et de la technologie. Il s'agit de la cuisine.

Il n'enseigne pas, ce n'est pas une collection de recettes, et il ne se contente pas de décrire.

Au lieu de cela, il analyse, considère les choses sous de multiples perspectives. Cela pourrait expliquer pourquoi nous faisons les choses comme nous le faisons aujourd’hui, ou même décrire de mauvaises façons de faire les choses, ou d’obscures alternatives.

Il approfondit nos connaissances et les enrichit, même si ce n'est pas la connaissance que nous pouvons appliquer au sens pratique - mais elle n'a pas besoin d'être pratiquée, pour être précieuse.

C'est quelque chose que nous pourrions lire à notre guise, loin de la cuisine elle-même, quand nous voulons de penser à cuisiner à un niveau plus élevé, et de mieux comprendre le sujet.

## Comment écrire une bonne explication
### Fournir un contexte
Les explications sont un lieu pour l'arrière-plan et le contexte - par exemple, les formulaires Web et la manière dont ils sont traités chez Django, ou Recherche dans le CMS django.

Ils peuvent également expliquer pourquoi les choses sont comme elles sont - les décisions de conception, les raisons historiques, les contraintes techniques.

### Discuter des alternatives et des avis
L'explication peut envisager des alternatives, ou plusieurs approches différentes d'une même question. Par exemple, dans un article sur le déploiement de Django, il conviendrait d'envisager et d'évaluer différentes options de serveurs Web.

Les discussions peuvent même examiner et peser des avis contraires - par exemple, si les modules d'essai doivent être dans un répertoire de paquets ou non.

### N'instruisez pas ou ne fournissez pas de référence technique
L'explication devrait fournir des choses que les autres parties de la documentation ne font pas. L'explication n’est pas l’endroit pour apprendre à l'utilisateur comment faire quelque chose. Elle ne doit pas non plus fournir de description technique. Ces fonctions de documentation sont déjà prises en charge dans d'autres documents.

## Exemples
Jetez un coup d'oeil à [la section Discussions de divio][exemple_explanation]
Ces articles n'enseignent rien. Ils ne disent pas à l'utilisateur ce qu'il doit faire. Ce ne sont pas des documents d'information. Ils discutent juste de sujets particuliers. L'utilisateur n'a pas besoin de connaître (par exemple) la mise en cache ou le CDN ou comment nous gérons des variables d'environnement pour utiliser la plate-forme ou d'accomplir une tâche particulière, mais il est probable qu’un moment arrive où l'expérience et l'utilisation de la plate-forme de quelqu'un seront améliorées en ayant une compréhension plus claire, meilleure et plus profonde de ces explications.

Ces articles donnent une vue d'ensemble, le contexte. Les utilisateurs sont des êtres humains ; peut-être qu'ils n'ont pas besoin de savoir exactement pourquoi nous faisons certaines choses d'une certaine manière, mais le savoir pourrait bien leur fournir une sorte de satisfaction et de confort qui en font des utilisateurs plus heureux du produit.

**Voir également:**
* [catalogue de termes (ℹ️)][doctype_catalogue_de_termes]
* [archives (ℹ️)][doctype_archives]
* [premiers pas (ℹ️)][doctype_premiers_pas]
* [tutoriels (ℹ️)][doctype_tutoriels]
* [informations (ℹ️)][doctype_informations]

[exemple_explanation]: https://docs.divio.com/background/
[divio_explanation]: https://docs.divio.com/documentation-system/explanation/
[exemple_concret_1]: ../discussions/arborescence.md
[exemple_concret_2]: ../discussions/conventions_de_nommage.md
[doctype_catalogue_de_termes]: ./catalogue_de_termes.md
[doctype_archives]: ./archives.md
[doctype_premiers_pas]: ./premiers_pas.md
[doctype_tutoriels]: ./tutoriels.md
[doctype_informations]: ./informations.md
