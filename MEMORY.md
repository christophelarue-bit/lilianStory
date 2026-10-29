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

### 1. Les personnes (`people/`)

Une fiche par personne qui compose la vie de Lillian. Chaque fiche couvre :

- leurs relations entre eux
- leurs relations avec Lillian
- leur impact sur sa vie
- leur importance dans sa vie
- leur importance dans son histoire et la construction de son être
- un **tableau des périodes** où elles apparaissent, placé en tête de fiche, juste après le titre (période, époque, lieu, ce qui a été partagé)
- tout ce qui permet de comprendre leur impact sur Lillian : douleurs, bonheurs, sentiments forts suscités

Modèle : [people/_template.md](people/_template.md)

### 2. Les périodes (`periods/`)

Une fiche par période de la vie de Lillian. Chaque fiche couvre :

- le pays, la ville
- la ou les dates
- les personnes fréquentées, avec anecdotes de vie et histoires fortes en émotions ou profondes dans la relation
- les histoires et petits détails de la période
- les paysages et l'ambiance de vie

Modèle : [periods/_template.md](periods/_template.md)

### 3. Les époques (`eras/`)

Une époque est une grande partie de la vie de Lillian, qui peut devenir **un livre de la collection**. Ses périodes en sont les chapitres. Chaque fiche époque couvre :

- les dates et l'âge de Lillian
- un résumé de l'époque
- la liste des périodes qui la composent
- le fil rouge et les enjeux
- les interviews à prévoir avec Lillian (thèmes, statut)

Une époque décrit son contenu en quelques paragraphes et liste les périodes qui la composent. **Les personnes ne sont reliées qu'aux périodes, pas aux époques** (on verra plus tard si une table des personnes est utile au niveau de l'époque).

Modèle : [eras/_template.md](eras/_template.md)

## Structure du dépôt

```
MEMORY.md              ← ce fichier : objectif, méthode, index
README.md              ← pitch du projet
eras/
  _template.md           ← modèle de fiche époque
  01-origins-and-early-childhood.md
  02-childhood-and-teens-in-france.md
  03-back-to-the-united-states.md
  04-marriage-to-mohamed.md
  05-flight-attendant-hawaii-alaska.md
  06-back-to-france.md
  07-chris-and-nice-draft.md
people/
  _template.md           ← modèle de fiche personne
  lillian.md
  dad.md
  mom.md
  gwen.md
  xavier.md
  maternal-grandfather.md
  clara.md
  mohamed.md
  david-ny.md
  david-friend.md
  walter.md
  yacine.md
  adriana.md
  jose.md
  the-rennes-man.md
  christophe.md
periods/
  _template.md           ← modèle de fiche période
  01-01-meeting-in-frankfurt.md
  01-02-birth-in-heidelberg.md
  01-03-early-childhood-with-family.md
  01-04-summer-1985-saint-brevin.md
  02-01-childhood-and-teens-in-france.md
  03-01-syracuse-finding-dad.md
  03-02-new-york-city.md
  04-01-married-life-with-mohamed.md
  05-01-flight-attendant.md
  05-02-nurse-in-hawaii.md
  05-03-nurse-in-alaska.md
  06-01-the-rennes-man-brittany-ferries.md
  06-02-apartment-in-rennes.md
  07-01-meeting-chris.md
```

Convention : fichiers en minuscules, sans accents, tirets pour les espaces.

- Les **époques** sont préfixées par un numéro d'ordre chronologique : `01-origins-and-early-childhood.md`.
- Les **périodes** sont préfixées par le numéro de leur époque, puis leur numéro dans l'époque : `03-02-new-york-city.md` est la 2e période de l'époque 03. Insérer une période ne touche que son époque.

## Index

### Personnes

| Fiche | Résumé |
|---|---|
| [lillian](people/lillian.md) | Le personnage central. Habite Nice depuis environ 1 an. |
| [papa](people/dad.md) | Mark, américain, militaire (GI, Irak), habite Syracuse (État de New York). |
| [maman](people/mom.md) | Béatrice, ex-jeune fille au pair, habite Saint-Brieuc, France. |
| [gwen](people/gwen.md) | Sœur cadette, née en 1982, habite Vendôme. |
| [xavier](people/xavier.md) | Frère cadet, né après l'été 1985, habite Nantes. |
| [grand-pere-maternel](people/maternal-grandfather.md) | Père de Béatrice, a suggéré qu'elle reste en France en 1985. |
| [clara](people/clara.md) | Rôle à préciser, liée à une blessure avec Mark. |
| [mohamed](people/mohamed.md) | Mari de Lillian pendant 15 ans (sensible). |
| [david-ny](people/david-ny.md) | Petit flirt chinois de New York. |
| [david-ami](people/david-friend.md) | Ami de l'époque 05, avec Adriana. |
| [walter](people/walter.md) | Du Bangladesh, rencontré à New York. |
| [yacine](people/yacine.md) | Rencontré pendant le mariage, rôle à préciser. |
| [adriana](people/adriana.md) | Amie de l'époque 05. |
| [jose](people/jose.md) | Un amour de l'époque 05. |
| [le-rennais](people/the-rennes-man.md) | Rencontre amoureuse de 2021 à Rennes (sensible). |
| [christophe](people/christophe.md) | Chris, fiche minimale en brouillon. |

