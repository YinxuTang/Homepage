---
title: UniRel: Relation-Centric Knowledge Graph Question Answering with RL-Tuned LLM Reasoning
authors:
- admin
- Chengsong Huang
- Jiaxin Huang
- William Yeoh
date: "2026-02-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract:  Knowledge Graph Question Answering (KGQA) has largely focused on entity-centric queries that return a single answer entity. However, many real-world questions are inherently relational, aiming to understand how entities are associated rather than which entity satisfies a query. In this work, we introduce relation-centric KGQA, a complementary setting in which the answer is a subgraph that represents the semantic relations among entities. The main challenge lies in the abundance of candidate subgraphs, where trivial or overly common connections often obscure the identification of unique and informative answers. To tackle this, we propose UniRel, a unified modular framework that combines a subgraph retriever with an LLM fine-tuned using reinforcement learning. The framework uses a reward function to prefer compact and specific subgraphs with informative relations and low-degree intermediate entities. Experiments show that UniRel improves connectivity and reward over Prompting baselines and generalizes well to unseen entities and relations. Moreover, UniRel can be applied to conventional entity-centric KGQA, achieving competitive or improved performance in several settings.

# Summary. An optional shortened abstract.
<!-- summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. -->

tags:
- Source Themes
featured: false

links:
<!-- - name: Custom Link
  url: http://example.org -->
url_pdf: https://arxiv.org/pdf/2512.17043
<!-- url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes' -->
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

<!-- # Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
