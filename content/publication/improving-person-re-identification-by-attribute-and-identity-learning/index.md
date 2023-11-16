---
title: Improving Person Re-identification by Attribute and Identity Learning
publication_types:
  - "2"
authors:
  - Yutian Lin
  - Liang Zheng
  - Zhedong Zheng
  - Yu Wu
  - Zhilan Hu
  - Chenggang Yan
  - Yi Yang
publication: Pattern Recognition
abstract: Person re-identification (re-ID) and attribute recognition share a
  common target at learning pedestrian descriptions. Their difference consists
  in the granularity. Most existing re-ID methods only take identity labels of
  pedestrians into consideration. However, we find the attributes, containing
  detailed local descriptions, are beneficial in allowing the re-ID model to
  learn more discriminative feature representations. In this paper, based on the
  complementarity of attribute labels and ID labels, we propose an
  attribute-person recognition (APR) network, a multi-task network which learns
  a re-ID embedding and at the same time predicts pedestrian attributes. We
  manually annotate attribute labels for two large-scale re-ID datasets, and
  systematically investigate how person re-ID and attribute recognition benefit
  from each other. In addition, we re-weight the attribute predictions
  considering the dependencies and correlations among the attributes. The
  experimental results on two large-scale re-ID benchmarks demonstrate that by
  learning a more discriminative representation, APR achieves competitive re-ID
  performance compared with the state-of-the-art methods. We use APR to speed up
  the retrieval process by ten times with a minor accuracy drop of 2.92% on
  Market-1501. Besides, we also apply APR on the attribute recognition task and
  demonstrate improvement over the baselines.
draft: false
featured: true
url_pdf: https://www.sciencedirect.com/science/article/abs/pii/S0031320319302377?via%3Dihub#absh001
url_dataset: https://github.com/vana77/Market-1501_Attribute
url_code: https://github.com/vana77/Market-1501_Attribute
links:
  - name: Bibtex
    url: https://github.com/vana77/Market-1501_Attribute
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2019-01-01T08:35:26.458Z
---
