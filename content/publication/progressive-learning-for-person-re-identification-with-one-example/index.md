---
title: Progressive Learning for Person Re-Identification with One Example
publication_types:
  - "2"
authors:
  - Yu Wu
  - Yutian Lin
  - Xuanyi Dong
  - Yan Yan
  - Wei Bian
  - Yi Yang
publication: EEE Transactions on Image Processing (TIP)
abstract: In this paper, we focus on the one-example person re-identiﬁcation
  (re-ID) task, where each identity has only one labeled example along with many
  unlabeled examples. We propose a progressive framework which gradually
  exploits the unlabeled data for person re-ID. In this framework, we
  iteratively (1) update the Convolutional Neural Network (CNN) model and (2)
  estimate pseudo labels for the unlabeled data. We split the training data into
  three parts, i.e., labeled data, pseudo-labeled data, and index- labeled data.
  Initially, the re-ID model is trained using the labeled data. For the
  subsequent model training, we update the CNN model by the joint training on
  the three data parts. The proposed joint training method can optimize the
  model by both the data with labels (or pseudo labels) and the data without any
  reliable labels. For the label estimation step, instead of using a static
  sampling strategy, we propose a progressive sampling strategy to increase the
  number of the selected pseudo-labeled candidates step by step. We select a few
  candidates with most reliable pseudo labels from unlabeled examples as the
  pseudo-labeled data, and keep the rest as index-labeled data by assigning them
  with the data indexes. During iterations, the index-labeled data are
  dynamically transferred to pseudo-labeled data. Notably, the rank-1 accuracy
  of our method outperforms the state-of-the-art method by 21.6 points
  (absolute, i.e., 62.8% vs. 41.2%) on MARS, and 16.6 points on
  DukeMTMC-VideoReID. Extended to the few-example setting, our approach with
  only 20% labeled data surprisingly achieves comparable performance to the
  supervised state-of-the-art method with 100% labeled data.
draft: false
featured: true
url_pdf: https://yu-wu.net/pdf/TIP2019_One-Example-reID.pdf
url_dataset: https://github.com/Yu-Wu/One-Example-Person-ReID
url_code: https://github.com/Yu-Wu/One-Example-Person-ReID
links:
  - name: Bibtex
    url: https://yu-wu.net/bibtexs/tip2019-reid.txt
  - name: IEEE
    url: https://ieeexplore.ieee.org/document/8607049
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2019-01-01T08:25:36.396Z
---
