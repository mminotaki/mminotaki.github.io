---
title: "A generalized model for estimating adsorption energies of single atoms on doped carbon materials"
authors:
- admin
date: "2024-03-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Single metal atoms on doped carbons constitute a new class of extremely appealing materials, as they present the best metal utilization for catalysis. However, their stability can be compromised by metal aggregation and the formation of nanoparticles, which often results in reduced activity or even catalyst deactivation. In many cases, the carbon hosts are generated via thermal processes, leading to poorly controlled materials. This causes a structural and compositional diversity that is modeled via indirect procedures and by comparison to a collection of structural models with different compositions. Our aim in this work is to develop a general framework based on machine learning techniques to determine the stability of the different structures against aggregation as nanoparticles. Here, we built machine learning models for the cavities and identified the robust features characterizing the metal–support interaction, considering different heteroatoms in the decorative cavity and single metal atoms. The descriptors presented here are accessible and cost-effective, such as the cavity size, electronegativity of the metal and heteroatoms, different covalent radii, and the metal electronic density. These can then be employed in the search for a mathematical equation that describes the adsorption energy via the Bayesian machine scientist. The algorithm is able to separate coordination, and covalent and ionic contributions expressed by the descriptors. This approach paves the way towards general modeling of single atoms in modified carbons particularly addressing one of the crucial features, stability.

# Summary. An optional shortened abstract.
summary:
  - ML workflow for single-atom catalyst stability.
  - DFT simulations automation, data analysis, and feature engineering.
  - Regression models to predict adsorption energies and extract physical insights.
  


#tags:
#- Machine learning for single-atom catalysts stability

featured: true

links:
- name: "J. Mater. Chem. A, 2024, 12, 11049–11061, DOI: 10.1039/D3TA05898K"
  url: https://pubs.rsc.org/en/content/articlelanding/2024/ta/d3ta05898k
#url_pdf: http://arxiv.org/pdf/1512.04133v1
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Royal Society of Chemistry**](https://pubs.rsc.org/en/content/articlelanding/2024/ta/d3ta05898k)'
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
#slides: example
#---

#This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

#{{% callout note %}}
#Create your slides in Markdown - click the *Slides* button to check out the example.
#{{% /callout %}}

#Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including  [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
