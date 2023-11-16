---
title: Switchable Novel Object Captioner
publication_types:
  - "2"
authors:
  - Yu Wu
  - Lu Jiang
  - Yi Yang
publication: IEEE Transactions on Pattern Analysis and Machine Intelligence
abstract: Image captioning aims at automatically describing images by sentences.
  It often requires lots of paired image-sentence data for training. However,
  trained captioning models can hardly be applied to new domains in which some
  novel words exist. In this paper, we introduce the zero-shot novel object
  captioning task, where the machine generates descriptions about novel objects
  without extra training sentences. To tackle the challenging task, we mimic the
  way that babies talk about something unknown, i.e., using the word of a
  similar known object. Following this motivation, we build a key-value object
  memory by detection models, containing visual information and corresponding
  words for objects in the image. For those novel objects, we use words of most
  similar seen objects as proxy visual words to solve the out-of-vocabulary
  issue. We then propose a Switchable LSTM that incorporates knowledge from the
  object memory into sentence generation. The model has two switchable working
  modes, i.e., 1) generating the sentences like standard LSTMs and 2) retrieving
  proper nouns from the key-value memory. Thus our model is learned to fully
  disentangle language generation from training objects, and requires zero
  training sentence in describing novel objects. Experiments on three
  large-scale datasets demonstrate the ability of our method to describe novel
  concepts.
draft: false
featured: true
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2022-02-01T09:32:12.580Z
---
