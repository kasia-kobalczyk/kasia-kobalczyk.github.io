---
title: 'cegpy: Modelling with chain event graphs in Python'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Gareth Walley
  - Aditi Shenvi
  - Peter Strong 
  - admin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-08-15T00:00:00Z'
doi: 'https://doi.org/10.1016/j.knosys.2023.110615'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-08-15-T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Knowledge-Based Systems*
#publication_short: In *ICW*

abstract: Chain event graphs (CEGs) are a recent family of probabilistic graphical models that generalise the popular Bayesian networks (BNs) family. Crucially, unlike BNs, a CEG is able to embed, within its graph and its statistical model, asymmetries exhibited by a process. These asymmetries might be in the conditional independence relationships or in the structure of the graph and its underlying event space. Structural asymmetries are common in many domains, and can occur naturally (e.g. a defendant vs prosecutor’s version of events) or by design (e.g. a public health intervention). Whilst two CEG packages exist in R for modelling processes with asymmetric conditional independencies, there currently exists no software that allows a user to leverage the theoretical developments of the CEG model family in modelling processes with structural asymmetries. In this paper, we present cegpy—the first Python implementation of CEGs and the first across all languages to support structurally asymmetric processes. cegpy contains an implementation of Bayesian learning and probability propagation algorithms for CEGs. We illustrate the functionality of cegpy using a structurally asymmetric dataset.

# Summary. An optional shortened abstract.
summary: Chain event graphs (CEGs) are a recent family of probabilistic graphical models that generalise the popular Bayesian networks (BNs) family. In this paper, we present cegpy—the first Python implementation of CEGs and the first across all languages to support structurally asymmetric processes. 

tags: [Knowledge-Based Systems, Bayesian Inference, Graphical Models]


# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
# - name: ScienceDirect
#   url: 'https://www.sciencedirect.com/science/article/pii/S0950705123003659?utm_campaign=STMJ_AUTH_SERV_PUBLISHED&utm_medium=email&utm_acid=274721439&SIS_ID=&dgcid=STMJ_AUTH_SERV_PUBLISHED&CMX_ID=&utm_in=DM370924&utm_source=AC_'
- name: PDF
  url: 'publications/articles/cegpy/cegpy-main.pdf'
- name: Code
  url: 'https://github.com/g-walley/cegpy'
- name: Docs
  url: 'https://cegpy.readthedocs.io/en/stable/intro.html'


#url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

![imgage](cegpy.png)

Chain event graphs (CEGs) are a recent family of probabilistic graphical models that generalise the popular Bayesian networks (BNs) family. Crucially, unlike BNs, a CEG is able to embed, within its graph and its statistical model, asymmetries exhibited by a process. These asymmetries might be in the conditional independence relationships or in the structure of the graph and its underlying event space. Structural asymmetries are common in many domains, and can occur naturally (e.g. a defendant vs prosecutor’s version of events) or by design (e.g. a public health intervention). Whilst two CEG packages exist in R for modelling processes with asymmetric conditional independencies, there currently exists no software that allows a user to leverage the theoretical developments of the CEG model family in modelling processes with structural asymmetries. In this paper, we present cegpy—the first Python implementation of CEGs and the first across all languages to support structurally asymmetric processes. cegpy contains an implementation of Bayesian learning and probability propagation algorithms for CEGs. We illustrate the functionality of cegpy using a structurally asymmetric dataset.