### Époques

| Fiche | Résumé |
|---|---|
| [01 — Origines et petite enfance](eras/01-origins-and-early-childhood.md) | De la rencontre des parents (1976) à l'été 1985. |
| [02 — Enfance et adolescence en France](eras/02-childhood-and-teens-in-france.md) | Amorce : 1985 à environ 1997. |
| [03 — Retour aux États-Unis](eras/03-back-to-the-united-states.md) | Retrouver son père, déception Clara, New York, rencontre de Mohamed. |
| [04 — Mariage avec Mohamed](eras/04-marriage-to-mohamed.md) | 15 ans de mariage (sensible). |
| [05 — Hôtesse de l'air, Hawaï, Alaska](eras/05-flight-attendant-hawaii-alaska.md) | Trois périodes de travail et de rencontres. |
| [06 — Retour en France](eras/06-back-to-france.md) | 2021 : Rennes, Brittany Ferries, rapprochement de la famille. |
| [07 — Chris et Nice (brouillon)](eras/07-chris-and-nice-draft.md) | Après le 01/01/2023, brouillon. |

### Périodes

| Fiche | Résumé |
|---|---|
| [01-01 — Rencontre à Francfort](periods/01-01-meeting-in-frankfurt.md) | 1976, Mark et Béatrice se rencontrent dans un bar de GI. |
| [01-02 — Naissance à Heidelberg](periods/01-02-birth-in-heidelberg.md) | 1979, naissance à l'hôpital militaire. |
| [01-03 — Petite enfance en famille](periods/01-03-early-childhood-with-family.md) | 1979-1985, vie avec Mark, naissance de Gwen. |
| [01-04 — Été 1985 à Saint-Brevin](periods/01-04-summer-1985-saint-brevin.md) | Les vacances qui deviennent un retour définitif en France. |
| [02-01 — Enfance et adolescence en France](periods/02-01-childhood-and-teens-in-france.md) | Amorce : 1985 à environ 1997. |
| [03-01 — Syracuse : retrouver papa](periods/03-01-syracuse-finding-dad.md) | Amorce : retrouvailles avec Mark, déception Clara. |
| [03-02 — New York City](periods/03-02-new-york-city.md) | David, Walter, rencontre de Mohamed. |
| [04-01 — Vie conjugale avec Mohamed](periods/04-01-married-life-with-mohamed.md) | 15 ans de mariage (sensible). |
| [05-01 — Hôtesse de l'air](periods/05-01-flight-attendant.md) | Amorce. |
| [05-02 — Infirmière à Hawaï](periods/05-02-nurse-in-hawaii.md) | Amorce. |
| [05-03 — Infirmière en Alaska](periods/05-03-nurse-in-alaska.md) | Amorce. |
| [06-01 — Le Rennais, Brittany Ferries, 2e avortement](periods/06-01-the-rennes-man-brittany-ferries.md) | 2021, Rennes (sensible). |
| [06-02 — Appartement à Rennes](periods/06-02-apartment-in-rennes.md) | Période plus calme, près de la famille. |
| [07-01 — Rencontre avec Chris](periods/07-01-meeting-chris.md) | Brouillon. |

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

- Si, en parlant d'une période, on évoque une nouvelle personne, on **crée sa fiche** dans `people/` à partir du modèle.
- La fiche personne est **liée aux différentes périodes** où elle apparaît (tableau en tête de fiche, juste après le titre), et la fiche période est liée à la fiche personne (section « Personnes fréquentées »).
- **Toute personne nommée évoquée dans une période doit avoir sa fiche personne.**
- Les personnes ou groupes **sans nom** (belle-famille, amis, enfants, collègues) n'ont pas de fiche : ils sont cités dans la période, et « À préciser » demande leur nom. Dès qu'ils sont nommés, on crée la fiche.

### Règle 3 — Personne qui introduit une période

- Réciproquement, si, en parlant d'une personne, on évoque une période qui n'existe pas encore, on **crée la fiche période** dans `periods/` à partir du modèle, avec son numéro `EE-PP`.
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
