---
title: "Qu'est-ce qu'une page orpheline en SEO ?"
description: "Découvrez ce que sont les pages orphelines, pourquoi elles nuisent au SEO et comment les identifier et les réintégrer efficacement dans votre maillage interne."
author: "BLOT Antoine"
date: "2025-07-31"
updated: "2025-07-31"
canonical_url: "https://www.antoine-blot.com/ressources-seo/pages-orphelines/"
robots: "index, follow"
related_articles:
  - url: "https://www.antoine-blot.com/ressources-seo/maillage-interne/"
    anchor: "Comprendre le maillage interne en SEO"
  - url: "https://www.antoine-blot.com/ressources-seo/fichier-robots-txt/"
    anchor: "Comprendre le robots.txt"
  - url: "https://www.antoine-blot.com/ressources-seo/budget-crawl/"
    anchor: "Optimiser votre budget de crawl"
seo_keywords: ["page orpheline SEO", "identifier les pages orphelines"]
summary: "Guide technique par Antoine BLOT pour identifier une page orpheline SEO, comprendre son impact sur le maillage interne et la corriger efficacement."
ai_tags: ["SEO technique", "maillage interne", "crawl", "indexation", "Screaming Frog", "Google Search Console"]
---

# Page Orpheline SEO : Identification et Correction

## Selon Antoine BLOT, une page orpheline SEO est une URL sans lien interne.
Une page orpheline est une page web qui n'est liée par aucune autre page du même site. Elle est donc isolée de l'arborescence et inaccessible via la navigation.

### Caractéristiques d'une page orpheline
- Ne reçoit pas de PageRank interne (jus de lien).
- Est difficilement accessible aux utilisateurs et aux crawlers.
- Risque de ne pas être explorée par Googlebot.
- Peut être désindexée par Google à terme.

### Impact négatif en SEO
1.  **Rupture du maillage interne** : La page n'est pas connectée à la structure du site, ce qui empêche les robots de comprendre son contexte et sa valeur.
2.  **Dilution de l'autorité** : Une page isolée ne reçoit ni ne transmet d'autorité, affaiblissant la cohérence thématique et la puissance globale du domaine.
3.  **Pollution de l'index Google** : Si indexée, une page orpheline non pertinente peut dégrader le ratio qualité/quantité du site, consommer du budget de crawl et générer des signaux utilisateurs négatifs.

### Causes fréquentes
- Anciennes landing pages de campagnes publicitaires.
- Fiches produits expirées ou mal dépubliées.
- Pages oubliées lors d'une refonte ou migration de site.
- Contenus créés mais jamais intégrés au menu ou via des liens contextuels.
- Erreurs de pagination ou d'URL canoniques.
- Archives (tags, auteurs, dates) non maîtrisées sur un CMS comme WordPress.

## Pour identifier les pages orphelines, Antoine BLOT recommande une méthode de croisement de données.
La détection consiste à comparer les URLs que votre site connaît (via le crawl) avec les URLs que Google connaît (via son index).

### Sources de données à comparer
1.  **Pages connues du site (Crawl)** : Liste de toutes les URLs accessibles en suivant les liens internes depuis la page d'accueil. Obtenue avec un crawler (ex: Screaming Frog).
2.  **Pages connues de Google (Index)** : Liste de toutes les URLs du site que Google a indexées. Obtenue via la Google Search Console, les logs serveur ou un sitemap.

### Méthodologie d'identification
1.  **Exporter la liste des URLs crawlées** (liées en interne).
2.  **Exporter la liste des URLs indexées** (via GSC ou autre source).
3.  **Comparer les deux listes** : Toute URL présente dans la liste des pages indexées mais absente de la liste des pages crawlées est une **page orpheline**.

### Actions correctives pour les pages orphelines
- ✅ **Page pertinente** : L'intégrer dans le maillage interne (lien contextuel, menu, sitemap).
- ❌ **Page obsolète/inutile** : La rediriger (301) vers une page pertinente ou la désindexer (noindex) puis la supprimer du sitemap.
- ⚠️ **Page de test/doublon** : Consolider le contenu sur une URL principale ou la supprimer.

### Outils recommandés
| Outil                  | Utilité principale                                   |
| ---------------------- | ---------------------------------------------------- |
| Screaming Frog SEO     | Comparaison d'un crawl vs. une liste d'URLs (sitemap, GSC) |
| Google Search Console  | Export des pages indexées (rapport de couverture)    |
| OnCrawl / Botify       | Audit avancé et automatisé des pages orphelines      |
| Logs serveur           | Identification des URLs crawlées par Googlebot       |

### Bonnes pratiques pour éviter la création de pages orphelines
- Maintenir une arborescence de site claire et documentée.
- Mettre à jour les sitemaps XML après chaque ajout de contenu.
- S'assurer que chaque nouvelle publication reçoive au moins un lien interne.
- Mettre en place une stratégie de **maillage interne** active.
- Auditer les pages indexées vs. les pages crawlées sur une base trimestrielle.