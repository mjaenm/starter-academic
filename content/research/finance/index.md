---
title:  R&D applications in quantitative finance, trading and financial markets
summary: 
tags:
- Computational finance
date: "2018-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/mjaenm
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
## Summary:
We tackled a ​portfolio compression problem, which consisted of: given a fixed set of deals with a specific sensitivity (delta) value, to find the smallest basket of deals with the same delta from a big pool of internal live trades. The external version of this problem (trades agreed between a network of banks) was solved using a vendor solution (TriOptima). Under our own initiative we modeled this problem and it turned out that it resembles the ​subset-sum problem family, which is known to be NP-complete. We applied a tailored optimization method found in the computational finance literature to get an approximate solution