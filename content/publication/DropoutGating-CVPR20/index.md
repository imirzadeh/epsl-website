---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Dropout as an Implicit Gating Mechanism For Continual Learning"
authors: [Iman Mirzadeh, Mehrdad Farajtabar, Hassan Ghasemzadeh]
date: 2020-04-21T00:03:28-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-04-21T00:03:28-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The IEEE Conference on Computer Vision and Pattern Recognition (CVPR) Workshops"
publication_short: ""

abstract: ""

# Summary. An optional shortened abstract.
summary: "In recent years, neural networks have demonstrated an outstanding ability to achieve complex learning tasks across various domains. However, they suffer from the ''catastrophic forgetting'' problem when they face a sequence of learning tasks, where they forget the old ones as they learn new tasks. This problem is also highly related to the ''stability-plasticity dilemma''. The more plastic the network, the easier it can learn new tasks, but the faster it also forgets previous ones.
  Conversely, a stable network cannot learn new tasks as fast as a very plastic network. However, it is more reliable to preserve the knowledge it has learned from the previous tasks. 
  Several solutions have been proposed to overcome the forgetting problem by making the neural network parameters more stable, and some of them have mentioned the significance of dropout in continual learning. However, their relationship has not been sufficiently studied yet.
  In this paper, we investigate this relationship and show that a stable network with dropout learns a gating mechanism such that for different tasks, different paths of the network are active. 
  Our experiments show that the stability achieved by this implicit gating plays a very critical role in leading to performance comparable to or better than other involved continual learning algorithms to overcome catastrophic forgetting."
tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.dropbox.com/s/mawmene018mfh4i/cvpr20-cl.pdf?dl=0
url_code: https://github.com/imirzadeh/stable-continual-learning
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
slides: ""
---
