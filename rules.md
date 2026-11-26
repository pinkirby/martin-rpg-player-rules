# Création de personnage

> **Notation mathématique :** L'opérateur `//` désigne la **division entière** (arrondie vers l'infini négatif, comme en programmation / floor(a / b)). Par exemple, 7 // 2 = 3.

Chaque joueur doit faire les **3 choix** suivants pour créer son personnage :

- **12 points** à distribuer dans les différentes caractéristiques
- **1 Archétype**
- **1 Talent**

---

## Description des statistiques

| Statistique | Description |
| :--- | :--- |
| **Points de vie** | Nombre de points de dégâts total qu'un ennemi doit infliger pour que le joueur tombe au combat. Chaque point de dégât encaissé réduit le total de points de vie de 1. À 0 point de vie ou moins, le joueur tombe au combat. |
| **Points d'action** | Nombre d'actions maximal qu'un joueur peut effectuer dans un même tour. |
| **Relances** | Nombre total de relances de dés avec lequel le joueur commence un combat. Utilisable à chaque jet de dé pour rejouer et changer sa valeur immédiatement (réduit le total de 1 ; impossible à 0). |
| **Points de mouvement** | Nombre total de déplacements qu'un joueur peut faire lors d'un tour. Un déplacement correspond à se déplacer sur une case adjacente sur la grille de jeu. |
| **Précision** | Dicte la difficulté à toucher une cible au combat. À 0, il est impossible de toucher une cible. Chaque point de précision correspond au nombre de faces du dé (d20) menant à un succès en partant du 20 vers le bas (ex. : 5 de précision = 5 faces : 20, 19, 18, 17, 16 en succès et moins de 16 en échec ; 7 de base = 7 faces : 14 à 20). |

### Statistiques de base

Valeur maximale de base pour chacune des statistiques du joueur :

| Statistique | Valeur |
| :--- | :---: |
| Points de vie | 30 |
| Points d'action | 3 |
| Relances | 1 |
| Points de mouvement | 3 |
| Précision | 7 |

---

## Possessions de départ

- **20 $**
- **1 arme à distance** (au choix : Colt 45, Revolver)
- **1 arme de mêlée** (au choix : Bâton, Couteau)
- **3 chargeurs remplis** (6 balles chacun)
- **1 Medkit**

---

## Caractéristiques

