---
layout: default
title: Livre de règles
nav_order: 1
permalink: /rulebook/
---

[Créer un personnage]({{ site.baseurl }}/){: .btn .btn-primary }

# Création du personnage

## Votre point de départ

L'aventure commence à **Antes, capitale du royaume d'Ontin**, à l'occasion des enchères du solstice d'été.

La ville attire pour l'événement des marchands, des nobles, des collectionneurs, des aventuriers et toutes sortes de voyageurs.

Vous avez accepté un travail ponctuel auprès d'Eldon, un marchand venu assister aux enchères. Il recherche des personnes pour assurer sa protection pendant l'événement et à sa sortie.

Il n'est pas particulièrement exigeant sur les qualifications de ses recrues. Que vous soyez mercenaire, érudit, artisan, mage ou simple voyageur, vous avez pu obtenir ce travail.

**La raison pour laquelle vous avez accepté cette mission vous appartient.**

## Qui êtes-vous ?

Pour aider à situer votre personnage dans le monde on propose de répondre à quatre questions :

  1. Quel est votre statut social ?

> Êtes-vous issu de la noblesse, affilié à une grande maison, membre d'une guilde, citoyen ordinaire, vagabond ou fugitif ?

  2. Quelle est votre occupation ?

> Êtes-vous plutôt combattant, artisan, érudit, marchand, praticien de la magie ou travailleur ordinaire ?
  
  3. Pourquoi êtes-vous à Antes ?

> Y avez-vous toujours vécu ? Êtes-vous venu pour le travail, les études, une affaire personnelle, ou fuyez-vous quelque chose ?
  
  4. Pourquoi êtes-vous libre de partir à l'aventure ?

> Avez-vous perdu votre emploi ? Rompu avec votre famille ? Terminé vos études ? Cherchez-vous fortune, du savoir ou une nouvelle vie ?

## Répartition des compétences

À la création, chaque personnage dispose d'un budget de **700 points** à répartir entre ses compétences normales.

Les règles suivantes s'appliquent :

- Chaque compétence normale commence avec un minimum de **15 points**.
- Aucune compétence normale ne peut dépasser **70 points** à la création.
- Des exceptions au minimum de 15 peuvent être autorisées par le MJ si elles sont justifiées par l'histoire du personnage.
- Les points sont répartis librement, sans classe ni profession imposée.

La profession et le passé du personnage peuvent guider cette répartition, mais n'imposent pas de compétences particulières.

### Compétences spéciales initiales

Chaque personnage peut commencer avec **une compétence spéciale**, choisie dans le catalogue ou proposée au MJ.

Cette compétence spéciale :

- Est facultative.
- Commence à **30 points**, sans coût sur le budget initial.
- Ne peut pas être augmentée davantage à la création.
- Nécessite de respecter les prérequis d'apprentissage du catalogue.

Les disciplines avancées nécessitant déjà la maîtrise d'une autre compétence spéciale ne sont pas accessibles à la création, sauf exception accordée par le MJ.

Après la création, les compétences spéciales progressent normalement grâce aux professeurs, aux ouvrages et aux épiphanies.

### Vitalité initiale

Chaque personnage commence avec **100 points de vie de base**.

Les équipements peuvent ajouter des bonus fixes au maximum de points de vie. Une armure peut porter des valeurs finales déterminées manuellement ou calculer séparément ses bonus de PV, sa Protection physique et sa Protection magique selon la formule suivante :

```text
valeur effective = floor(valeur de base × (1 + (niveau de l'Item − 1) × ratio de la statistique))
```

Chaque statistique possède son propre ratio. Au niveau `1`, la valeur effective est exactement égale à la valeur de base ; le ratio détermine seulement la progression des niveaux supplémentaires. Le niveau `0` désigne une base d'Item non finalisée, qui n'est pas encore utilisable comme équipement. Une base peut fixer les niveaux minimum et maximum auxquels un générateur est autorisé à la sélectionner. Les réductions en pourcentage restent des propriétés finales séparées et ne sont pas multipliées par le niveau.

# Compétences

Les personnages ont un ensemble de compétences communes. Leur degré de maîtrise est définie sur une échelle de 1 à 100.

