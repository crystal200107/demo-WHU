---
title: Learning to Anticipate Egocentric Actions by Imagination
publication_types:
  - "2"
authors:
  - Yu Wu
  - Linchao Zhu
  - Xiaohan Wang
  - Yi Yang
  - Fei Wu
publication: IEEE Transactions on Image Processing (TIP)
abstract: Anticipating actions before they are executed is crucial for a wide
  range of practical applications, including autonomous driving and robotics. In
  this paper, we study the egocentric action anticipation task, which predicts
  future action seconds before it is performed for egocentric videos. Previous
  approaches focus on summarizing the observed content and directly predicting
  future action based on past observations. We believe it would beneﬁt the
  action anticipation if we could mine some cues to compensate for the missing
  information of the unobserved frames. We then propose to decompose the action
  anticipation into a series of future feature predictions. We imagine how the
  visual feature changes in the near future and then predicts future action
  labels based on these imagined representations. Differently, our ImagineRNN is
  optimized in a contrastive learning way instead of feature regression. We
  utilize a proxy task to train the ImagineRNN, i.e., selecting the correct
  future states from distractors. We further improve ImagineRNN by residual
  anticipation, i.e., changing its target to predicting the feature difference
  of adjacent frames instead of the frame content. This promotes the network to
  focus on our target, i.e., the future action, as the difference between
  adjacent frame features is more important for forecasting the future.
  Extensive experiments on two large-scale egocentric action datasets validate
  the effectiveness of our method. Our method signiﬁcantly outperforms previous
  methods on both the seen test set and the unseen test set of the EPIC Kitchens
  Action Anticipation Challenge.
draft: false
featured: true
url_pdf: https://yu-wu.net/pdf/TIP2020_Anticipation.pdf
links:
  - name: Bibtex
    url: https://yu-wu.net/bibtexs/tip2020-anticipation.txt
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-02-01T09:24:38.363Z
---
