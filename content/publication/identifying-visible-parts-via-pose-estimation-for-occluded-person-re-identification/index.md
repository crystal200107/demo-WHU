---
title: Identifying Visible Parts via Pose Estimation for Occluded Person
  Re-Identification
publication_types:
  - "2"
authors:
  - Jiaxu Miao
  - Yu Wu
  - Yi Yang
publication: IEEE Transactions on Neural Networks and Learning Systems (TNNLS)
abstract: We focus on the occlusion problem in person re-identification (re-id),
  which is one of the main challenges in real-world person retrieval scenarios.
  Previous methods on the occluded re-id problem usually assume that only the
  probes are occluded, thereby removing occlusions by manually cropping.
  However, this may not always hold in practice. This paper relaxes this
  assumption and investigates a more general occlusion problem, where both the
  probe and gallery images could be occluded. The key to this challenging
  problem is depressing the noise information by identifying bodies and
  occlusions. We propose to incorporate the pose information into the re-id
  framework, which benefits the model in three aspects. First, it provides the
  location of the body. We then design a Pose-Masked Feature Branch to make our
  model focus on the body region only and filter those noise features brought by
  occlusions. Second, the estimated pose reveals which body parts are visible,
  giving us a hint to construct more informative person features. We propose a
  Pose-Embedded Feature Branch to adaptively re-calibrate channel-wise feature
  responses based on the visible body parts. Third, in testing, the estimated
  pose indicates which regions are informative and reliable for both probe and
  gallery images. Then we explicitly split the extracted spatial feature into
  parts. Only part features from those commonly visible parts are utilized in
  the retrieval. To better evaluate the performances of the occluded re-id, we
  also propose a large-scale dataset for the occluded re-id with more than
  35,000 images, namely Occluded-DukeMTMC.Extensive experiments show our
  approach surpasses previous methods on the occluded, partial, and non-occluded
  re-id datasets.
draft: false
featured: true
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-02-01T09:21:50.437Z
---
