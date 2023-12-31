---
title: Decoupled Novel Object Captioner
publication_types:
  - "1"
authors:
  - Yu Wu
  - Linchao Zhu
  - Lu Jiang
  - Yi Yang
author_notes: []
publication: ACM-MM
abstract: >-
  Image captioning is a challenging task where the machine automatically
  describes an image by sentences or phrases. It often requires a large number
  of paired image-sentence annotations for training. However, a pre-trained
  captioning model can hardly be applied to a new domain in which some novel
  object categories exist, i.e., the objects and their description words are
  unseen during model training. To correctly caption the novel object, it
  requires professional human workers to annotate the images by sentences with
  the novel words. It is labor expensive and thus limits its usage in real-world
  applications.


  In this paper, we introduce the zero-shot novel object captioning task where the machine generates descriptions without extra sentences about the novel object. To tackle the challenging problem, we propose a Decoupled Novel Object Captioner (DNOC) framework that can fully decouple the language sequence model from the object descriptions. DNOC has two components. 1) A Sequence Model with the Placeholder (SM-P) generates a sentence containing placeholders. The placeholder represents an unseen novel object. Thus, the sequence model can be decoupled from the novel object descriptions. 2) A key-value object memory built upon the freely available detection model, contains the visual information and the corresponding word for each object. The SM-P will generate a query to retrieve the words from the object memory. The placeholder will then be filled with the correct word, resulting in a caption with novel object descriptions. The experimental results on the held-out MSCOCO dataset demonstrate the ability of DNOC in describing novel concepts in the zero-shot novel object captioning task.
draft: false
featured: true
url_pdf: https://dl.acm.org/doi/10.1145/3240508.3240640
url_dataset: https://github.com/Yu-Wu/DukeMTMC-VideoReID](https://github.com/Yu-Wu/Decoupled-Novel-Object-Captioner
links:
  - name: Bibtex
    url: https://yu-wu.net/bibtexs/mm2018-DNOC.txt
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2018-02-01T07:10:00.000Z
---
