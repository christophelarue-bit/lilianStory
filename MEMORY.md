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

## Structure du dépôt

```
MEMORY.md              ← ce fichier : objectif, méthode, index
README.md              ← pitch du projet
personnes/
  _modele.md           ← modèle de fiche personne
  lillian.md
  papa.md
  maman.md
periodes/
  _modele.md           ← modèle de fiche période
  01-naissance-heidelberg.md
```

Convention : fichiers en minuscules, sans accents, tirets pour les espaces. Les périodes sont préfixées par un numéro d'ordre chronologique (`01-`, `02-`…), réattribuable si on découvre une période intermédiaire.

## Index

### Personnes

| Fiche | Résumé |
|---|---|
| [lillian](personnes/lillian.md) | Le personnage central. Habite Nice depuis environ 1 an. |
| [papa](personnes/papa.md) | Américain, habite Syracuse (État de New York). |
| [maman](personnes/maman.md) | Habite Saint-Brieuc, France. |

### Périodes

| Fiche | Résumé |
|---|---|
| [01 — Naissance à Heidelberg](periodes/01-naissance-heidelberg.md) | Naissance en Allemagne. |

## Règles de travail

- Ne rien inventer : tout ce qui n'est pas confirmé par Lillian reste dans « Questions ouvertes ».
- Les fiches s'enrichissent au fil des échanges ; chaque ajout significatif fait l'objet d'un commit.
- Quand une personne ou une période apparaît dans une fiche sans avoir la sienne, on crée la fiche et on l'ajoute à l'index.
