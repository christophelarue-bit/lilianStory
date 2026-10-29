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
- un **tableau des périodes** où elles apparaissent, placé en tête de fiche, juste après le titre (période, époque, lieu, ce qui a été partagé)
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
- le fil rouge et les enjeux
- les interviews à prévoir avec Lillian (thèmes, statut)

Une époque décrit son contenu en quelques paragraphes et liste les périodes qui la composent. **Les personnes ne sont reliées qu'aux périodes, pas aux époques** (on verra plus tard si une table des personnes est utile au niveau de l'époque).

Modèle : [epoques/_modele.md](epoques/_modele.md)

## Structure du dépôt

```
MEMORY.md              ← ce fichier : objectif, méthode, index
README.md              ← pitch du projet
epoques/
  _modele.md           ← modèle de fiche époque
  01-origines-et-petite-enfance.md
  02-enfance-adolescence-france.md
  03-retour-etats-unis.md
  04-mariage-mohamed.md
  05-hotesse-hawai-alaska.md
  06-retour-en-france.md
  07-chris-et-nice-brouillon.md
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
  01-01-rencontre-francfort.md
  01-02-naissance-heidelberg.md
  01-03-petite-enfance-en-famille.md
  01-04-ete-1985-saint-brevin.md
  02-01-enfance-adolescence-france.md
  03-01-syracuse-retrouver-papa.md
  03-02-new-york-city.md
  04-01-vie-conjugale-avec-mohamed.md
  05-01-hotesse-de-l-air.md
  05-02-infirmiere-hawai.md
  05-03-infirmiere-alaska.md
  06-01-le-rennais-brittany-ferries.md
  06-02-appartement-a-rennes.md
  07-01-rencontre-avec-chris.md
```

Convention : fichiers en minuscules, sans accents, tirets pour les espaces.

