---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Discovering Digital Tumor Signatures—Using Latent Code Representations to Manipulate
  and Classify Liver Lesions
subtitle: ''
summary: ''
authors:
- Jens Kleesiek
- Benedikt Kersjes
- Kai Ueltzhöffer
- Jacob M. Murray
- Carsten Rother
- Ullrich Köthe
- Heinz-Peter Schlemmer
tags: []
categories: []
date: '2021-06-01'
lastmod: 2022-01-11T22:09:31+01:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-01-11T21:09:31.095684Z'
publication_types:
- '2'
abstract: Modern generative deep learning (DL) architectures allow for unsupervised
  learning of latent representations that can be exploited in several downstream tasks.
  Within the ﬁeld of oncological medical imaging, we term these latent representations
  d̈igital tumor signaturesänd hypothesize that they can be used, in analogy to radiomics
  features, to differentiate between lesions and normal liver tissue. Moreover, we
  conjecture that they can be used for the generation of synthetic data, speciﬁcally
  for the artiﬁcial insertion and removal of liver tumor lesions at user-deﬁned spatial
  locations in CT images. Our approach utilizes an implicit autoencoder, an unsupervised
  model architecture that combines an autoencoder and two generative adversarial network
  (GAN)-like components. The model was trained on liver patches from 25 or 57 inhouse
  abdominal CT scans, depending on the experiment, demonstrating that only minimal
  data is required for synthetic image generation. The model was evaluated on a publicly
  available data set of 131 scans. We show that a PCA embedding of the latent representation
  captures the structure of the data, providing the foundation for the targeted insertion
  and removal of tumor lesions. To assess the quality of the synthetic images, we
  conducted two experiments with ﬁve radiologists. For experiment 1, only one rater
  and the ensemble-rater were marginally above the chance level in distinguishing
  real from synthetic data. For the second experiment, no rater was above the chance
  level. To illustrate that the “digital signatures” can also be used to differentiate
  lesion from normal tissue, we employed several machine learning methods. The best
  performing method, a LinearSVM, obtained 95% (97%) accuracy, 94% (95%) sensitivity,
  and 97% (99%) speciﬁcity, depending on if all data or only normal appearing patches
  were used for training of the implicit autoencoder. Overall, we demonstrate that
  the proposed unsupervised learning paradigm can be utilized for the removal and
  insertion of liver lesions at user deﬁned spatial locations and that the digital
  signatures can be used to discriminate between lesions and normal liver tissue in
  abdominal CT scans.
publication: '*Cancers*'
doi: 10.3390/cancers13133108
links:
- name: URL
  url: https://www.mdpi.com/2072-6694/13/13/3108
---
