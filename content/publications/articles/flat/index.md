---
title: 'Tabular Few-Shot Generalization Across Heterogenous Feature Spaces'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- in review
  - Max Zhu
  - admin
  - Andrija Petrovic
  - Mladen Nikolic
  - Mihaela van der Schaar
  - Pietro Lio
  - Boris Delibašić

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-09-22T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2311.1005'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-08-22T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: 'arXiv'
publication_short: 'arXiv'

abstract: Despite the prevalence of tabular datasets, learning with just a few labelled examples remains an under-explored area of research. Existing few-shot learning methods are not directly applicable to tabular datasets due to the variation in the relationships between the columns, their underlying meanings, and their permutational invariance. To address these challenges, we propose FLAT—the first solution for the generalized problem of tabular few-shot learning, including the critical aspect of knowledge sharing between datasets with heterogenous sets of columns. Using a Dataset2Vec-inspired encoder, FLAT learns a low-dimensional embedding space of tabular datasets and their individual columns that captures the key characteristics of datasets; this enables knowledge transfer and generalization to previously unseen datasets. Based on the embedding of a new dataset, a decoder network generates the parameters of the predictive target network. To handle the varying number of features, their permutational invariance and structural relationship, we implement the target network as a Graph Attention Network. Using a collection of datasets from the UCI Machine Learning Repository, we demonstrate successful generalization to different tabular datasets and a considerable improvement over existing baselines.

# Summary. An optional shortened abstract.
summary: We introduce new tabular few-shot learning solution capable of knowledge sharing between datasets with heterogenous sets of columns.

tags: [in review, meta-learning, few-shot learning, tabular data]


# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
# - name: Code
#   url: 'https://github.com/Maccy-Z/FairFewshot'
- name: arXiv
  url: 'https://arxiv.org/abs/2311.10051'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: true

---
![imgage](featured.jpg)
  Despite the prevalence of tabular datasets, few-shot learning remains under-explored within this domain. Existing few-shot methods are not directly applicable to tabular datasets due to varying column relationships, meanings, and permutational invariance. To address these challenges, we propose FLAT-a novel approach to tabular few-shot learning, encompassing knowledge sharing between datasets with heterogeneous feature spaces. Utilizing an encoder inspired by Dataset2Vec, FLAT learns low-dimensional embeddings of datasets and their individual columns, which facilitate knowledge transfer and generalization to previously unseen datasets. A decoder network parametrizes the predictive target network, implemented as a Graph Attention Network, to accommodate the heterogeneous nature of tabular datasets. Experiments on a diverse collection of 118 UCI datasets demonstrate FLAT's successful generalization to new tabular datasets and a considerable improvement over the baselines.

