# Création de personnage


Chaque joueur doit faire les 3 choix suivant pour creer son personnage:

- 12 points à distribuer dans les différentes caractéristiques 
- 1 Archétype
- 1 Talent


Description des statistiques
---

##### Points de vie

Le nombre de points de dégat total qu'un ennemi doit infliger pour que le joueur tombe au combat. Chaque point de dégat encaissé réduit le total de points de vie de 1. Lorsque le nombre de points de vies est inférieur ou égal à 0, le joueur tombe au combat.

##### Points d'action

Le nombre d'actions maximal qu'un joueur peut effectuer dans un même tour.

##### Relances

Le nombre total de relances de dés avec lequel le joueur commence un combat. Une relance peut être utilisé à chaque fois qu'un dé est lancé pour rejouer le dé et changer sa valeur immédiatement. Chaque utilisation d'une relance reduit son total de relances par 1. Lorsque le total de relance est à 0, il n'est plus possible de rejouer le dé.

##### Points de mouvements

Le nombre total de déplacements qu'un joueur peut faire lors d'un tour. Un déplacement correspond à se déplacer sur une case adjacente sur la grille de jeu.

##### Précision

La précision dicte la difficulté à toucher une cible au combat. Avec une précison nulle (0) il est impossible de toucher une cible. Chaque points en précision augmente le nombre de faces du dé qui correspondent à un succès, i.e une cible atteinte. Par exemple, un joueur avec 5 de précision possède 5 faces succès (20, 19, 18, 17, 16) et 15 faces d'échec (toutes les faces inférieures à 16).

#### Statistiques de base

Le tableau suivant indique la valeur maximale de base pour chacune des statistiques du joueur.

| Statistique          | Valeur |
|----------------------|--------|
| Points de vie        | 10     |
| Points d'action      | 3      |
| Relances             | 1      |
| Points de mouvement  | 3      |
| Précision            | 7      |

Possessions de départ
---

- Commence avec 10 $
- Une arme à distance (Choix entre : Colt 45, Revolver)
- Une arme de melee (Baton, couteau)
- 2 chargeur remplis (6 balles chacun)
- Un medkit

Caratéristiques
---

Les valeurs d'une caractéristique ne peut qu'être comprise en 0 et 10. Chaque points investi caractéristique réduit la difficulté des tests d'abilité (voir la section sur les tests d'abilité). Voici les avantages que chaque caractéristique confère.

##### Force (STR)

- Augmente de 1 le nombre de dégats infligés pour chacune attaque au corps à corps effectué pour chaque point attribué

##### Perception (PER)

