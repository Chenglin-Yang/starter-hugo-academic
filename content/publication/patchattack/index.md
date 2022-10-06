---
title: "PatchAttack: A Black-box Texture-based Attack with Reinforcement Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Adam Kortylewski 
- Cihang Xie 
- Yinzhi Cao
- Alan Yuille

# Author notes (optional)
author_notes: []

date: "2022"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-04-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *European Conference on Computer Vision, 2020*
publication_short: In *ECCV2020*

abstract: Patch-based attacks introduce a perceptible but localized change to the input that induces misclassification. A limitation of current patch-based black-box attacks is that they perform poorly for targeted attacks, and even for the less challenging non-targeted scenarios, they require a large number of queries. Our proposed PatchAttack is query efficient and can break models for both targeted and non-targeted attacks. PatchAttack induces misclassifications by superimposing small textured patches on the input image. We parametrize the appearance of these patches by a dictionary of class-specific textures. This texture dictionary is learned by clustering Gram matrices of feature activations from a VGG backbone. PatchAttack optimizes the position and texture parameters of each patch using reinforcement learning. Our experiments show that PatchAttack achieves > 99% success rate on ImageNet for a wide range of architectures, while only manipulating 3% of the image for non-targeted attacks and 10% on average for targeted attacks. Furthermore, we show that PatchAttack circumvents state-of-the-art adversarial defense methods successfully.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2004.05682'
url_code: 'https://github.com/Chenglin-Yang/PatchAttack'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---
