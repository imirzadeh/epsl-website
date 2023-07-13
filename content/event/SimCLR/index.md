---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Forecasting the future clinical events of a patient through contrastive learning"
event: EMIL Summer'23 Seminars
event_url:
location: Online (Zoom)
address:
  street:
  city:
  region:
  postcode:
  country:
summary:  This study implemented SimCLR on EHR data to detect rare dseases. In general, rare diseases are underrepresentative classes in any clinical dataset. Therefore, using SimCLR (contrastive learning) boosts their classification accuracy.
abstract: Models in the supervised learning framework may capture rich and complex representations over the features that are hard for humans to interpret. Existing methods to explain such models are often specific to architectures and data where the features do not have a time-varying component. In this work, we propose TIME, a method to explain models that are inherently temporal in nature. Our approach (i) uses a model-agnostic permutationbased approach to analyze global feature importance, (ii) identifies the importance of salient features with respect to their temporal ordering as well as localized windows of influence, and (iii) uses hypothesis testing to provide statistical rigor.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2023-07-12T12:30:00-07:00
date_end: 2023-07-12T13:00:00-07:00
all_day: false

# Schedule page publish date (NOT event date).
publishDate: 2022-07-12T16:45:20-07:00

authors: [asiful-arefeen]
tags: []

# Is this a featured event? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your event's folder or a URL.
url_slides: CL.pptx

url_code:
url_pdf: "https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9382392/pdf/ocac086.pdf"
url_video:

# Markdown Slides (optional).
#   Associate this event with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---