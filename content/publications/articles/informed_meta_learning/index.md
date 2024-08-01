---
title: 'Informed Meta-Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Mihaela van der Schaar

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-02-25T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2402.16105'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-02-25-T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In SPIGM and MFHAIA workshops at ICML 2024
#publication_short: In *ICW*

abstract: In noisy and low-data regimes prevalent in real-world applications, a key challenge of machine learning lies in effectively incorporating inductive biases that promote data efficiency and robustness. Meta-learning and informed ML stand out as two approaches for incorporating prior knowledge into ML pipelines. While the former relies on a purely data-driven source of priors, the latter is guided by prior domain knowledge. In this paper, we formalise a hybrid paradigm, informed meta-learning, facilitating the incorporation of priors from unstructured knowledge representations, such as natural language; thus, unlocking complementarity in cross-task knowledge sharing of humans and machines. We establish the foundational components of informed meta-learning and present a concrete instantiation of this framework--the Informed Neural Process. Through a series of experiments, we demonstrate the potential benefits of informed meta-learning in improving data efficiency, robustness to observational noise and task distribution shifts.

# Summary. An optional shortened abstract.
summary: We introduce the paradigm of informed meta-learning, a novel approach to inductive bias specification based on human knowledge represented in any form, including unstructured natural language.

tags: [meta-learning, informed machine learning, human knowledge]


# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: PDF
  url: 'publications/articles/informed_meta_learning/paper.pdf'
- name: arXiv
  url: https://arxiv.org/abs/2402.16105
- name: ICML workshop poster 
  url:  'publications/articles/informed_meta_learning/workshop_poster.pdf'


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

![imgage](featured.png)

In noisy and low-data regimes prevalent in real-world applications, a key challenge of machine learning lies in effectively incorporating inductive biases that promote data efficiency and robustness. Meta-learning and informed ML stand out as two approaches for incorporating prior knowledge into ML pipelines. While the former relies on a purely data-driven source of priors, the latter is guided by prior domain knowledge. In this paper, we formalise a hybrid paradigm, informed meta-learning, facilitating the incorporation of priors from unstructured knowledge representations, such as natural language; thus, unlocking complementarity in cross-task knowledge sharing of humans and machines. We establish the foundational components of informed meta-learning and present a concrete instantiation of this framework--the Informed Neural Process. Through a series of experiments, we demonstrate the potential benefits of informed meta-learning in improving data efficiency, robustness to observational noise and task distribution shifts.