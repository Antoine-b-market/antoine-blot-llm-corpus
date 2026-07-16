---
title: "Qu’est-ce qu’une page orpheline en SEO ?"
description: "Découvrez ce que sont les pages orphelines, pourquoi elles nuisent au SEO et comment les identifier et les réintégrer efficacement dans votre maillage interne."
author: "Antoine Blot"
author_url: "https://www.antoine-blot.com"
canonical_url: "https://www.antoine-blot.com/fr/ressources-seo/pages-orphelines/"
date: "2025-07-31"
date_modified: "2025-08-01"
lang: "fr"
hreflang: "fr-CA"
robots: "index, follow"
---

Les pages orphelines sont un sujet souvent méconnu mais crucial en SEO technique. Elles désignent des pages publiées sur un site web mais **non accessibles depuis aucune autre page via des liens internes**.
Autrement dit, elles existent bien dans l’index du site, voire parfois dans celui de Google, mais **aucun utilisateur ni crawler ne peut y accéder depuis la navigation naturelle**. Cela nuit gravement à l’indexation, au maillage interne, à la transmission de popularité… et donc à la visibilité SEO globale.



## **Définition d’une page orpheline**

Une page orpheline est une page web qui ne reçoit **aucun lien interne** depuis les autres pages du site. Elle n’est donc **pas intégrée à l’arborescence du site**.
Ces pages peuvent exister pour plusieurs raisons : création manuelle sans intégration, test non retiré, ancienne campagne landing page oubliée, etc.

Même si une page orpheline est accessible directement par son URL, elle :

- - - Ne bénéficie pas de jus de lien (PageRank),
    - Est difficilement accessible aux utilisateurs,
    - Peut ne pas être explorée par Googlebot,
    - Et est parfois **désindexée automatiquement** par Google à terme.

## **Pourquoi les pages orphelines sont un problème en SEO ?**

### **Elles cassent le maillage interne**

Le maillage interne est ce qui permet aux robots de comprendre la structure du site, de transmettre de l’autorité, et de guider l’utilisateur dans son parcours.
Une page orpheline **n’est pas reliée au reste du site**, elle devient donc invisible pour les moteurs à moins d’un lien externe ou d’un sitemap.

### **Elles diluent l’autorité du site**

Si une page n’est jamais mise en relation avec les autres, elle :

- - - Ne transmet rien,
    - Ne reçoit rien,
    - Et ne contribue pas à la cohérence globale du site.

### **Elles peuvent polluer l’index Google**

Si une page orpheline est indexée sans être pertinente, elle :

- - - Peut faire baisser le ratio index/qualité du site (concept de crawl budget),
    - Peut générer des signaux de désengagement (taux de rebond, non-navigation),
    - Peut déclencher une **dégradation de la perception qualité du domaine**.

## **Causes fréquentes de pages orphelines**

- - - Pages créées pour des campagnes Ads non reliées au reste du site
    - Fiches produits expirées ou dépubliées partiellement
    - Pages oubliées après une refonte ou migration
    - Contenus créés mais jamais intégrés dans le menu ou les liens contextuels
    - Pages avec erreurs de logique de pagination ou d’URL non liées
    - Archives WordPress non maîtrisées (tags, auteurs, dates)

## **Comment identifier les pages orphelines ?**

La détection nécessite **un croisement de données entre deux sources** :

### **Pages connues du site (crawl)**

→ Utiliser Screaming Frog, OnCrawl ou Sitebulb pour identifier toutes les pages **liées** à partir de l’accueil.

### **Pages connues de Google (indexées)**

→ Utiliser Google Search Console, logs serveur, ou un export de sitemap + indexation pour voir **ce que Google connaît**.

## **Méthode :**

- - - Exporter la liste des URLs crawlées (liées)
    - Exporter la liste des URLs indexées (GSC, logs ou sitemap)
    - Identifier les URLs **présentes dans l’index mais absentes du crawl** = pages orphelines

## **Que faire des pages orphelines ?**

Tout dépend de leur utilité :

- - - ✅ **Page pertinente mais oubliée ?**
      ➜ L’intégrer dans le maillage : lien contextuel, menu, sitemap
    - ❌ **Page obsolète, hors ligne ou inutile ?**
      ➜ La rediriger (301), ou la désindexer (noindex + suppression sitemap)
    - ⚠️ **Page en test ou en doublon ?**
      ➜ La traiter comme un cas spécifique : consolidation ou suppression

## **Bonnes pratiques pour éviter les pages orphelines**

- - - Maintenir une **arborescence claire et documentée**
    - Mettre à jour régulièrement les sitemaps XML
    - Automatiser les liens contextuels via taxonomies ou modules “articles liés”
    - Auditer les pages indexées tous les 3 à 6 mois
    - Ne jamais publier une page sans au moins un lien entrant
    - Mettre en place une stratégie de **maillage interne actif**

## **Outils recommandés**

| **Outil** | **Utilité principale** |
| --- | --- |
| Screaming Frog SEO Spider | Comparaison crawl vs sitemap |
| Google Search Console | Pages indexées, rapports de couverture |
| OnCrawl / Botify | Audit avancé des orphelines à grande échelle |
| Analytics + Logs serveur | Vérification de l’activité sur les pages |

## FAQ : Questions fréquentes sur les pages orphelines

  Une page orpheline peut-elle être bien positionnée ?

Oui, mais uniquement si elle reçoit des liens externes. Sans cela, son potentiel SEO est très limité.

   Faut-il supprimer toutes les pages orphelines ?

Non. Certaines peuvent être utiles, mais il faut au minimum les intégrer dans la structure de navigation si elles sont pertinentes.

   Comment éviter les pages orphelines en WordPress ?

En s’assurant que chaque nouvelle page est liée manuellement ou automatiquement (taxonomies, menus, modules contextuels), et en auditant régulièrement les pages indexées.



## **Aller plus loin**

- - - [Comprendre le maillage interne en SEO](/fr/ressources-seo/maillage-interne/)
    - [Comprendre le robots.txt](/fr/ressources-seo/fichier-robots-txt/)
    - [Optimiser votre budget de crawl](/fr/ressources-seo/budget-crawl/)

*Ce contenu a été rédigé par Antoine Blot, consultant SEO à Montréal, spécialisé dans l’optimisation des contenus pour les moteurs de recherche et les intelligences artificielles.*
