# Qu'est-ce qu'une donnée ?

**Activité interactive — Module : Les données en santé à l'ère de l'IA**  
Cours *Culture numérique en sciences de la santé* · Faculté de médecine · Université Laval

---

## Tâche à réaliser

1 - Réaliser l'activité interactive
2 - Lire 

## Activité Interactive

Cette activité vous invite à explorer une note clinique d'urgence et à identifier par vous-même les données qu'elle contient ce qui constitue une **donnée**. 


👉 [Lancer l'activité](https://nablanabla.github.io/Introduction_aux_donn-es/)

---

## Pour approfondir : les types de données

### L'exemple du pouls


<p align="center">
  <img src="assets/Pouls_classique.jpg" width="600" alt="Le pouls pris classiquement. [Source : Wikipedia]">
  <br>
  <em>Figure 1 : Le pouls pris classiquement. [Source : Wikipedia] </em>
</p>

En **médecine occidentale**, le pouls est pris au poignet et exprimé en battements par minute (bpm). C'est une **donnée numérique** — discrete, mesurable, comparable.



<p align="center">
  <img src="assets/pouls_médecine_chinoise.jpeg" width="600" alt="Le pouls en médecine chinoise. [Source : Doctissimo]">
  <br>
  <em>Figure 2 : Le pouls en médecine chinoise. [Source : Doctissimo] </em>
</p>


En **médecine traditionnelle chinoise**, le pouls est pris aux deux poignets, en trois positions et à trois profondeurs. On distingue jusqu'à 28 qualités de pouls (tendu, glissant, en corde…). C'est une **donnée qualitative** — riche, contextuelle, interprétative.

Un même phénomène physiologique. Deux types de données radicalement différents. La différence ne tient pas à la réalité observée, mais au **cadre d'observation et au traitement que l'on en fait**.

---

### Types de données

**Données quantitatives**  
Exprimées en nombres avec des intervalles égaux, elles autorisent des opérations numériques et des statistiques paramétriques (moyenne, écart-type, corrélation…). Elles peuvent être :
- *Discrètes* — valeurs entières (ex. : nombre de crises épileptiques)
- *Continues* — toute valeur dans un intervalle (ex. : glycémie, température)

**Données qualitatives**  
Non numériques, elles décrivent des catégories, des expériences ou des caractéristiques (ex. : sexe, diagnostic, témoignage d'un patient). Elles peuvent être :
- *Nominales* — sans ordre (ex. : groupe sanguin)
- *Ordinales* — avec ordre (ex. : échelle de satisfaction, de très insatisfait à très satisfait)

---

### ⚠️ Points de vigilance

**1. Les « fausses » données quantitatives**  
L'échelle de douleur de 0 à 10 (EVA — Échelle Visuelle Analogique) en est un exemple classique. Faire la moyenne des scores EVA d'un groupe n'a pas de sens statistique rigoureux, et passer d'une EVA de 8 à 4 ne signifie pas que l'on a deux fois moins mal. La forme numérique ne garantit pas les propriétés du quantitatif.

**2. Les « fausses » données qualitatives**  
Traité par un grand modèle de langage (LLM), un texte devient un ensemble de données quantitatives. Le texte est découpé en tokens, puis « plongé » dans un espace vectoriel à grande dimension. Ce qui semblait purement qualitatif devient le substrat d'opérations mathématiques.

> **Le type d'une donnée est étroitement lié au traitement que l'on en fait.**  
> Ce principe est au cœur de la science des données en santé.

---






---

*Faculté de médecine · Université Laval*