- Augmente de (PER // 2) la précision du joueur

##### Endurance (END)

- Augmente de 1 le maximum total de points de vie pour chaque point attribué
- Augmente de (END // 3) les points de mouvement 

##### Charisme (CHR)

- Réduit la valeur de 1$ pour l'achat d'un objet pour chaque point attribué (pour un minimum possible de 1$ par objet)
- Chaque marchant rencontré offre (1 + CHR // 2) balles ou (CHR // 5)$ gratuitement
- Augmente la valeur de revente de chaque objet possédé

##### Intelligence (INT)

- Augmente de 1 le nombre de dégats infligé par les explosifs pour chaque point attribué 

##### Agilité (AGI)

- Augmente de 1 le nombre de dégats infligé par les armes à distance pour chaque point attribué 

##### Chance (LCK)

- Augmente de (LCK // 2) le nombre maximal de relances du joueur

Archétypes
---

Un archétype offre l'option d'une action spéciale exclusive utilisable une seule fois par tour (sauf si contre-indiqué).

##### Bouncer

L'action spéciale:
- Provoque la reduction de 1 + (END // 4) des dégats infligés par les ennemis jusqu'au prochain tour du joueur 
- Force les ennemis à 1 + (CHR // 3)  cases ou moins de distance d'engager le joueur si possible

##### Boxer

Le boxeur doit avoir les deux mains vide pour pouvoir utiliser son action spéciale.

L'action spéciale:
- Attaque 2 + (STR // 4) fois une cible à portée avec les poings.

##### Brawler

Le brawler peut toujours, avec une action, choisir d'attaquer avec deux armes au corps à corps, à une main et équipées, par ailleurs les deux attaques doivent toucher leur cible pour que l'ennemi ciblé se fasse infliger des points de dégat.

L'action spéciale:
- Attaque 2 fois en tout avec n'importe quelle combinaison d'armes au corps à corps, à une main et équipées sans engager les armes utilisés ainsi. Si les deux attaques ainsi effectuées touchent la cible, alors une troisième attaque avec une arme au corps à corps, à une main et équipées est possible toujours sans engager l'arme utilisé

##### Bully

L'action spéciale:
- Rend 1 + (CHR // 6) cibles pacifique et immobile dans un rayon de 1 + (CHR // 2) cases jusqu'au prochain tour du bully. Les alliés dans un rayon de 1 + (CHR // 3) cases augmentent leur précision de 1 + (CHR // 4) contre les cibles ennemis atteintes par l'action spéciale du bully.


##### Card Dealer

Le card dealer n'a pas d'action spéciale. À la place, au début de son tour, le joueur decide s'il souhaite lancer un dé 8. S'il décide de le faire, en fonction du résultat, le card dealer obtient le bonus/malus ci-dessous pour le tour actif. Les relances sont possible pour ce dé.

1. Réduit le total de points d'action disponibles de 1
2. Réduit de 3 - (LCK // 4) les points de dégats infligés pour chacune des attaques
3. Augmente la précision du joueur de 2 + (LCK // 3)
4. Restore soi-même de 2 + (LCK // 3) points de vie
5. Augmente de 2 + (LCK // 4) maximum points de mouvements
6. Augmente de 1 + (LCK // 3) les points de dégats infligés par les armes au corps à corps et aux poings
7. Augmente de 1 + (LCK // 3) les points de dégats infligés par les armes à distance
8. Augmente le total de points d'action disponibles de 1 et augmente de 1 + (LCK // 4) les points de dégats infligés par les explosifs

##### Cowboy

Le cowboy peut se déséquiper d'une arme à une main et équiper l'autre main d'une autre arme à une main en une seule action plutôt que 2. Le cowboy doit avoir une main vide pour pouvoir utiliser son action spéciale.

L'action spéciale:
- Attaque une même cible avec une arme à une main ayant un barillet jusqu'à 2 + (AGI // 4) fois ou jusqu'à ce que le chargeur soit vide. Chaque attaque ainsi faite a un malus de 6 - (PER // 3) de précision

##### Leader

L'action spéciale:
- Donne une action standard à 1 + (CHR // 6) joueurs dans un rayon de 1 + (CHR // 2) cases

##### Medic

L'action spéciale:
- Stabiliser un allié
- Donner 1 + (INT // 2) points de vie a cet allié

ou

- Convertir un medkit en pistolet regénérateur
- Tirer le pistolet sur une cible allié. Un jet de précision est nécessaire pour atteindre la cible
- Une cible atteinte regagne les points de vie donné par un un medkit standard + (1 + INT // 2) points de vie

##### Professional Pitcher

L'action spéciale:
- Équipe jusqu'à un objet dans chaque main libre
- Lance un objet avec une portée accrue de 1 + (LCK // 3) cases

##### Pistolero

Le pistolero peut toujours, avec une action, choisir d'attaquer avec deux armes à distance, à une main et équipées, par ailleurs les deux attaques doivent toucher leur cible pour que l'ennemi ciblé se fasse infliger des points de dégat.

L'action spéciale:
- Attaque 2 fois en tout avec n'importe quelle combinaison d'armes à distance, à une main et équipées sans engager les armes utilisés ainsi. Si les deux attaques ainsi effectuées touchent la cible, alors une troisième attaque avec une arme à distance, à une main et équipées est possible toujours sans engager l'arme utilisé

##### Rogue

Le rogue doit ne pas être engagé et ne doit pas avoir l'aggro pour pouvoir utiliser son action spéciale.

L'action spéciale:
- Permet de bouger de 2 + (END // 4) cases vers un ennemi immédiatemment
- Attaque avec une arme de corps à corps un ennemi à portée et assure un coup critique de l'attaque si cette dernière touche la cible

##### Rummager

Hors combat, le rummager peut faire l'action de fouiller jusqu'à 1 + (LCK // 2) fois entre chaque repos court au lieu d'une seule. 

L'action spéciale:
- Fait l'action de fouiller durant le combat à condition d'être à couvert.

ou

- Permet de fabriquer une grenade improvisée. La grenade improvisée coûte 10 - (INT // 3) balles pour être construite et inflige le même nombre de points de dégat qu'une dynamite standard. 

##### Sniper

Le sniper doit ne pas être engagé et ne doit pas avoir l'aggro pour pouvoir utiliser son action spéciale.

L'action spéciale:
- Attaque avec une arme à un coup (Single shot) et donne un bonus de 1 + (PER // 4) de précision temporaire pour l'attaque et assure un coup critique de l'attaque si cette dernière touche la cible

##### Spy

L'action spéciale:
- Provoque la perte de l'engagement des ennemis adjacents
- Donne une action de mouvement gratuite immédiatemment, i.e. le joueur peut bouger de 3 + (END // 3) cases.
- Provoque perte du l'aggro pour le tour
- Rend la prochaine attaque est silencieuse, i.e. ne provoque pas l'aggro des ennemis

Talents
---

##### Retaliator

La première fois qu'un joueur se fait attaquer par un ennemi engagé, il peut effectuer une contre-attaque avec une arme au corps à corps disponible même si l'arme est engagée ou avec son poing s'il est disponible.

##### Opportunist

Lorsque qu'un ennemi se désengage du joueur, ce dernier peut faire une action d'attaque avec une arme au corps à corps disponible même si l'arme est engagée ou avec son poing s'il est disponible.

##### Maniac

Lorsqu'un joueur attaque avec une arme au corps à corps à 2 mains, Il peut attaquer jusqu'à 1 + (STR // 4) cibles supplémentaires à portée.

##### Strategist

Lorsqu'un joueur terminer son tour avec au moins 1 points d'action disponible et n'avait pas déjà de point d'action supplémentaire ce tour-ci, à son prochain tour, il aura 2 points d'action supplémentaires disponibles.

##### Fast Fingers

Lorsqu'un chargeur ou barillet est vide, permet de faire une action de recharge gratuite immédiatemment.

##### Eagle Eye

Les attaques à 5 case de distance ou plus on 2 + (PER // 3) de precision et rend l'ennemi atteint déstabilisé (perd des stats)

##### Rocket Scientist

Augmente le rayon d'impact des explosifs de 1 + (INT // 4). Le joueurs et tous les alliés sont immunisés au explosifs durant le tour du joueur. Lorsque le joueur obtient un ou des explosifs, le joueur en reçoit le double à la place.

##### Short Sighted

Les armes à distance peuvent atteindre les cibles ennemies adjacentes. Lorsque le joueur cible un ennemi avec une arme à distance dans un rayon de 2 + (PER // 4) cases ou moins, il peut attaquer immédiatemment une cible à portée. 

##### Loot Goblin

Permet de effectué un piller 1 + (LCK // 4) fois supplémentaire lors d'une pille.

##### Party Animal

Les bonus obtenus par les boissons et drogues consommés ou offert à un allié sont doublés. Lorsqu'une boisson ou drogue est obtenu, le joueur en reçoit le double à la place.

##### Overconfident

Permet de porter n'importe quel arme dans une seule main. si l'arme nécessite 2 main normalement, la précision de l'arme est réduite de 5 - (PER // 4).

##### Dual Wielder

Chaque action de recharge en effectue une pour chaque arme équipée. Une action d'attaque est suffisante pour attaquer avec chaque arme équipée.

##### Skillful

Lorsqu'un joueur attaque avec deux types d'armes différentes dans un même tour (Pour rappel, les types d'armes sont: corps à corps, à distance et explosifs), le joueur obtient une action supplémentaire ce tour-ci et le joueur inflige 1 + (LCK // 3) sur les types encore inutilisé ce tour-ci. 

##### Clumsy 

Lorsqu'un jet de dé cause le joueur à raté la cible. Si le résultat du dé est pair, le joueur obtient 1 + (LCK // 4) relances ou jusqu'à ce que son maximum de relances soit atteint.

##### Sleight of Hands 

Il est possible pour le joueur de déséquiper et équiper une arme pour une action au lieu de 2.

##### Informant

Lorsqu'un allié devient adjacent au joueur du le tour de ce dernier, l'allié gagne 1 + (CHR // 6) points de mouvement supplémentaire à son prochain tour et inflige 1 + (CHR // 3) dégats supplémentaires sur sa prochaine attaque.

##### Silent

Lorsque le joueur n'a pas l'aggro, les attaques silencieuses inflige le double de dégats.

##### Secourist

Lorsqu'un allié a moins de la moitié de son maximum de points de vie, le joueur obtient 2 + (END // 3) points de mouvements supplémentaires et gagne \[2 + PER // 3\] précision pour le tour. Les effets des medkits sont doublés. Le prochain medkit perdu n'est pas retiré de l'inventaire.

##### Lucky Bastard

Le nombre de faces sur le dé provoquants un coups critiques est augmenté de 1 + (LCK // 6). Par exemple, avec 7 points de caractéristique en chance, les coups critiques sont provoqué avec les faces 18, 19 et 20. 

##### Quick Pocket

Le joueur obtient une main supplémentaire utilisable exclusivement pour lancer des objets. Cette main supplémentaire ne peut pas équiper d'arme. Cette main peut équiper un explosif. Le joueur peut effectuer gratuitement jusqu'à une action par tour parmi les choix suivant:
- Utiliser un objet consommable sur soi-même
- Utiliser un objet consommable sur un allié adjacent
- Donner un objet à un allié adjacent

# Règles

Hors combat
---

### Tests d'abilité (skill check)

Le DM peut être amené à demander à un joueur de faire un test d'abilité dépendant de l'action du joueur. Le DM choisit la charactéristique qui sera testé et la difficulté du test. Voici une charte du résultat minimal nécessaire en fonction de la difficulté du test:

| Difficulté | Minimum requis |
|------------|----------------|
| Facile     | 6              |
| Moyen      | 11             |
| Difficile  | 16             |
| Impossible | 20             |

Le résultat minimal nécessaire du dé est reduit selon les points investi d'un joueur dans une charactéristique. La réduction du minimum requis du dé varie selon la formule suivante \[ Caractéristique // 4 \]. Par exemple, si le DM choisit un test de force avec une difficulté moyenne et le joueur a 6 point en force alors le minimum requis pour ce test sera $ 11 - \floor{ STR / 4 } = 11 - 1 = 10 $. Un test impossible ne peut pas être réduit.

Short rest : Récupère 3 pts de vie (Repos court seulement disponible 1 fois après combat)
Long rest : Récupère 10 pts de vie (Repos long seulement disponible au motel)

 Une fois par repos court:
Rummage: Permet de découvrir des objets communs (balles, medkit, etc.) si caisses, boites, etc. proches
01-02 : 1 x balle
03-04 : 2 x balles
05-06 : 3 x balles
07-08 : 1 x Shell
09-10 : ammo pack
11-12 : medkit
13-14 : 1 x Long ammo
15-16 : 1 x Carreau ou fleche
17-18 : 1 dollar
19-20 : 3 dollar
Échange entre joueur
 Une fois par repos long:
Permet de recharger toutes ses arme et clips
Changer ses équipements

Type de damage:
Piercing (balle, lance, etc.)
Bludgeoning (Baton, crowbar, etc.)
Slashing ( couteau, machete, etc. )
Impact (explosifs)

Range:
Précision standard:
Pistolet : 5 cases
Shotgun : 2 cases (dmg range, mais peut etre utiliser en melee/cohésion)
Melee : 1 case
Rifle : 9 cases
Crossbow : 6 cases
Scope : Infini cases
Lancer : 4 case + Force modifier - Over range ne s'applique pas
Over range :
+1 case : Précision nécessaire + 5
+2 cases : Précision nécessaire + 8
+3 : Impossible

Aggro
Lorsqu'un personne bouge 2 case ou +, tire, attaque en melee ou est en cohésion avec un ennemi, elle gagne un token d'aggro
Si une personne ne bouge pas ou 1 case max, tire pas, attaque pas en melee, n'est pas en cohésion avec un ennemi et n'est pas en vue, elle perd son token d'aggro
Les ennemies vont favoriser les joueurs avec un token d'aggro pour ensuite aller vers les joueurs sans token si plus aucun joueur en a.

Intiative
Un joueur dans le combat (+ agilité) VS le DM lance un dé 20 et le plus haut commence le tour

Cohésion
Doit utiliser 1 action pour sortir de la cohésion  ; x > 10 pour succès
Cohésion avec ennemi - Ne peux plus attaquer avec des armes de range
Cohésion avec allié - Peux healer et échanger des objets

Vente d'objets
(Cout de l'objet / 2)

Level up
Gagne 5 pts de caractéristique

Combat

 Règle implicite:
2 joueurs ne peuvent pas occupé la même espace
Les joueurs peuvent tiré a traver les autres joueur, mais pas les ennemies
Si un joueur tire un ennemi qui est en cohésion avec un allié, + 5 de précision nécessaire
Lorsqu'un joueur perd tout ses point de vie, il tombe en état critique. Le joueur doit lancer x > 15 pour se relever. Un allié stabilisé revient avec 1 pts de vie (3 chances, 1 par tour)

 Déroulement:
Untap phase (untap armes ou objets tapped)
Action possible (1 action parmi ceux-ci = 1 action): :
Attaquer : Utilise une arme équiper
Coup de poings
Tap l'arme
Utilise le nombre d'action inscrit sur l'arme
Jet de dé pour précision (s'applique au melee et range) = x > 13 pour succés (1 == Toujours raté) (20 == Double dmg)
Recharger
Si arme de type revolver : 2 + (LCK // 4) balles recharger = 1 action
Cependant, le revolver peut utiliser 1 action pour choisir la balle dans le baril
Si arme de type Colt : 1 clip = 1 action, Cependant :
Si le clip est vide, 1 action = 2 + (LCK // 4) balle recharger dans le clip
Bouger : permet d'utiliser tout sont mouvement ou partiellement
Équiper ou déséquiper une arme
Utiliser un objet de son sac (Utilise le nombre d'action inscrit sur l'objet)
Sortir du melee/cohésion = x > 10 pour succès
Stabiliser un allié (relève automatiquement un allié à 1 pts de vie)
Échéanger des items avec un allié en cohésion
Action contextuel ( incluant la créativité du joueur )
perdre l'aggro
desengager 1 fois par tour
lancer un objet
consommer un objet
Faire consommer un objet en sa possession à un allié adjacent
donner un objet a un allié adjacent
prendre un objet a un allié adjacent

Loot
Container commun:
01-02 : Rien
03-04 : 1 x shell
05-06 : 1 x long ammo
07-08 : 2 x balles
09-10 : Ammo pack au choix
11-12 : medkit
13-14 : 2 x shell
15-16 : 2$
17-18 : 1 x Carreau ou fleche
19-20 : Objet commun

Container uncommun:
01-02 : Rien
03-04 : 5 x shell
05-06 : 5 x long ammo
07-08 : 10 x balles
09-10 : 5 x Ammo pack au choix
11-12 : 2 x medkit
13-14 : 10 x shell
15-16 : 10$
17-18 : 5 x Carreau ou fleche
19-20 : Objet uncommun

=============================================

Ennemi commun (1 dé par ennemi) :
01-02 : 1 x balle
03-04 : 2 x balles + 1$
05-06 : 3 x balles + 2$
07-08 : 1 balles + 1$
09-10 : Ammo pack au choix
11-12 : medkit
13-14 : 1 x Long ammo + 1$
15-16 : 1 x Carreau ou fleche
17-18 : Objet commun
19-20 : Objet uncommun

Ennemi uncommun (chaque joueur lance 1 dé) :
01-02 : 5 x balle + 3$
03-04 : 6 x balles + 4$
05-06 : 7 x balles + 5$
07-08 : 3 balles + 4$
09-10 : 3 x Ammo pack au choix + 4$
11-12 : 10 $
13-14 : 3 x Long ammo + 1$
15-16 : 4 x Carreau ou fleche + 3$
17-18 : Objet uncommun + 10$
19-20 : Objet rare + 15$

