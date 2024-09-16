---
title: "ModsNet: Performance-aware Top-𝑘 Model Search using Exemplar Datasets"
authors:
  - Mengying Wang
  - Sheng Guan
  - Hanchao Ma
  - admin
  - Haolai Che
  - Abhishek Daundkar
  - Alp Sehirlioglu
  - Yinghui Wu
date: "2024-01-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Very Large Data Bases*
publication_short: In *VLDB*

abstract: We demonstrate ModsNet, a search tool for pre-trained data science MODels recommendatioN using Examplar daTaset. Given a set of pre-trained data science models, an “example” input dataset, and a user-specified performance metric, ModsNet answers the following query "what are top-k models that have the best expected performance for the input data?” The need for searching high-quality
pre-trained models is evident in data-driven analysis. Inspired by "query by example” paradigm, ModsNet does not require users to write complex queries, but only provide an "examplar" dataset, a task description, and a performance measure as input, and can automatically suggest top-𝑘 matching models that are expected to have desirable performance to perform the task over the provided sample dataset. ModsNet utilizes a knowledge graph to integrate model performances over datasets and synchronizes it with a bipartite graph neural network to estimate model performance, reduce
inference cost, and promptly respond to top-𝑘 model search queries. To cope with strict cold-start (upon receiving a new dataset when no historical performance of registered models are observed), it performs a dynamic, cost-bounded “probe-and-select” strategy to incrementally identify promising models. We demonstrate the application of ModsNet in enabling efficient scientific data analysis.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Data Managemnt Systems
  - Information Retrieval

featured: true

# links:
#   - name: Custom Link
#     url: http://example.org

url_pdf: "https://dl.acm.org/doi/pdf/10.1145/3511808.3557194"
url_code: ""
url_dataset: ""
url_poster: ""
url_project: "https://crux-project.github.io/"
url_slides: "https://dl.acm.org/doi/pdf/10.1145/3511808.3557194"
url_source: ""
url_video: "https://dl.acm.org/doi/pdf/10.1145/3511808.3557194"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)"
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

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
