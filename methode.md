---
title: "construction d'un style CSL pour une revue qui n'en dipose pas"
date: 20250211
author: Damien Belvèze
---

# Recherche d'un style source avec le moteur de recherche de CSL Visual Editor 

Formatage des exemples fournis par la recherche de style par proximité dans l'application [CSL Visual Viewer](https://editor.citationstyles.org/searchByExample/)

## préparation des exemples

exemples fournis par la fonctionalité "Search by example"

**article de revue électronique**
- Campbell John L. et Ove K. Pedersen, « The varieties of capitalism and hybrid success », Comparative Political Studies, vol. 40, no 3, 1er mars 2007, p. 307-332 (en ligne : https://journals.sagepub.com/doi/abs/10.1177/0010414006286542 ; consulté le 26 juillet 2010).  

**ouvrage**
- Isaacson Walter, Steve Jobs, New York, NY, Simon & Schuster, 2011.  

**chapitre d'ouvrage**
- Mares Isabela, « Firms and the welfare state: When, why, and how does social policy matter to employers? », dans Peter A. Hall et David Soskice (éd.), Varieties of capitalism. The institutional foundations of comparative advantage, New York, Oxford University Press, 2001, p. 184-213.  

Autres caractéristiques : le style de destination est un style note et l'appel de citation est numérique et ne comporte pas de suffixe ni de préfixe : 1 au lieu de (1) ou [1]. 
Confirmé en allant voir les articles parus dans la revue. 


Première ligne : présentation extraite des guidelines de la revue (https://journals.openedition.org/craup/)
Deuxième ligne : application des termes contenus dans les exemples fournis par CSL visual viewer pour améliorer la détection de styles proches.

### ouvrage

#Prénom Nom, Titre, Ville d’édition, Maison d’édition (Collection), année de publication, p. xx.
Walter Isaacson, Steve Jobs, New York, Simon & Schuster, 2011

### article revue avec identifiant numérique 

#Prénom Nom, « Titre de l’article », Titre de la revue, vol. /n° , date de publication, p. xx.
John L. Campbell, "The varieties of capitalism and hybrid sucess", Comparative Political Studies, vol. 40, n°3, 2007, p. 307-332 [en ligne] [https://journals.sagepub.com/doi/abs/10.1177/0010414006286542], consulté le 26 juillet 2010


### chapitre ouvrage collectif

#Prénom Nom, « Titre du chapitre », dans Prénom Nom et Prénom Nom (dir./coord./éd./éds, etc.), Titre, Ville d’édition, Maison d’édition, année de publication, p. xx.
Isabella Mares, « Firms and the welfare state: When, why, and how does social policy matter to employers? » dans Peter A. Hall et David Soskice (éd.), Varieties of capitalism, New York, Oxford University Press, 2001, p. 184-213

### 

Pas d'exemple fourni par CSL Viewer pour des ouvrages collectifs

##



# Résultats des tests avec la fonctionnalité "Search by example"

particularité de l'appel de citation numérique sans suffixe ni préfixe : les 5 styles qui l'appliquent sont très éloignés du style cible. 
Lorsqu'on réitère la recherche avec cet indice entre parenthèses ou entre crochets, les premiers styles qui apparaissent avec le plus grand score de match ne prennent pas en compte le formatage du nom (Mares I ou MARES I. au lieu de Isabella Mares comme dans le style cible). 

-> partir du style source ENS-Lyon déjà formaté par Lucie Ribourg