- Les **époques** sont préfixées par un numéro d'ordre chronologique : `01-origines-et-petite-enfance.md`.
- Les **périodes** sont préfixées par le numéro de leur époque, puis leur numéro dans l'époque : `03-02-new-york-city.md` est la 2e période de l'époque 03. Insérer une période ne touche que son époque.

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
| [01 — Origines et petite enfance](epoques/01-origines-et-petite-enfance.md) | De la rencontre des parents (1976) à l'été 1985. |
| [02 — Enfance et adolescence en France](epoques/02-enfance-adolescence-france.md) | Amorce : 1985 à environ 1997. |
| [03 — Retour aux États-Unis](epoques/03-retour-etats-unis.md) | Retrouver son père, déception Clara, New York, rencontre de Mohamed. |
| [04 — Mariage avec Mohamed](epoques/04-mariage-mohamed.md) | 15 ans de mariage (sensible). |
| [05 — Hôtesse de l'air, Hawaï, Alaska](epoques/05-hotesse-hawai-alaska.md) | Trois périodes de travail et de rencontres. |
| [06 — Retour en France](epoques/06-retour-en-france.md) | 2021 : Rennes, Brittany Ferries, rapprochement de la famille. |
| [07 — Chris et Nice (brouillon)](epoques/07-chris-et-nice-brouillon.md) | Après le 01/01/2023, brouillon. |

### Périodes

| Fiche | Résumé |
|---|---|
| [01-01 — Rencontre à Francfort](periodes/01-01-rencontre-francfort.md) | 1976, Mark et Béatrice se rencontrent dans un bar de GI. |
| [01-02 — Naissance à Heidelberg](periodes/01-02-naissance-heidelberg.md) | 1979, naissance à l'hôpital militaire. |
| [01-03 — Petite enfance en famille](periodes/01-03-petite-enfance-en-famille.md) | 1979-1985, vie avec Mark, naissance de Gwen. |
| [01-04 — Été 1985 à Saint-Brevin](periodes/01-04-ete-1985-saint-brevin.md) | Les vacances qui deviennent un retour définitif en France. |
| [02-01 — Enfance et adolescence en France](periodes/02-01-enfance-adolescence-france.md) | Amorce : 1985 à environ 1997. |
| [03-01 — Syracuse : retrouver papa](periodes/03-01-syracuse-retrouver-papa.md) | Amorce : retrouvailles avec Mark, déception Clara. |
| [03-02 — New York City](periodes/03-02-new-york-city.md) | David, Walter, rencontre de Mohamed. |
| [04-01 — Vie conjugale avec Mohamed](periodes/04-01-vie-conjugale-avec-mohamed.md) | 15 ans de mariage (sensible). |
| [05-01 — Hôtesse de l'air](periodes/05-01-hotesse-de-l-air.md) | Amorce. |
| [05-02 — Infirmière à Hawaï](periodes/05-02-infirmiere-hawai.md) | Amorce. |
| [05-03 — Infirmière en Alaska](periodes/05-03-infirmiere-alaska.md) | Amorce. |
| [06-01 — Le Rennais, Brittany Ferries, 2e avortement](periodes/06-01-le-rennais-brittany-ferries.md) | 2021, Rennes (sensible). |
| [06-02 — Appartement à Rennes](periodes/06-02-appartement-a-rennes.md) | Période plus calme, près de la famille. |
| [07-01 — Rencontre avec Chris](periodes/07-01-rencontre-avec-chris.md) | Brouillon. |

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
- La fiche personne est **liée aux différentes périodes** où elle apparaît (tableau en tête de fiche, juste après le titre), et la fiche période est liée à la fiche personne (section « Personnes fréquentées »).
- **Toute personne nommée évoquée dans une période doit avoir sa fiche personne.**
- Les personnes ou groupes **sans nom** (belle-famille, amis, enfants, collègues) n'ont pas de fiche : ils sont cités dans la période, et « À préciser » demande leur nom. Dès qu'ils sont nommés, on crée la fiche.

### Règle 3 — Personne qui introduit une période

- Réciproquement, si, en parlant d'une personne, on évoque une période qui n'existe pas encore, on **crée la fiche période** dans `periodes/` à partir du modèle, avec son numéro `EE-PP`.
- Les liens sont posés dans les deux sens, comme dans la règle 2.

### Règle 4 — Époques

- Chaque période est rattachée à une **époque** (champ « Époque » en tête de fiche, dans l'introduction) et listée dans le tableau « Périodes » de la fiche époque.
- Toute nouvelle période est ajoutée à l'époque qui lui correspond, dans les deux sens.
- Les époques sont les candidates au découpage en livres, sans que cela soit décidé.
- Chaque fiche époque contient une section **« Interviews à prévoir »** : thèmes à couvrir avec Lillian et statut (à faire, faite). Prévu : époque 04, 1 à 2 interviews ; époque 05, au moins 1 interview par période (hôtesse de l'air, Hawaï, Alaska).

### Règle 5 — Index

- Toute fiche créée est ajoutée à l'index de ce fichier.

### Règle 6 — Brouillon après le 01/01/2023 (règle temporaire)

- Tout ce qui concerne la vie de Lillian **après le 01/01/2023** (dont l'époque 07, Chris et Nice) est traité comme un **brouillon** : on ne crée que le minimum et la section « À préciser » contient **3 questions essentielles au maximum** (dates, lieu, rôle de la personne), sans questions de détail, d'émotions ou d'anecdotes.
- **À supprimer** quand les époques 01 à 06 seront traitées : on posera alors autant de questions que nécessaire pour préciser cette époque.

### Règle 7 — Sujets sensibles

- Pour les sujets sensibles (avortements, alcool, humiliations, abandon, violences…), les faits sont consignés **sobrement**, sans détail inventé.
- La fiche concernée porte la mention : « **Sensible : à valider avec Lillian avant tout usage dans un livre** ».
- Les noms de personnes réelles sont à revalider avec Lillian au moment de l'écriture.

### Règle 8 — Commits

- Les modifications d'organisation sont commitées **séparément**, dans cet ordre : règles (`MEMORY.md`), puis époques, puis périodes, puis personnes.
- Les messages de commit sont en français, courts, et terminés par la ligne de co-auteur demandée par l'outil.

### Règle 9 — Questions à Lillian

- Les questions sont posées **groupées par thème**.
- Avant de bâtir un plan de réorganisation, on pose d'abord **toutes les questions** utiles pour bien comprendre la demande.
