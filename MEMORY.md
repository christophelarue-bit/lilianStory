# MEMORY — Les story de Lillian

## Objectif du projet

Réaliser une **série de livres** racontant l'histoire de **Lillian**, une femme de la fin de la Génération X, au parcours très riche, qui peut être organisé pour former une **collection de livres**.

## Ce qui reste à décider (plus tard)

- Nombre de pages par livre
- Organisation des chapitres
- Structuration de la collection (par période, par thème, par personnage…)
- Tonalité et style des livres

## Phase actuelle : collecte d'informations

Pas d'écriture des livres pour l'instant. On construit petit à petit, au fil des échanges et des commits, une base de matériaux, sous forme de fiches Markdown.

### 1. Les personnes (`personnes/`)

Une fiche par personne qui compose la vie de Lillian. Chaque fiche couvre :

- leurs relations entre eux
- leurs relations avec Lillian
- leur impact sur sa vie
- leur importance dans sa vie
- leur importance dans son histoire et la construction de son être
- leurs différents moments de partage de vie (période, emplacement)
- tout ce qui permet de comprendre leur impact sur Lillian : douleurs, bonheurs, sentiments forts suscités

Modèle : [personnes/_modele.md](personnes/_modele.md)

### 2. Les périodes (`periodes/`)

Une fiche par période de la vie de Lillian. Chaque fiche couvre :

- le pays, la ville
- la ou les dates
- les personnes fréquentées, avec anecdotes de vie et histoires fortes en émotions ou profondes dans la relation
- les histoires et petits détails de la période
- les paysages et l'ambiance de vie

Modèle : [periodes/_modele.md](periodes/_modele.md)

### 3. Les époques (`epoques/`)

Une époque est une grande partie de la vie de Lillian, qui peut devenir **un livre de la collection**. Ses périodes en sont les chapitres. Chaque fiche époque couvre :

- les dates et l'âge de Lillian
- un résumé de l'époque
- la liste des périodes qui la composent
- les personnes clés
- le fil rouge et les enjeux

Modèle : [epoques/_modele.md](epoques/_modele.md)

## Structure du dépôt

```
MEMORY.md              ← ce fichier : objectif, méthode, index
README.md              ← pitch du projet
epoques/
  _modele.md           ← modèle de fiche époque
  01-origines-et-enfance.md
  02-annees-americaines.md
  03-vie-adulte.md
personnes/
  _modele.md           ← modèle de fiche personne
  lillian.md
  papa.md
  maman.md
  gwen.md
  xavier.md
  grand-pere-maternel.md
  clara.md
periodes/
  _modele.md           ← modèle de fiche période
  00-rencontre-francfort.md
  01-naissance-heidelberg.md
  02-petite-enfance-en-famille.md
  03-ete-1985-saint-brevin.md
  04-retour-etats-unis-18-ans.md
```

Convention : fichiers en minuscules, sans accents, tirets pour les espaces. Les époques et les périodes sont préfixées par un numéro d'ordre chronologique (`01-`, `02-`…), réattribuable si on découvre une période intermédiaire.

## Index

### Personnes

| Fiche | Résumé |
|---|---|
| [lillian](personnes/lillian.md) | Le personnage central. Habite Nice depuis environ 1 an. |
| [papa](personnes/papa.md) | Mark, américain, militaire (GI, Irak), habite Syracuse (État de New York). |
| [maman](personnes/maman.md) | Béatrice, ex-jeune fille au pair, habite Saint-Brieuc, France. |
| [gwen](personnes/gwen.md) | Sœur cadette, née en 1982. |
| [xavier](personnes/xavier.md) | Frère cadet, né après l'été 1985. |
| [grand-pere-maternel](personnes/grand-pere-maternel.md) | Père de Béatrice, a suggéré qu'elle reste en France en 1985. |
| [clara](personnes/clara.md) | Rôle à préciser, liée à une blessure avec Mark. |

### Époques

| Fiche | Résumé |
|---|---|
| [01 — Origines et enfance](epoques/01-origines-et-enfance.md) | De la rencontre des parents (1976) aux 18 ans de Lillian. |
| [02 — Années américaines](epoques/02-annees-americaines.md) | Amorce : Lillian rejoint son père aux États-Unis. |
| [03 — Vie d'adulte](epoques/03-vie-adulte.md) | Amorce : jusqu'à Nice. Titre provisoire. |

### Périodes

| Fiche | Résumé |
|---|---|
| [00 — Rencontre à Francfort](periodes/00-rencontre-francfort.md) | 1976, Mark et Béatrice se rencontrent dans un bar de GI. |
| [01 — Naissance à Heidelberg](periodes/01-naissance-heidelberg.md) | 1979, naissance à l'hôpital militaire. |
| [02 — Petite enfance en famille](periodes/02-petite-enfance-en-famille.md) | 1979-1985, vie avec Mark, naissance de Gwen. |
| [03 — Été 1985 à Saint-Brevin](periodes/03-ete-1985-saint-brevin.md) | Les vacances qui deviennent un retour définitif en France. |
| [04 — Retour aux États-Unis à 18 ans](periodes/04-retour-etats-unis-18-ans.md) | Amorce : Lillian rejoint son père. |

## Règles de travail (à appliquer à chaque échange)

- Ne rien inventer : tout ce qui n'est pas confirmé par Lillian reste dans la section « À préciser ».
- Les fiches s'enrichissent au fil des échanges ; chaque ajout significatif fait l'objet d'un commit.

### Règle 1 — La section « À préciser »

- Chaque fiche (personne ou période) contient une section **« À préciser »**.
- À chaque fois qu'on découvre une personne ou une période, et au fil des échanges sur ce sujet, on y note les questions qui permettraient de compléter la compréhension :
  - du personnage
  - du contexte
  - d'une situation
  - d'une période
  - d'un événement en particulier
  - d'une histoire personnelle à creuser avec un personnage
- Cette section est **mise à jour à chaque échange** : on ajoute les nouvelles questions et on retire (en reportant la réponse dans la bonne section de la fiche) celles qui ont été résolues.

### Règle 2 — Période qui introduit une personne

- Si, en parlant d'une période, on évoque une nouvelle personne, on **crée sa fiche** dans `personnes/` à partir du modèle.
- La fiche personne est **liée aux différentes périodes** où elle apparaît (tableau « Moments de partage de vie »), et la fiche période est liée à la fiche personne (section « Personnes fréquentées »).
- **Toute personne évoquée dans une période doit avoir sa fiche personne.**

### Règle 3 — Personne qui introduit une période

- Réciproquement, si, en parlant d'une personne, on évoque une période qui n'existe pas encore, on **crée la fiche période** dans `periodes/` à partir du modèle, avec son numéro chronologique.
- Les liens sont posés dans les deux sens, comme dans la règle 2.

### Règle 4 — Époques

- Chaque période est rattachée à une **époque** (champ « Époque » en tête de fiche) et listée dans le tableau « Périodes » de la fiche époque.
- Toute nouvelle période est ajoutée à l'époque qui lui correspond, dans les deux sens.
- Les époques sont les candidates au découpage en livres, sans que cela soit décidé.

### Règle 5 — Index

- Toute fiche créée est ajoutée à l'index de ce fichier.