Compétences d'actions, sujettes à la [résolution normale](#résolution-daction). Elles permettent *d'intervenir sur le monde*, avec des conséquences et des compromis possibles:

   - [Artisanat, construire](#artisanat-construire)
   - [Athlétisme](#athlétisme)
   - [Discrétion](#discrétion)
   - [Intimider](#intimider)
   - [Mentir, convaincre](#mentir-convaincre)
   - [Piloter](#piloter)
   - [Réflexes](#réflexes)
   - [Serrures et pièges](#serrures-et-pièges)
   - [Survie](#survie)
   - [Voler](#voler)

 Compétences douces, [résolution binaire](#résolution-binaire) :

   - [Connaissance de la nature](#connaissance-de-la-nature)
   - [Connaissance des secrets](#connaissance-des-secrets)
   - [Droit](#droit)
   - [Lire, écrire](#lire-écrire)
   - [Magie](#magie)
   - [Perception](#perception)
   - [Psycologie](#psycologie)

 Compétences de combat :

   - [Combat à distance](#combat-à-distance)
   - [Combat rapproché](#combat-rapproché)
   - [Esquiver](#esquiver)
   - [Parer](#parer)

## Compétences d'actions

### Artisanat, construire

Permet de fabriquer des objets manuellement, pour peu que l'on dispose du matériel et des outils nécessaires: fabriquer une épée, assembler un mécanisme, préparer un objet à recevoir une rune...

### Athlétisme

Cette compétence permet d'accomplir toutes les actions physiques, y compris la nage ou l'escalade.

### Discrétion

Utilisée lorsque vous devez vous déguiser ou vous faire oublier dans l'endroit où vous vous trouvez/rendez.
Lorsque vous disposez du matériel adéquat pour vous déguiser, vous
pouvez même prendre l'apparence de quelqu'un en particulier si vous réussissez votre jet.
Dans le cadre d'une filature ou d'une poursuite, votre **Discrétion** s'opposera à la [Perception](#perception) de votre adversaire (cf. [défenses et compétences opposées](#défenses-et-compétences-opposées)).

### Intimider

Parfois, la parole ne suffit pas et il vous faudra manier la menace, les sous-entendus et la grosse voix pour forcer votre auditoire à être d'accord avec vous. Intimider entre en jeu à ce moment-là. Votre victume utilise la [Psycologie](#psycologie) pour résister (cf. [défenses et compétences opposées](#défenses-et-compétences-opposées)).

### Magie

Tout personnage possède un potentiel magique.
La compétence Magie détermine la compétence générique d'un mage, sa puissance brute, sa capacité à apprendre ou approfondir ses compétenses dans des [domaines de magie](#domaines-de-magie). Magie sert à percevoir ou ressentir la magie ou sa présence mais ne peut pas être utilisé pour lancer des sorts sans avoir appris leur [domaine](#domaines-de-magie).

### Mentir, convaincre

Plus subtil qu'[Intimider](#intimider), cette compétence vous permet de rallier votre auditoire à votre avis. Elle est utilisée dans toutes les négociations : commerciales, politiques, en-tourloupes, etc. Votre interlocuteur ou interlocutrice utilise sa [Psychologie](#psycologie) pour ne pas se laisser faire (cf. [défenses et compétences opposées](#défenses-et-compétences-opposées)).

### Piloter

Qu'il s'agisse de monter un cheval, de conduire les étranges machines
naines, voire de mener un navire, cette compétence vous permet de diriger et/ou manœuvrer tout moyen de locomotion (animal, végétal, mécanique, autre…). La
présence de plusieurs personnes sur les grands navires est toujours nécessaire.

### Réflexes

Parfois, vous devrez être vif pour échapper à un éboulement, empêcher une
noble d'avaler un poison ou protéger un enfant d'un carreau d'arbalète. Réflexes intervient précisément à ce moment-là. Les combats exploitent aussi cette compétence pour déterminer qui agit en premier.

### Serrures et pièges

Vous permet de crocheter ou verrouiller tout type de serrure non magique et de fabriquer ou désamorcer tout type de piège mécanique.

### Survie

Mélange de sens de l'orientation, de repérage aux étoiles et de débrouillardise, cette compétence vous permet de vous accommoder des lieux que vous ne connaissez pas. Elle est notamment employée pour déterminer si vous trouvez de quoi subvenir à vos besoins en milieu sauvage.

### Voler

Compétence préférée des roublards et autre tire-laine, Voler permet au personnage de soulager un propriétaire de ses menues possessions, qu'il s'agisse d'une bourse pleine de pièces, d'une bague ou autres objets. Le MJ peut imposer un malus si l'objet à dérober est particulièrement imposant. La victime du larcin utilise sa [Perception](#perception) comme défense contre le vol (cf. [défenses et compétences opposées](#défenses-et-compétences-opposées)).

## Compétences douces

### Connaissance de la nature

Mélange de chimie et de biologie, cette compétence permet de reconnaître les éléments en extérieur, tels que les plantes et poisons, ou d'en savoir plus sur les animaux.

### Connaissance des secrets 

Donne au personnage des indices sur des éléments incompréhensibles, du ressort de la culture générale (histoire, géographie, héraldique, etc.). Peut aussi être utilisé pour en savoir plus sur la magie et sur certaines légendes.

### Droit

Vous donne accès aux usages administratifs et judiciaires des royaumes que vous traversez. Vous savez ainsi ce qui est illégal ou non et la peine encourue pour les différents crimes et délits.

### Lire, écrire

Sans cette compétence, un héros ne peut absolument rien lire, pas même un panneau indicateur. Lire un livre nécessite une demi-journée par partie distincte.

| Score | Niveau | Capacités indicatives |
| - | - | - |
| < 20 | Illettré | Ne sait pas lire ou écrire couramment. Peut reconnaître quelques symboles, noms ou mots familiers. |
| 20–39 | Rudimentaire | Peut lire des panneaux, des lettres simples et rédiger de courts messages. Lecture lente et laborieuse. |
| 40–59 | Lettré | Lit et rédige couramment. Peut consulter des ouvrages, tenir une correspondance et travailler sur des documents complexes. |
| 60–79 | Érudit | Maîtrise les subtilités de l'écrit. Peut analyser des textes anciens, reconnaître des parentés linguistiques et tenter des traductions difficiles. |
| ≥ 80 | Maître linguiste | Peut travailler sur des écritures oubliées, reconstituer des textes fragmentaires et déchiffrer certaines langues inconnues lorsque des indices suffisants existent. |

### Perception

Représente la capacité du personnage à capter et analyser rapidement les différentes informations de son environnement.

### Psycologie

Cette compétence vous permet d'avoir un aperçu des attentes des autres individus et de rester droit dans vos bottes quand on tente de vous manipuler. Elle est utilisée pour résister à [Mentir, convaincre](#mentir-convaincre) ou [Intimider](#intimider).

## Compétences de combat

### Combat à distance

Permet d’utiliser des armes à projectiles (arcs, arbalètes…) ou de lancer (couteau, bolas…). La même compétence est utilisée pour toutes les armes à distance mais le MJ
peut imposer un malus de -10 % s’il estime l’arme employée trop exotique pour le personnage.

### Combat rapproché

Permet d’utiliser les armes de corps à corps en combat, qu’elles soient à une ou deux mains. Une seule et même compétence de Combat rapproché est utilisée pour toutes les armes de corps à corps mais le MJ peut imposer un malus de -10 % s’il estime l’arme
employée trop exotique pour le personnage.

### Esquiver

Cette compétence est utilisée en combat pour éviter les différents coups
qui vous sont portés. Vous ne pouvez pas attaquer le même tour où vous esquivez.

### Parer

Intercepter ou dévier une attaque avec une arme, un bouclier ou un moyen adapté.

# Compétences spéciales

Les compétences spéciales représentent les domaines de spécialisation d'un personnage. Elles possèdent chacune leur propre score de maîtrise.

Leur apprentissage ou leur perfectionnement peut nécessiter un niveau minimum dans une ou plusieurs compétences normales.

*Exemple: un apprentissage de la Magie du feu demande une compétence de [Magie](#magie) d'au moins 30.*

Lorsqu'une action fait appel à une compétence spéciale, le jet s'effectue uniquement sur le score de cette dernière, sans effectuer de jet supplémentaire sur les compétences normales associées.

Certaines compétences normales peuvent également contribuer aux effets produits par une compétence spéciale, notamment dans le calcul des dégâts ou de la puissance.

## Apprentissage et progression des compétences spéciales

Par défaut, une compétence spéciale nouvellement apprise commence avec un score de **30**. Un tuteur peut toutefois définir directement un score d'enseignement supérieur : dans ce cas, une compétence absente est apprise à la valeur effective du tuteur.

Les compétences spéciales peuvent être apprises et perfectionnées de deux manières : grâce à un [**tuteur**](#tuteurs) ou par [**épiphanie**](#épiphanies).

### Tuteurs

Un tuteur est une source d'enseignement permettant d'apprendre ou d'améliorer une compétence normale ou spéciale. Il peut s'agir d'un professeur, d'un livre de compétences ou de toute autre source de savoir.

Chaque tuteur définit :
  - **La compétence normale ou spéciale enseignée.**
  - **Un score d'enseignement**, qui sert aussi de plafond de maîtrise.
  - **Des prérequis éventuels** : compétences normales, compétences spéciales, matériel, artefacts, consommables, paiement ou autres conditions.
  - **Une durée d'apprentissage**, généralement comprise entre un jour et une semaine.

Un tuteur peut posséder des valeurs fixes ou être une base mise à l'échelle par niveau. Pour une base calculée, le score d'enseignement et chaque minimum de compétence requis suivent séparément la formule :

```text
valeur effective = ceil(valeur de base + (niveau du tuteur − 1) × incrément par niveau)
```

Le niveau `1` restitue exactement la valeur de base et le résultat ne peut pas dépasser `100`. Le niveau `0` représente une base de tuteur non finalisée, inutilisable tant qu'un niveau jouable ne lui a pas été attribué. Une base peut limiter les niveaux auxquels un générateur est autorisé à la sélectionner. Les Items éventuellement requis ne sont jamais multipliés ni renforcés par le niveau du tuteur.

Lorsque les conditions sont réunies et que le temps nécessaire a été consacré à l'apprentissage, une compétence absente ou déjà connue progresse directement jusqu'au score effectif du tuteur. Le bonus permanent propre à la compétence reste séparé de ce score de base.

*Exemple : un traité de magie du Feu de niveau 3 possède un score de base de 35 et un incrément de 5 par niveau. Il enseigne donc Feu à 45. Son prérequis de Magie possède une base de 30 et un incrément de 2,5 : après arrondi supérieur, il exige 35 en Magie. Une potion particulière et trois jours d'étude peuvent également être demandés, sans que la potion ne scale avec le niveau.*

*Un personnage ne connaissant pas encore Feu l'apprend à 45. Un personnage possédant déjà 35 en Feu progresse jusqu'à 45. Un personnage possédant 60 en Feu n'en tire aucun bénéfice.*

### Épiphanies

Une épiphanie est une progression accordée directement par le MJ lorsqu'un événement ou les actions du personnage justifient une amélioration de sa maîtrise.

Elle peut notamment résulter d'une utilisation particulièrement ingénieuse d'une compétence, d'une expérience marquante, d'une découverte ou d'une rencontre extraordinaire.

Le MJ détermine la progression accordée selon les circonstances.

Contrairement aux tuteurs, **l'épiphanie ne nécessite ni dépense ni temps d'apprentissage supplémentaire** : le personnage a déjà acquis cette expérience au cours de l'aventure.

## Catalogue de compétences spéciales

On propose un catalogue **NON EXHAUSTIF** de compétences spéciales utilisées par les PNJ du monde :

### Artisanat et disciplines techniques

| Compétence spéciale | Prérequis d'apprentissage | Domaine d'application |
| - | - | - |
| Runologie | Connaissance des secrets ≥ 40, Artisanat, construire ≥ 30 | Étudier, concevoir et modifier les runes magiques |
| Formations magiques | Runologie ≥ 50, Connaissance des secrets ≥ 40 | Construire des réseaux d'inscriptions produisant des effets à grande échelle |
| Forgemagie | Runologie ≥ 30, Artisanat, construire ≥ 40 | Fabriquer des armes et armures enchantées par des runes |
| Ingénierie | Artisanat, construire ≥ 40 | Concevoir des mécanismes et machines complexes |


### Sciences, soins et investigation

| Compétence spéciale | Prérequis d'apprentissage | Domaine d'application |
| - | - | - |
| Dressage | Survie ≥ 40, Psychologie ≥ 30 | Éduquer, entraîner et diriger des animaux ou créatures extraordinaires |
| Alchimie | Connaissance de la nature ≥ 40, Magie ≥ 30 | Transformer et combiner des substances grâce à des procédés magiques |
| Apothicairerie | Connaissance de la nature ≥ 40 | Préparer des remèdes, poisons et antidotes |
| Médecine | 	Connaissance de la nature ≥ 40 | Diagnostiquer, traiter et opérer des patients |
| Investigation | Perception ≥ 40, Psychologie ≥ 30 | Reconstitution d'événements à partir d'indices, analyse méthodique d'une scène, recoupement de témoignages |

### Disciplines martiales

| Compétence spéciale | Prérequis d'apprentissage | Domaine d'application |
| - | - | - |
| Art de l'épée | Combat rapproché ≥ 40, Réflexes ≥ 30 | 	Maîtrise avancée du maniement de l'épée |
| Art des armes d'hast | Combat rapproché ≥ 40 | Techniques avancées de lance, hallebarde et armes apparentées |
| Art du tir | Combat à distance ≥ 40, Perception ≥ 30 | Techniques de tir exceptionnelles |
| Maîtrise corporelle | Athlétisme ≥ 40, Réflexes ≥ 30 | Développement physique, conditionnement, contrôle musculaire et exploits restant dans les limites naturelles |

### Disciplines magiques avancées

Certaines compétences spéciales permettent de prolonger une discipline ordinaire par la maîtrise de la magie.

Elles nécessitent généralement une maîtrise préalable de la discipline concernée ainsi qu'un certain niveau en [Magie](#magie).

Ces spécialisations permettent d'accomplir des actions dépassant les limites physiques naturelles, sans nécessairement relever d'un domaine de magie élémentaire ou fondamental.

*Exemple : Renforcement corporel magique*

| Compétence spéciale | Compétences associées | Domaine d'application |
| - | - | - |
| Renforcement corporel magique | Maîtrise corporelle ≥ 60, Magie ≥ 40 | Canaliser l'énergie magique dans son corps pour développer une force, une vitesse, une résistance et une mobilité surnaturelles. |

## Domaines de magie

Dans notre monde on catégorise la magie en plusieurs domaines, chaque domaine est une compétence spéciale du personnage et va régir sa capacité à executer des sorts ou manipulations **précises ou complexes** dans ce domaine.

Ces domaines ne sont pas des limites fixées à toutes les magies possibles dans notre monde.
Ce sont simplement des disciplines que les personnages peuvent apprendre ou développer *naturellement* au cours de leur aventure.
L'apprentissage des [domaines de magie](#domaines-de-magie) se fait via des professeurs, des livres de compétences, ou une épiphanie naturelle du personnage, leur maîtrise n'est pas innée.

L'apprentissage d'un domaine de magie nécessite un score d'au moins **40 en Magie**.

| Domaine | Périmètre |
| - | - |
| Feu | Produire, entretenir, déplacer ou éteindre des flammes ; manipuler la chaleur et provoquer une combustion. |
| Eau/Glace | Manipuler l'eau sous ses différentes formes, en modifier l'état, créer ou déplacer des masses d'eau et de glace. |
| Air | Manipuler les courants d'air, la pression et les mouvements de l'atmosphère. |
| Foudre | Produire, canaliser et manipuler les décharges électriques. |
| Terre | Manipuler la terre, la roche, le sable et les matières minérales naturelles. |
| Télékinésie | Exercer des forces à distance sur la matière inerte afin de la déplacer, la maintenir ou la manipuler sans contact. Ne permet pas d'exercer directement une force sur les êtres vivants. |
| Esprit | Développer et projeter sa conscience au-delà des limites du corps, percevoir l'environnement par le sens spirituel et établir des connexions avec certains objets magiques. La perception spirituelle traverse les obstacles physiques ordinaires, mais peut être bloquée par des formations, interdictions ou matériaux particuliers. |
| Espace | Manipuler les distances, les positions et les relations spatiales, permettant notamment des déplacements instantanés ou des distorsions de l'espace. |
| Temps | Percevoir ou modifier l'écoulement du temps, sa vitesse et éventuellement certaines relations temporelles entre les événements. |
| Mort | Pratiquer la nécromancie, animer et contrôler les dépouilles, infliger des malédictions et manipuler les âmes des défunts, notamment pour les emprisonner, les asservir ou exploiter leur énergie spirituelle. |

### Exemples de niveaux de maîtrise

> Les exemples suivants donnent des ordres de grandeur pour évaluer la maîtrise d'un domaine magique. Ils ne constituent ni une liste exhaustive de sorts ni des seuils de déblocage stricts. La faisabilité d'une manipulation dépend également de sa portée, de sa précision, de son intensité et des circonstances.

| Maîtrise | Feu | Télékinésie | Mort |
| - | - | - | - |
| 30-39 | Allumer une bougie ou produire une petite flamme| Déplacer un petit objet à quelques mètres, avec un contrôle assez rudimentaire | Animer de petits restes organiques, percevoir des traces de nécromancie ou des résidus d'âmes |
| 40-59 | Produire et diriger un jet de flammes | Manipuler plusieurs petits objets simultanément à une dizaine de mètres, ou déplacer un objet lourd | Réanimer un cadavre et lui donner des ordres simples, lancer des malédictions mineures, capturer de faibles résidus spirituels |
| 60-79 | Provoquer un incendie localisé et en contrôler la propagation | Contrôler précisément une dizaine d'objets à plusieurs dizaines de mètres, ou soulever une carriole | Contrôler plusieurs morts-vivants, infliger des malédictions persistantes, capturer et asservir des âmes dépouillées de leur conscience |
| 80-89 | Produire un brasier capable de ravager un bâtiment| Manipuler des dizaines d'objets indépendamment, à plusieurs centaines de mètres, ou soulever une masse considérable | Créer des serviteurs nécromantiques puissants et partiellement autonomes, infliger des malédictions difficiles à lever, emprisonner et exploiter des âmes puissantes |
| 90-100 | Déchaîner un incendie dévastateur à l'échelle d'un quartier | Contrôler simultanément des centaines d'objets sur une zone immense, ou déplacer des structures monumentales | Lever une armée de morts-vivants, imposer des malédictions dévastatrices sur une communauté entière ou asservir des légions d'âmes pour alimenter des rituels extraordinaires |

# Résolution des actions

Quand un personnage entreprend une action sa résolution dépend des [compétences](#compétences) ou [compétences spéciales](#compétences-spéciales) impliquées. 

> **Un jet de dés est nécessaire que lorsque le MJ considère que la réussite n'est pas triviale**.

Les lancés de dés sont des jets de *1d100*. Le jet est considéré comme réussi quand le résultat est **inférieur ou égal** au score de la compétence éprouvée. Le MJ peut attribuer des bonus ou malus (+- 10, 20...) pour que la difficulté du jet corresponde mieux à l'action entreprise.
 
En fonction de la compétence ciblée on propose deux façons de résolution : 

- la [résolution d'action normale](#résolution-daction) pour les actions qui affectent directement le monde extérieur
- la [résolution binaire](#résolution-binaire) pour les autres

## Résolution d'action

Une action est une tentative d'influer sur le monde extérieur, elles peuvent réussir **complètement**, **partiellement**, ou **échouer**.

On propose un arbre de résolution pour s'assurer que l'action du personnage soit résolue de manière **logique** et en faisant **progresser la scène**.


> 1. Est ce que l'action est possible pour le personnage et ou les PNJ intervenants ? 
> 
>   - Oui --> Proceed au 2.
>   - Non --> Succès impossible, pas de roll de dés, résolution narrative selon l'action.
> 
> 2. Est ce que l'action est facilement réalisable par le PJ dans la situation où il se trouve ?
> 
>   - Oui --> Succès automatique, pas besoin de roll.
>   - Non --> Proceed au 3.
> 
> 3. Est ce que des complications ou conséquences logiques peuvent s'appliquer en cas d'échec ?
> 
>  - Oui --> On roll le skill impliqué du PJ en applicant des bonus ou malus sur le seuil de réussite.
>  - Non --> Dans ce cas le PJ réussi sans roll de dés.
> 
> 4. Est ce que le roll passe ?
> 
> Un roll est un d100 contre la compétence du PJ +- les modificateurs de difficulté du roll.
> 
>  - Un succès simple est un résultat **inférieur ou égal** à ce seuil.
>  - Un succès **partiel ou mitigé** est un résultat **inférieur ou égal à deux fois ce seuil**.
>  - Un **échec** ou **succès difficile** est un résultat **au dessus de deux fois ce seuil**.


Les conséquences moyennes ou lourdes sont **à la discrétion du MJ** du moment qu'elles sont **logiques** par rapport à la situation et qu'elles font **avancer la scène** en cas d'échec.

> **L'échec narratif est une explication de pourquoi le personnage ne peut plus réussir son action.**

## Résolution binaire

Certaines compétences ne proposent pas narativement de compromis intéressant, elles sont résolues par un roll de d100 sous le seuil de la compétence. Un succès est un jet inférieur ou égal à la compétence après l'application des modificateurs de difficulté.

## Défenses et compétences opposées

Certaines actions peuvent être résitées par leur compétences opposées : 

- [Voler](#voler), [Discrétion](#discrétion) | [Perception](#perception)
- [Intimider](#indimider), [Mentir, convaincre](#mentir-convaincre) | [Psycologie](#psycologie)

Lors de ces confrontations la compétence opposée va ajouter un modificateur de difficulté sur le jet offensif en suivant cette règle :

| Compétence défensive de la cible | Malus au jet de l'attaquant |
| - | - |
| < 30 | Aucun |
| 30-59 | −10 |
| 60-79 | −20 |
| ≥ 80 | −30 |


*Exemple:*

*Alice cherche à voler la bourse d'un marchand dans la foule. Sa compétence de Vol est de 65, et le marchand possède 40 en Perception.
Le MJ considère que les circonstances du vol le rendent plus facile et accorde un bonus de 10% au jet. La Perception du marchand ajoute un malus de 10%, le jet devient un simple lancé de d100 avec une [résolution normale d'action](#résolution-daction).*

# TLDR combat

  - Moi attaque. Moi touche.
  - Ennemi esquive ou pare ? Lui lance dé.
  - Lui réussit ? Moi rate. Lui échoue ? Moi tape.
  - Beaucoup ennemis taper moi ? Moi malus esquive ou parade.
  - Initiative = d100 + Réflexes

# Combat

Le combat repose sur un principe simple : une attaque réalisable touche sa cible, sauf si celle-ci parvient à se défendre.

Contrairement aux actions ordinaires, l'attaquant n'effectue donc pas de jet pour déterminer s'il touche. Les jets sont effectués par les défenseurs lorsqu'ils tentent d'éviter une attaque.

## Initiative 

Au début d'un combat les intervenants vont lancer l'initiative pour déterminer l'ordre de jeu.

`Initiative = 1d100 + Réflexes`

Le plus grand chiffre joue en premier, en cas d'égalité priorité aux joueurs.

## Résolution d'une attaque

1. Déclaration de l'attaque : l'attaquant choisit sa cible et son action. Le MJ vérifie que l'attaque est réalisable compte tenu de la portée, de la position et des circonstances.
2. Effets préalables : les éventuels effets On Action sont appliqués avant la défense.
3. Défense réactive : si elle en a la possibilité, la cible tente une Parade ou une Esquive.
4. Résolution : si la défense réussit, l'attaque est annulée. Sinon, elle touche et ses dégâts et effets à l'impact sont appliqués.

Une cible incapable de se défendre est touchée automatiquement.

## Parade et Esquive

Les personnages disposent de deux compétences défensives :

| Compétence | Utilisation |
| - | - |
| Parer | Intercepter ou dévier une attaque avec une arme, un bouclier ou un moyen adapté. |
| Esquiver | Éviter physiquement une attaque en se déplaçant. |

La Parade peut être utilisée contre des attaques au corps à corps comme à distance, à condition de disposer d'un moyen crédible de les intercepter.

L'Esquive peut être utilisée contre toute attaque physiquement évitable, mais subit un malus important au corps à corps.

*Exemple : Une flèche peut être esquivée ou interceptée par un bouclier adapté, tandis qu'une boule de feu doit généralement être esquivée, sauf protection particulière.*

### Modificateurs défensifs

Le score offensif de l'attaquant impose un malus au jet défensif. L'Esquive subit également un malus important lorsqu'elle est utilisée contre une attaque au corps à corps.

| Compétence offensive | Malus défensif |
| - | - |
| 0-29 | 0 |
| 30-59 | −10 |
| 60-79 | −20 |
| 80-100 | −30 |

L'Esquive subit un malus supplémentaire de −20 contre les attaques au corps à corps.

Lorsqu'un personnage tente plusieurs défenses au cours d'un même tour, chaque défense après la première subit un malus cumulatif de −10. Ce malus est réinitialisé au début du tour suivant.

Tous les malus applicables se cumulent.

Le défenseur effectue un unique jet de d100 :
  - **Résultat inférieur ou égal à la compétence défensive modifiée** : l'attaque est annulée.
  - **Résultat supérieur** : la défense échoue et l'attaque touche.


## TLDR Dégats

 - Arme fait dégâts.
 - Moi fort en compétence ? Arme tape plus fort (vraiment).
 - Arme magique ? Peut faire dégâts bonus.
 - Dégâts bonus sur effet d'arme viennent de l'arme, pas de moi.
 - Dés sur arme faire 25% des dégats.
  
## Dégâts et résistances

### Types de dégâts

Il existe deux types de dégâts :

- **Physiques**
- **Magiques**

Chaque attaque peut infliger une ou plusieurs lignes de dégâts, chacune possédant son propre type et sa propre valeur.

### Calcul des dégâts

Chaque arme ou attaque magique possède une formule de dégâts de base, composée de dés et d'une valeur fixe, par exemple `2d8+27`.

Les dégâts principaux sont amplifiés par les compétences du personnage selon la formule :

`Dégâts bruts = Dégâts de base × (1 + 2 × (Compétence normale + Compétence spéciale) / 100)`

- **Dégâts de base** : résultat de la formule de dégâts de l'arme ou de l'attaque.
- **Compétence normale** : compétence normale utilisée pour l'attaque.
- **Compétence spéciale** : compétence spéciale associée à l'attaque, ou 0 si le personnage ne la possède pas.

Pour une attaque physique, on utilise **Combat rapproché** ou **Combat à distance**, ainsi que l'éventuelle discipline martiale correspondante.

Pour une attaque magique, on utilise **Magie** et le domaine magique concerné.

Les armes sont généralement conçues pour qu'environ **25 % de leurs dégâts moyens proviennent des dés et 75 % d'une valeur fixe**.

### TLDR Résitances

- Deux types : physique et magique.
- Résistance % réduit dégâts d'abord.
- Résistance fixe enlève dégâts ensuite.
- Plusieurs lignes de dégâts ? Résistance appliquée à chaque ligne séparément.

### Résistances

Chaque personnage possède quatre valeurs de résistance :

| Résistance | Fonction |
| - | - |
| Physique (%) | Réduction proportionnelle des dégâts physiques |
| Physique fixe | Réduction fixe des dégâts physiques |
| Magique (%) | Réduction proportionnelle des dégâts magiques |
| Magique fixe | Réduction fixe des dégâts magiques |

Pour chaque ligne de dégâts, on applique d'abord la résistance en pourcentage, puis la résistance fixe correspondante :

`Dégâts reçus = max(0, Dégâts bruts × (1 - Résistance % / 100) - Résistance fixe)`

Les dégâts reçus ne peuvent pas être négatifs.

### Attaques à plusieurs lignes

Lorsqu'une attaque inflige plusieurs lignes de dégâts, **chaque ligne est réduite indépendamment** par les résistances de son type.

Les dégâts restants sont ensuite additionnés pour obtenir les dégâts totaux subis.

*Exemple :* Une épée enchantée inflige 100 dégâts physiques et 40 dégâts magiques.

La cible possède :
- 20 % de résistance physique et 15 de résistance physique fixe ;
- 25 % de résistance magique et 10 de résistance magique fixe.

La ligne physique inflige : `100 × 0,80 - 15 = 65`.

La ligne magique inflige : `40 × 0,75 - 10 = 20`.

**Total : 85 dégâts reçus.**

### Effets additionnels des armes

Certaines armes disposent d'effets supplémentaires déclenchés lorsqu'une attaque touche (*On Hit*).

Ces effets peuvent notamment ajouter des lignes de dégâts physiques ou magiques.

Contrairement aux dégâts principaux de l'attaque, **les lignes de dégâts additionnelles provenant de l'objet ne sont pas amplifiées par les compétences du personnage**.

Elles sont néanmoins soumises aux résistances habituelles, indépendamment des autres lignes de dégâts.

## Magie persistante en combat

Certains effets magiques nécessitent une concentration continue pour être maintenus, comme la manipulation d'objets par Télékinésie.

D'autres effets peuvent persister naturellement après leur création, comme une brume ou un incendie. Ceux-ci ne nécessitent pas de concentration.

### Maintien de la concentration

Lorsqu'un personnage maintenant un sort subit une attaque qui le touche, il doit effectuer un jet de concentration pour maintenir son effet.

Ce jet utilise directement la compétence spéciale du domaine magique concerné.

La compétence offensive de l'attaquant impose un malus selon les mêmes paliers que les défenses :

| Compétence offensive | Malus de concentration |
| - | - |
| 0–29 | 0 |
| 30–59 | −10 |
| 60–79 | −20 |
