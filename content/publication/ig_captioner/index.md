
---
title: "IG Captioner: Information Gain Captioners are Strong Zero-shot Classifiers"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Siyuan Qiao
- Yuan Cao
- Yu Zhang
- Tao Zhu
- Alan Yuille
- Jiahui Yu

# Author notes (optional)
author_notes: []

date: ""
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-11-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *arXiv, 2023*
publication_short: In *arXiv23*

abstract: "Generative training has been demonstrated to be powerful for building visual-language models. However, on zero-shot discriminative benchmarks, there is still a performance gap between models trained with generative and discriminative objectives. In this paper, we aim to narrow this gap by improving the efficacy of generative training on classification tasks, without any finetuning processes or additional modules.
Specifically, we focus on narrowing the gap between the generative captioner and the CLIP classifier. We begin by analysing the predictions made by the captioner and classifier and observe that the caption generation inherits the distribution bias from the language model trained with pure text modality, making it less grounded on the visual signal. To tackle this problem, we redesign the scoring objective for the captioner to alleviate the distributional bias and focus on measuring the gain of information brought by the visual inputs. We further design a generative training objective to match the evaluation objective. We name our model trained and evaluated from the novel procedures as Information Gain (IG) captioner. We pretrain the models on the public Laion-5B dataset and perform a series of discriminative evaluations. For the zero-shot classification on ImageNet, IG captioner achieves >18% improvements over the standard captioner, achieving comparable performances with the CLIP classifier. IG captioner also demonstrated strong performance on zero-shot image-text retrieval tasks on MSCOCO and Flickr30K. We hope this paper inspires further research towards unifying generative and discriminative training procedures for visual-language models."

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2311.17072'
url_code: ''
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