Les valeurs d'une caractéristique sont comprises entre **0 et 10**. Chaque point investi dans une caractéristique réduit la difficulté des tests d'habileté (voir la section *Tests d'habileté*).

| Caractéristique | Abréviation | Effets et bonus |
| :--- | :---: | :--- |
| **Force** | **STR** | +1 dégât par attaque au corps à corps par tranche de 3 points attribués (`STR // 3`). |
| **Perception** | **PER** | Augmente la précision du joueur de `PER // 2`. |
| **Endurance** | **END** | +1 maximum de points de vie par point attribué ; augmente les points de mouvement de `END // 3`. |
| **Charisme** | **CHR** | Réduit le coût d'achat d'un objet de 1 $ par point (minimum 1 $ par objet) ; chaque marchand rencontré offre `1 + (CHR // 2)` balles ou `(CHR // 4)` $ gratuitement ; augmente la valeur de revente de chaque objet possédé. |
| **Intelligence** | **INT** | +1 dégât infligé par les explosifs par tranche de 3 points attribués (`INT // 3`). |
| **Agilité** | **AGI** | +1 dégât infligé par les armes à distance par tranche de 3 points attribués (`AGI // 3`). |
| **Chance** | **LCK** | Augmente le nombre maximal de relances du joueur de `LCK // 2`. |

---

## Archétypes

Un archétype offre l'option d'une action spéciale exclusive utilisable **une seule fois par tour** (sauf indication contraire).

### Bouncer
- **Action spéciale :**
  - Réduit de `1 + (END // 4)` les dégâts infligés par les ennemis jusqu'au prochain tour du joueur.
  - Force les ennemis à `1 + (CHR // 3)` cases ou moins de distance d'engager le Bouncer si possible.

### Boxer
- **Condition :** Avoir les deux mains vides.
- **Action spéciale :** Attaque une même cible avec une précision réduite de 2 jusqu'à ce qu'une des conditions suivantes soit vérifiée :
  - `2 + (STR // 2)` attaques ont été faites.
  - Une attaque subséquente est manquée (toute attaque faite après la toute première).

### Brawler
- **Action spéciale :** Attaque 2 fois avec une arme au corps à corps équipée sans engager l'arme utilisée ainsi.

### Bully
- **Action spéciale :**
  - Rend `1 + (CHR // 6)` cibles immobiles dans un rayon de `1 + (CHR // 2)` cases jusqu'au prochain tour du Bully.
  - Les alliés dans un rayon de `1 + (CHR // 3)` cases augmentent leur précision de `1 + (CHR // 4)` contre les cibles ennemies atteintes par cette action spéciale.
  - *Rappel :* Une cible ennemie ne peut être immobilisée qu'une seule fois par combat. Les immobilisations subséquentes sur une même cible la rendent **déstabilisée** à la place.

### Card Dealer
- N'a pas d'action spéciale. Au début de son tour, le joueur décide s'il souhaite lancer un **d8** (relances possibles). Selon le résultat, il obtient le bonus ou malus suivant pour le tour actif :

| d8 | Effet pour le tour actif |
| :---: | :--- |
| **1** | Réduit le total de points d'action disponibles de 1. |
| **2** | Réduit de `3 - (LCK // 4)` les points de dégâts infligés pour chacune des attaques. |
| **3** | Augmente la précision du joueur de `2 + (LCK // 3)`. |
| **4** | Restaure `2 + (LCK // 3)` points de vie au joueur. |
| **5** | Augmente le maximum de points de mouvement de `2 + (LCK // 4)`. |
| **6** | Augmente de `1 + (LCK // 3)` les points de dégâts infligés par les armes au corps à corps et aux poings. |
| **7** | Augmente de `1 + (LCK // 3)` les points de dégâts infligés par les armes à distance. |
| **8** | Augmente le total de points d'action disponibles de 1 et augmente de `1 + (LCK // 4)` les points de dégâts infligés par les explosifs. |

### Cowboy
- **Condition :** Avoir une main vide et une main équipée d'une arme avec un barillet.
- **Action spéciale :** Attaque une même cible avec une précision réduite de 2 jusqu'à ce qu'une des conditions suivantes soit vérifiée :
  - `2 + (AGI // 2)` attaques ont été faites.
  - Une attaque subséquente est manquée (toute attaque faite après la toute première).
  - Le barillet est vide.

### Hitman
- **Action spéciale (au choix) :**
  - Recharge 2 armes équipées.
  - Attaque avec chacune des armes équipées sans engager les armes utilisées.

### Leader
- **Passif :** Peut toujours dépenser une action pour donner une action à un allié adjacent.
- **Action spéciale :** Donne une action standard à 2 alliés dans un rayon de `1 + (CHR // 2)` cases.

### Medic
- **Action spéciale (au choix) :**
  - Stabiliser un allié et lui donner `1 + (INT // 2)` points de vie.
  - Convertir un medkit en pistolet régénérateur et tirer sur une cible alliée (jet de précision requis pour toucher). Si touchée, la cible regagne les points de vie d'un medkit standard + `1 + (INT // 2)` points de vie.

### Professional Pitcher
- **Action spéciale :**
  - Équipe jusqu'à un objet dans 2 mains libres.
  - Lance un objet avec une portée accrue de `1 + (LCK // 3)` cases.

### Rogue
- **Condition :** Ne pas être engagé et ne pas avoir l'aggro.
- **Action spéciale :**
  - Se déplace de `2 + (END // 4)` cases vers un ennemi immédiatement.
  - Attaque un ennemi à portée avec une arme de corps à corps et assure un coup critique si l'attaque touche.

### Rummager
- **Passif :** Hors combat, peut faire l'action de fouiller jusqu'à `1 + (LCK // 2)` fois entre chaque repos court au lieu d'une seule.
- **Action spéciale (au choix) :**
  - Fait l'action de fouiller durant le combat à condition d'être à couvert.
  - Fabrique une grenade improvisée : coûte `10 - (INT // 3)` balles et inflige autant de dégâts qu'une dynamite standard.

### Sniper
- **Condition :** Ne pas être engagé et ne pas avoir l'aggro.
- **Action spéciale :** Attaque avec une arme à un coup (*Single shot*) avec un bonus de précision temporaire de `1 + (PER // 4)` pour l'attaque et assure un coup critique si l'attaque touche.

### Spy
- **Action spéciale :**
  - Provoque la perte de l'engagement des ennemis adjacents.
  - Donne une action de mouvement gratuite immédiatement (`3 + (END // 3)` cases).
  - Provoque la perte de l'aggro pour le tour.
  - Rend la prochaine attaque silencieuse (ne provoque pas l'aggro des ennemis).

---

## Talents

| Talent | Effet |
| :--- | :--- |
| **Retaliator** | La première fois qu'un joueur se fait attaquer par un ennemi engagé, il peut effectuer une contre-attaque avec une arme au corps à corps disponible (même si engagée) ou avec son poing s'il est disponible. |
| **Opportunist** | Lorsqu'un ennemi se désengage du joueur, celui-ci peut faire une action d'attaque avec une arme au corps à corps disponible (même si engagée) ou avec son poing s'il est disponible. |
| **Maniac** | En attaquant avec une arme au corps à corps à 2 mains, peut attaquer jusqu'à `1 + (STR // 4)` cibles supplémentaires à portée. |
| **Strategist** | S'il termine son tour avec au moins 1 point d'action disponible et n'avait pas déjà de point d'action supplémentaire ce tour-ci, il gagne 2 points d'action supplémentaires au prochain tour. |
| **Fast Fingers** | Lorsqu'un chargeur ou barillet est vide, permet de faire une action de recharge gratuite immédiatement. |
| **Eagle Eye** | Les attaques à 5 cases de distance ou plus ont `+ 2 + (PER // 3)` de précision et rendent l'ennemi atteint **déstabilisé**. |
| **Rocket Scientist** | Augmente le rayon d'impact des explosifs de `INT // 6`. Le joueur et ses alliés sont immunisés aux explosifs durant le tour du joueur. Reçoit le double d'explosifs lorsqu'il en obtient. |
| **Short Sighted** | Les armes à distance peuvent atteindre les cibles ennemies adjacentes. Lorsqu'il cible un ennemi avec une arme à distance dans un rayon de `2 + (PER // 4)` cases ou moins, il peut attaquer immédiatement une cible à portée. |
| **Loot Goblin** | Permet d'effectuer un pillage `1 + (LCK // 4)` fois supplémentaire lors d'un pillage. |
| **Party Animal** | Les bonus des boissons et drogues consommées ou offertes à un allié sont doublés. Reçoit le double lorsqu'une boisson ou drogue est obtenue. |
| **Overconfident** | Permet de porter n'importe quelle arme dans une seule main. Si l'arme nécessite normalement 2 mains, sa précision est réduite de `3 - (PER // 4)`. |
| **Skillful** | Lorsqu'il attaque avec une arme, inflige `1 + (LCK // 3)` dégâts supplémentaires sur sa prochaine attaque avec un type d'arme encore inutilisé ce tour-ci (corps à corps, à distance, explosifs). Peut ensuite, au coût d'une action, déséquiper une arme en main pour équiper une autre arme ou un explosif du dernier type inutilisé ce tour-ci. |
| **Clumsy** | Lorsqu'un jet de dé fait rater la cible et que le résultat du dé est pair, obtient `1 + (LCK // 4)` relances (jusqu'au maximum de relances). |
| **Sleight of Hands** | Peut déséquiper et équiper une arme pour 1 action au lieu de 2. Une fois par tour, peut faire 2 actions de recharge immédiatement au coût d'une action. |
| **Informant** | Lorsqu'un allié devient adjacent au joueur durant le tour de ce dernier, l'allié gagne `1 + (CHR // 6)` points de mouvement supplémentaires au prochain tour et inflige `1 + (CHR // 3)` dégâts supplémentaires sur sa prochaine attaque. **Maximum 1 buff de l'Informant par joueur.** |
| **Silent** | Lorsque le joueur perd l'aggro, la première attaque suivante inflige le double de dégâts. |
| **Secourist** | Lorsqu'un allié a moins de la moitié de son maximum de points de vie, le joueur gagne `2 + (END // 3)` points de mouvement supplémentaires et `2 + (PER // 3)` de précision pour le tour. Les effets des medkits sont doublés. Le prochain medkit perdu n'est pas retiré de l'inventaire. |
| **Lucky Bastard** | Augmente de `1 + (LCK // 6)` le nombre de faces du dé provoquant un coup critique (ex. : 7 en Chance = critiques sur 18, 19, 20). |
| **Quick Pocket** | Obtient une main supplémentaire utilisable exclusivement pour lancer des objets ou équiper un explosif (pas d'arme). Permet d'effectuer gratuitement jusqu'à **1 action par tour** parmi : utiliser un consommable sur soi-même, utiliser un consommable sur un allié adjacent, ou donner un objet à un allié adjacent. |

---

# Règles

## Lexique et règles implicites

- **Adjacence :** Deux entités ou cases sont considérées comme **adjacentes** si elles se touchent orthogonalement (haut, bas, gauche, droite) (soit les 8 cases entourant une case sur la grille).
- **Engager une arme :** Consiste à *tap* (tourner/incliner) la carte correspondant à la main qui tient l'arme.
- **Engagement d'ennemi :** Être adjacent à l'ennemi et s'être fait attaquer par cet ennemi au moins une fois.
- **Équipement en main :** Une seule arme équipée par main.
- **Attaque de mêlée :** Toujours silencieuse.
- **Arme à distance :** Ne peut pas taper en mêlée (sauf exceptions explicitement prévues).
- **Déplacement et espace :** Deux joueurs ne peuvent pas occuper la même case. Les joueurs peuvent tirer à travers d'autres joueurs, mais pas à travers les ennemis.
- **État critique :** Lorsqu'un joueur perd tous ses points de vie, il tombe en état critique. Il doit lancer un dé 20 à chaque tour et obtenir un résultat supérieur à 15 pour se relever. Un allié stabilisé revient avec 1 point de vie.
- **Déstabilisé :** Réduit de 1 tout ce qui est mentionné sur la cible : **-1 dégât infligé**, **-1 point de mouvement** et **-1 en précision**.
- **Vente d'objets :** Valeur de revente de base = Coût de l'objet // 2.
- **Ammo pack :** Boîte de balles diverses (munitions variées).
- **Lecture des règles :** À tout moment, un joueur peut lire les règles du jeu, même au risque de « casser la vibe », sauf si son INT est strictement inférieur à 0 (ses capacités cognitives ne lui permettent pas de comprendre les règles).

---

## Hors combat

### Tests d'habileté (*Skill check*)

Le DM choisit la caractéristique testée et la difficulté. Le résultat minimal du dé est réduit de `Caractéristique // 4` (un test *Impossible* ne peut pas être réduit).

| Difficulté | Minimum requis de base | Formule avec caractéristique |
| :--- | :---: | :--- |
| **Facile** | 6 | `6 - (Carac // 4)` |
| **Moyen** | 11 | `11 - (Carac // 4)` |
| **Difficile** | 16 | `16 - (Carac // 4)` |
| **Impossible** | 20 | 20 (non réductible) |

*Exemple :* Un test de Force (difficulté Moyenne) avec 6 en Force demande `11 - (6 // 4) = 11 - 1 = 10`.

### Repos

Durant un repos, un joueur peut :
- Remplir tous les chargeurs et barillets de ses armes.
- Équiper et déséquiper n'importe quelle combinaison d'armes autant de fois qu'il le souhaite.
- Effectuer une action de fouille (selon les conditions du type de repos).

| Type de repos | Conditions | Soins et échanges |
| :--- | :--- | :--- |
| **Repos court** | Autorisé par le DM ; uniquement après un combat ; **maximum 1 par combat** (entre deux combats). | Restaure le tiers (arrondi à l'entier supérieur) des points de vie. Peut faire 1 fouille. |
| **Repos long** | Uniquement dans certains endroits déterminés par le DM (ex. : motel). | Restaure tous les points de vie. Permet l'échange libre d'objets entre joueurs. |

### Fouiller

Lancer un **d10** pour ajouter des objets à l'inventaire :

| d10 | Objets obtenus |
| :---: | :--- |
| **1** | 2 Balles standards |
| **2** | 4 Balles standards |
| **3** | 6 Balles standards |
| **4** | 2 Munitions uniques |
| **5** | 1 Medkit |
| **6** | 1 Bâton de dynamite |
| **7** | 1 $ |
| **8** | 3 $ |

**Munitions uniques :** Cartouche de shotgun, Balle longue portée, Carreau, Flèche.

---

## En combat

### Ordre des tours

1. Il y a deux camps : **Alliés** et **Ennemis**.
2. Le DM et un joueur lancent chacun un dé. Le camp le plus élevé commence (en cas d'égalité, relancer).
3. Chaque camp choisit l'ordre des tours de ses membres (accord unanime des joueurs requis ; à la discrétion du DM pour les ennemis). Les joueurs agissent dans l'ordre établi, un à la suite de l'autre.

### Phase de début de tour

- Regagne le maximum de **points d'action**.
- Regagne le maximum de **points de mouvement**.
- **Désengage** ses armes engagées.

### Actions (1 point d'action par action)

#### 1. Attaquer
- Engage une arme équipée (en tournant la carte de la main correspondante) ou donne un coup de poing avec une main vide.
- Cible un ennemi à portée et effectue un **jet de précision** (1 jet par cible pour un explosif).
- Si réussi, inflige les dégâts calculés. Si une arme à munition est utilisée, retire 1 munition immédiatement.

##### Jet de précision (d20)
- **Succès :** Si la précision est supérieure à 0, un résultat compris entre `21 - Précision` et `20` (soit un nombre de faces égal à la valeur de précision). Si la précision est à 0, aucun succès n'est possible.
- **1 naturel :** Toujours un échec.
- **20 naturel :** Toujours un succès et un **coup critique**.
- **Armes à distance :** Ne peuvent pas atteindre les cibles adjacentes (sauf exception).
- **Arme de corps à corps :** Précision accrue de +2.

##### Portée (*Range*) et *Over range*

| Type / Arme | Portée standard | *Over range* |
| :--- | :--- | :--- |
| **Pistolet** | 5 cases | +1 case : précision nécessaire +5 |
| **Shotgun** | 2 cases *(peut être utilisé en mêlée / cohésion)* | +2 cases : précision nécessaire +8 |
| **Mêlée** | 1 case | +3 cases : Impossible |
| **Rifle** | 9 cases | — |
| **Crossbow** | 6 cases | — |
| **Scope** | Infinie | — |
| **Lancer** | 4 cases + modificateur de Force | *Over range* ne s'applique pas |

##### Coup critique et dégâts
- **Coup critique :** Double les dégâts infligés de l'attaque en cours.

| Type d'attaque | Formule de dégâts | Notes |
| :--- | :--- | :--- |
| **Corps à corps** | Dégâts de l'arme + `(STR // 3)` | Toujours silencieuse. |
| **Coup de poing** | Dégâts de l'arme + `(STR // 3)` | Main vide. |
| **À distance** | Dégâts de l'arme + `(AGI // 3)` | Ne peut pas taper en mêlée. |
| **Explosifs** | Dégâts de l'explosif + `(INT // 3)` | Rayon d'explosion par défaut : 2 cases à l'impact au sol. |

##### Aggro
Un joueur gagne le statut d'**aggro** si :
- Il attaque avec une arme (non silencieuse).
- Il attaque en étant engagé.
- Il se déplace de **3 cases ou plus**.

Un ennemi est forcé d'attaquer uniquement les joueurs ayant l'aggro s'il y en a.

#### 2. Recharger
- Retire le chargeur d'une arme équipée et place un nouveau chargeur dans cette arme ; **ou**
- Remplit un chargeur de son inventaire de `2 + (LCK // 4)` balles (jusqu'à ce qu'il soit plein) et le place dans l'arme si aucun chargeur n'y est présent ; **ou**
- Remplit une arme équipée de `2 + (LCK // 4)` munitions (jusqu'à ce qu'elle soit pleine).

#### 3. Se déplacer
- Dépense jusqu'à son maximum de points de mouvement et se déplace d'autant de cases (orthogonalement ou en diagonale).

#### 4. Équiper une arme ou un objet
- Prend un objet de son inventaire et le place dans une main vide disponible (désengage l'arme le cas échéant).

#### 5. Déséquiper une arme ou un objet
- Place un objet équipé d'une main vers l'inventaire.

#### 6. Consommer un objet
- Retire l'objet de l'inventaire et applique son effet sur soi ou sur un allié adjacent.

#### 7. Se désengager
- Lance un **d20** : se désengage des ennemis adjacents si le résultat est supérieur à `10 - (END // 3)`.
- *Engagement :* Un joueur ou ennemi qui attaque et est adjacent à une cible est **engagé** (pour un ennemi, cela requiert qu'il ait attaqué la cible au moins une fois en étant adjacent). Un joueur engagé par un ennemi ne peut plus bouger tant qu'il est engagé par cet ennemi.

#### 8. Stabiliser un allié
- Relève un allié tombé au combat et lui donne 1 point de vie.

#### 9. Donner un objet
- Donne un objet de l'inventaire ou équipé à un joueur adjacent (placé dans l'inventaire de la cible).

#### 10. Prendre un objet
- Prend un objet de l'inventaire ou équipé d'un allié adjacent (avec son consentement) et le place dans l'inventaire ou une main vide (désengagé).

#### 11. Lancer un objet
- Lance un objet équipé à une portée de 4 cases. Si c'est un consommable lancé sur un allié, celui-ci gagne directement ses effets.

#### 12. Perdre l'aggro
- Fait perdre le statut d'aggro au joueur.

#### 13. Action contextuelle
- Action créative à la discrétion du DM.

---

## Butin (*Loot*)

À la discrétion du DM à la fin d'un combat.
