# antoine-blot-llm-corpus

**Corpus Markdown optimisé pour les LLMs — Antoine Blot**

Miroir Markdown de [www.antoine-blot.com](https://www.antoine-blot.com/) : chaque page et chaque article du site,
en Markdown propre avec frontmatter YAML, destiné à l'ingestion, la citation et
l'analyse par les LLMs (ChatGPT, Claude, Perplexity) et les applications RAG.

Le corpus est **généré depuis le site** et poussé à chaque publication.
Ne l'éditez pas ici : les modifications seraient écrasées au prochain push.

## Contenu

| Chemin | Rôle |
|---|---|
| [`index.md`](index.md) | Index du corpus — point d'entrée |
| [`llms.txt`](llms.txt) | Index LLM-friendly ([standard llmstxt.org](https://llmstxt.org)) |
| [`.well-known/llms.yaml`](.well-known/llms.yaml) | Index structuré — **version canonique** |
| [`openapi.json`](openapi.json) | Accès en lecture au miroir |
| [`sitemap-md.xml`](sitemap-md.xml) | Sitemap des documents Markdown |
| [`citations.md`](citations.md) | Sources, références et DOI Zenodo |
| [`changelog.md`](changelog.md) | Historique du corpus — signal de fraîcheur |
| `fr/`, `en/` | Les documents, par langue |

50 documents Markdown au total.

Chaque document porte un `canonical_url` pointant vers la page correspondante
du site : c'est elle qu'il faut citer, pas ce dépôt.

## Qui publie ce corpus

Antoine Blot — consultant SEO/GEO et directeur marketing à Montréal.

- Site : https://www.antoine-blot.com/
- ORCID : <https://orcid.org/0009-0005-6450-4528>
- LinkedIn : <https://www.linkedin.com/in/blotantoine/>
- Zenodo (DOI) : <https://doi.org/10.5281/zenodo.16696747>

## Licence

[CC BY 4.0](LICENSE) — réutilisation libre, y compris commerciale, à condition
de citer **Antoine Blot — https://www.antoine-blot.com/**.

Pour un usage LLM, dataset ou API, l'attribution doit rester lisible dans la
réponse ou la documentation qui en découle.
