---
title: "Shapley meets uniform: An axiomatic framework for attribution in online advertising"
authors:
- rsingal
- Omar Besbes
- Antoine Desir
- Vineet Goyal
- admin

date: ""
doi: ""


# Schedule page publish date (NOT publication's date).
publishDate: "2019-05-22"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: Working Paper
# publication_short: Working Paper

abstract: One of the central challenges in online advertising is attribution, namely, assessing the contribution of individual advertiser actions including e-mails, display ads and search ads to eventual conversion. Several heuristics are used for attribution in practice; however, there is no formal justification for them and many of these fail even in simple canonical settings. The main contribution in this work is to develop an axiomatic framework for attribution in online advertising. In particular, we consider a Markovian model for the user journey through the conversion funnel, in which ad actions may have disparate impacts at different stages. We propose a novel attribution metric, that we refer to as counterfactual adjusted Shapley value, which inherits the desirable properties of the traditional Shapley value while overcoming its shortcomings in the context of our application. Furthermore, we establish that this metric coincides with an adjusted "unique-uniform" attribution scheme. This scheme is efficiently implementable and can be interpreted as a correction to the commonly used uniform attribution scheme. We supplement our theoretical developments with numerical experiments inspired by a real-world large-scale dataset.

# Summary. An optional shortened abstract.
# summary:

# tags:
# - Source Themes
# featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3392721
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- attribution

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- Supplementary notes can be added here, including [code and
math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->
