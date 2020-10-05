---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Fine-Grained Urban Flow Inference"
authors: [Kun Ouyang, Yuxuan Liang, Ye Liu, Zekun Tong, Sijie Ruan, Yu Zheng, David S. Rosenblum]
date: 2020-07-30T22:11:23+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-30T22:11:23+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Knowledge and Data Engineering 2020"
publication_short: "IEEE TKDE"

abstract: "The ubiquitous deployment of monitoring devices in urban flow monitoring systems induces a significant cost for maintenance and operation. A technique is required to reduce the number of deployed devices, while preventing the degeneration of data accuracy and granularity. In this paper, we present an approach for inferring the real-time and fine-grained crowd flows throughout a city based on coarse-grained observations. This task exhibits two challenges: the spatial correlations between coarse-and fine-grained urban flows, and the complexities of external impacts. To tackle these issues, we develop a model entitled UrbanFM which consists of two major parts: 1) an inference network to generate fine-grained flow distributions from coarse-grained inputs that uses a feature extraction module and a novel distributional upsampling module; 2) a general fusion subnet to further boost the performance by considering the influence of different external factors. This structure provides outstanding effectiveness and efficiency for small scale upsampling. However, the single-pass upsampling used by UrbanFM is insufficient at higher upscaling rates. Therefore, we further present UrbanPy, a cascading model for progressive inference of fine-grained urban flows by decomposing the original tasks into multiple subtasks. Compared to UrbanFM, such an enhanced structure demonstrates favorable performance for larger-scale inference tasks."

# Summary. An optional shortened abstract.
summary: "IEEE TKDE 2020"

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
url_code:
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
