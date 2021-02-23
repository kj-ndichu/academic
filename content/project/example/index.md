---
title: Deep Learning for Generation of Concept Car Designs
summary:
tags:
- Deep Learning
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/georgecushen
url_code: "https://github.com/martinoywa/creative-gan"
url_pdf: "https://www.martinoywa.engineer/pdf/DL_Generation_Concept_Car_Designs.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Deep learning / Representation learning is a subset of AI that hasn’t been a round a very long
time. It has been applied in both Computer Vision widely in classification, and Natural Language
Processing for areas such as text generation and speech recognition.
What we’re trying to achieve here is using this technique for image generation in the creative
industry, more specifically concept car designs. This is going to be achieved using Deep
Learning’s application to a technique called Generative Adversarial Networks, GANs. This
particular technique uses two competing Neural Networks; a Generator and a Discriminator,
whereby the Generator generates images and the Discriminator assesses these images to test
their quality. This is done iteratively until the generated images are as realistic as possible.
