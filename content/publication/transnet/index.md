---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "TransNet: Minimally-Supervised Deep Transfer Learning for Dynamic Adaptation of Wearable Systems"
authors: [Seyed Ali Rokni, Marjan Nourollahi, Parastoo Alinia, Mahdi Pedram, Iman Mirzadeh, Hassan Ghasemzadeh]
date: 2020-07-23
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-23

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: "ACM Transactions on Design Automation of Electronic Systems (TODAES)"
publication_short: ""

abstract: "Wearables are poised to transform health and wellness through automation of cost-effective, objective, and real-time health monitoring. However, machine learning models for these systems are designed based on labeled data collected, and feature representations engineered, in controlled environments. This approach has limited scalability of wearables because (i) collecting and labeling sufficiently large amounts of sensor data is a labor-intensive and expensive process; and (ii) wearables are deployed in highly dynamic environments of the end-users whose context undergoes consistent changes. We introduce TransNet, a deep learning framework that minimizes the costly process of data labeling, feature engineering, and algorithm retraining by constructing a scalable computational approach. TransNet learns general and reusable features in lower layers of the framework and quickly reconfigures the underlying models from a small number of labeled instances in a new domain, such as when the system is adopted by a new user or when a previously unseen event is to be added to event vocabulary of the system. Utilizing TransNet on four activity datasets, TransNet achieves an average accuracy of 88.1% in cross-subject learning scenarios using only one labeled instance for each activity class. This performance improves to an accuracy of 92.7% with five labeled instances."

# Summary. An optional shortened abstract.
summary: ""

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

url_pdf:
url_code: https://github.com/ali-rokni/TransNet
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
