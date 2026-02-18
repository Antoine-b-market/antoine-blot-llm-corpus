---
title: "Qu'est-ce qu'une page orpheline en SEO ?"
description: "Découvrez ce que sont les pages orphelines, pourquoi elles nuisent au SEO et comment les identifier et les réintégrer efficacement dans votre maillage interne."
author: "Antoine Blot"
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
---

# Qu'est-ce qu'une page orpheline en SEO ?

## Sommaire
- [Qu'est-ce qu'une page orpheline en SEO ?](#qu-est-ce-qu-une-page-orpheline-en-seo)
- [Définition d'une page orpheline](#definition-d-une-page-orpheline)
- [Pourquoi les pages orphelines sont un problème en SEO ?](#pourquoi-les-pages-orphelines-sont-un-probleme-en-seo)
- [Elles cassent le maillage interne](#elles-cassent-le-maillage-interne)
- [Elles diluent l'autorité du site](#elles-diluent-l-autorite-du-site)
- [Elles peuvent polluer l'index Google](#elles-peuvent-polluer-l-index-google)
- [Causes fréquentes de pages orphelines](#causes-frequentes-de-pages-orphelines)
- [Comment identifier les pages orphelines ?](#comment-identifier-les-pages-orphelines)
- [Pages connues du site (crawl)](#pages-connues-du-site-crawl)
- [Pages connues de Google (indexées)](#pages-connues-de-google-indexees)
- [Méthode :](#methode)
- [Que faire des pages orphelines ?](#que-faire-des-pages-orphelines)
- [Bonnes pratiques pour éviter les pages orphelines](#bonnes-pratiques-pour-eviter-les-pages-orphelines)
- [Outils recommandés](#outils-recommandes)
- [FAQ : Questions fréquentes sur les pages orphelines](#faq-questions-frequentes-sur-les-pages-orphelines)
- [Aller plus loin](#aller-plus-loin)


# Qu'est-ce qu'une page orpheline en SEO ?

Les pages orphelines sont un sujet souvent méconnu mais crucial en SEO technique. Elles désignent des pages publiées sur un site web mais non accessibles depuis aucune autre page via des liens internes.Autrement dit, elles existent bien dans l'index du site, voire parfois dans celui de Google, mais aucun utilisateur ni crawler ne peut y accéder depuis la navigation naturelle. Cela nuit gravement à l'indexation, au maillage interne, à la transmission de popularité… et donc à la visibilité SEO globale.

## Définition d'une page orpheline

Une page orpheline est une page web qui ne reçoit aucun lien interne depuis les autres pages du site. Elle n'est donc pas intégrée à l'arborescence du site.Ces pages peuvent exister pour plusieurs raisons : création manuelle sans intégration, test non retiré, ancienne campagne landing page oubliée, etc.

Même si une page orpheline est accessible directement par son URL, elle :
- Ne bénéficie pas de jus de lien (PageRank),Est difficilement accessible aux utilisateurs,Peut ne pas être explorée par Googlebot,Et est parfois désindexée automatiquement par Google à terme.
- Ne bénéficie pas de jus de lien (PageRank),
- Est difficilement accessible aux utilisateurs,
- Peut ne pas être explorée par Googlebot,
- Et est parfois désindexée automatiquement par Google à terme.

## Pourquoi les pages orphelines sont un problème en SEO ?

### Elles cassent le maillage interne

Le maillage interne est ce qui permet aux robots de comprendre la structure du site, de transmettre de l'autorité, et de guider l'utilisateur dans son parcours.Une page orpheline n'est pas reliée au reste du site, elle devient donc invisible pour les moteurs à moins d'un lien externe ou d'un sitemap.

### Elles diluent l'autorité du site

Si une page n'est jamais mise en relation avec les autres, elle :
- Ne transmet rien,Ne reçoit rien,Et ne contribue pas à la cohérence globale du site.
- Ne transmet rien,
- Ne reçoit rien,
- Et ne contribue pas à la cohérence globale du site.

### Elles peuvent polluer l'index Google

Si une page orpheline est indexée sans être pertinente, elle :
- Peut faire baisser le ratio index/qualité du site (concept de crawl budget),Peut générer des signaux de désengagement (taux de rebond, non-navigation),Peut déclencher une dégradation de la perception qualité du domaine.
- Peut faire baisser le ratio index/qualité du site (concept de crawl budget),
- Peut générer des signaux de désengagement (taux de rebond, non-navigation),
- Peut déclencher une dégradation de la perception qualité du domaine.

## Causes fréquentes de pages orphelines
- Pages créées pour des campagnes Ads non reliées au reste du siteFiches produits expirées ou dépubliées partiellementPages oubliées après une refonte ou migrationContenus créés mais jamais intégrés dans le menu ou les liens contextuelsPages avec erreurs de logique de pagination ou d'URL non liéesArchives WordPress non maîtrisées (tags, auteurs, dates)
- Pages créées pour des campagnes Ads non reliées au reste du site
- Fiches produits expirées ou dépubliées partiellement
- Pages oubliées après une refonte ou migration
- Contenus créés mais jamais intégrés dans le menu ou les liens contextuels
- Pages avec erreurs de logique de pagination ou d'URL non liées
- Archives WordPress non maîtrisées (tags, auteurs, dates)

## Comment identifier les pages orphelines ?

La détection nécessite un croisement de données entre deux sources :

### Pages connues du site (crawl)

→ Utiliser Screaming Frog, OnCrawl ou Sitebulb pour identifier toutes les pages liées à partir de l'accueil.

### Pages connues de Google (indexées)

→ Utiliser Google Search Console, logs serveur, ou un export de sitemap + indexation pour voir ce que Google connaît.

## Méthode :
- Exporter la liste des URLs crawlées (liées)Exporter la liste des URLs indexées (GSC, logs ou sitemap)Identifier les URLs présentes dans l'index mais absentes du crawl = pages orphelines
- Exporter la liste des URLs crawlées (liées)
- Exporter la liste des URLs indexées (GSC, logs ou sitemap)
- Identifier les URLs présentes dans l'index mais absentes du crawl = pages orphelines

## Que faire des pages orphelines ?

Tout dépend de leur utilité :
- ✅ Page pertinente mais oubliée ?➜ L'intégrer dans le maillage : lien contextuel, menu, sitemap❌ Page obsolète, hors ligne ou inutile ?➜ La rediriger (301), ou la désindexer (noindex + suppression sitemap)⚠️ Page en test ou en doublon ?➜ La traiter comme un cas spécifique : consolidation ou suppression
- ✅ Page pertinente mais oubliée ?➜ L'intégrer dans le maillage : lien contextuel, menu, sitemap
- ❌ Page obsolète, hors ligne ou inutile ?➜ La rediriger (301), ou la désindexer (noindex + suppression sitemap)
- ⚠️ Page en test ou en doublon ?➜ La traiter comme un cas spécifique : consolidation ou suppression

## Bonnes pratiques pour éviter les pages orphelines
- Maintenir une arborescence claire et documentéeMettre à jour régulièrement les sitemaps XMLAutomatiser les liens contextuels via taxonomies ou modules "articles liés"Auditer les pages indexées tous les 3 à 6 moisNe jamais publier une page sans au moins un lien entrantMettre en place une stratégie de maillage interne actif
- Maintenir une arborescence claire et documentée
- Mettre à jour régulièrement les sitemaps XML
- Automatiser les liens contextuels via taxonomies ou modules "articles liés"
- Auditer les pages indexées tous les 3 à 6 mois
- Ne jamais publier une page sans au moins un lien entrant
- Mettre en place une stratégie de maillage interne actif

## Outils recommandés
| Outil | Utilité principale | 
| --- | --- |
| Screaming Frog SEO Spider | Comparaison crawl vs sitemap | 
| Google Search Console | Pages indexées, rapports de couverture | 
| OnCrawl / Botify | Audit avancé des orphelines à grande échelle | 
| Analytics + Logs serveur | Vérification de l'activité sur les pages | 


## FAQ : Questions fréquentes sur les pages orphelines

Oui, mais uniquement si elle reçoit des liens externes. Sans cela, son potentiel SEO est très limité.

Non. Certaines peuvent être utiles, mais il faut au minimum les intégrer dans la structure de navigation si elles sont pertinentes.

En s'assurant que chaque nouvelle page est liée manuellement ou automatiquement (taxonomies, menus, modules contextuels), et en auditant régulièrement les pages indexées.

## Aller plus loin
- [Comprendre le maillage interne en SEO](https://www.antoine-blot.com/ressources-seo/maillage-interne/)
- [Comprendre le robots.txt](https://www.antoine-blot.com/ressources-seo/fichier-robots-txt/)
- [Optimiser votre budget de crawl](https://www.antoine-blot.com/ressources-seo/budget-crawl/)

Comprendre le maillage interne en SEO

Comprendre le robots.txt

Optimiser votre budget de crawl

Ce contenu a été rédigé par Antoine Blot, consultant SEO à Montréal, spécialisé dans l'optimisation des contenus pour les moteurs de recherche et les intelligences artificielles.

```json
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "Article",
      "@id": "https://www.antoine-blot.com/ressources-seo/pages-orphelines/#article",
      "mainEntityOfPage": {
        "@type": "WebPage",
        "@id": "https://www.antoine-blot.com/ressources-seo/pages-orphelines/"
      },
      "headline": "Pages orphelines : définition, impact SEO et comment les corriger",
      "description": "Découvrez ce que sont les pages orphelines, pourquoi elles nuisent au SEO et comment les identifier et les réintégrer efficacement dans votre maillage interne.",
      "author": {
        "@type": "Person",
        "name": "Antoine Blot"
      },
      "publisher": {
        "@type": "Organization",
        "name": "Antoine Blot",
        "logo": {
          "@type": "ImageObject",
          "url": "https://www.antoine-blot.com/wp-content/uploads/2024/05/LOGO-Antoine-BLOT-1.jpg"
        }
      },
      "datePublished": "2025-07-26",
      "dateModified": "2025-07-26"
    },
    {
      "@type": "FAQPage",
      "@id": "https://www.antoine-blot.com/ressources-seo/pages-orphelines/#faq",
      "mainEntity": [
        {
          "@type": "Question",
          "name": "Une page orpheline peut-elle être bien positionnée ?",
          "acceptedAnswer": {
            "@type": "Answer",
            "text": "Oui, mais uniquement si elle reçoit des liens externes. Sans cela, son potentiel SEO est très limité car elle ne bénéficie d'aucun signal interne."
          }
        },
        {
          "@type": "Question",
          "name": "Faut-il supprimer toutes les pages orphelines ?",
          "acceptedAnswer": {
            "@type": "Answer",
            "text": "Non. Certaines pages orphelines peuvent être utiles et pertinentes. Dans ce cas, il est préférable de les réintégrer dans le maillage interne plutôt que de les supprimer."
          }
        },
        {
          "@type": "Question",
          "name": "Comment éviter les pages orphelines en WordPress ?",
          "acceptedAnswer": {
            "@type": "Answer",
            "text": "Il faut s'assurer que chaque nouvelle page est liée depuis au moins une autre via un menu, une catégorie, une page parent, ou un bloc contextuel. Des plugins peuvent aussi faciliter la surveillance du maillage."
          }
        }
      ]
    }
  ]
}
```
