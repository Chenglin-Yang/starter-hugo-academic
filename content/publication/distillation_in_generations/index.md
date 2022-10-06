---
title: "Knowledge Distillation in Generations: More Tolerant Teachers Educate Better Students"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Lingxi Xie 
- Siyuan Qiao
- Alan Yuille

# Author notes (optional)
author_notes: []

date: "2022"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *, 2019*
publication_short: In *AAAI19*

abstract: "We focus on the problem of training a deep neural network in generations. The flowchart is that, in order to optimize the target network (student), another network (teacher) with the same architecture is first trained, and used to provide part of supervision signals in the next stage. While this strategy leads to a higher accuracy, many aspects (e.g., why teacher-student optimization helps) still need further explorations.
This paper studies this problem from a perspective of controlling the strictness in training the teacher network. Existing approaches mostly used a hard distribution (e.g., one-hot vectors) in training, leading to a strict teacher which itself has a high accuracy, but we argue that the teacher needs to be more tolerant, although this often implies a lower accuracy. The implementation is very easy, with merely an extra loss term added to the teacher network, facilitating a few secondary classes to emerge and complement to the primary class. Consequently, the teacher provides a milder supervision signal (a less peaked distribution), and makes it possible for the student to learn from inter-class similarity and potentially lower the risk of over-fitting. Experiments are performed on standard image classification tasks (CIFAR100 and ILSVRC2012). Although the teacher network behaves less powerful, the students show a persistent ability growth and eventually achieve higher classification accuracies than other competitors. Model ensemble and transfer feature extraction also verify the effectiveness of our approach."

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/1805.05551'
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
