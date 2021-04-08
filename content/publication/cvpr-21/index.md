---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Generalizable Person Re-identiﬁcation with Relevance-aware Mixture of Experts"
authors: [Yongxing Dai, Xiaotong Li, Jun Liu, Zekun Tong, Lingyu Duan]
date: 2021-03-26T21:54:26+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-03-26T21:54:26+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Conference on Computer Vision and Pattern Recognition"
publication_short: "CVPR 2021"

abstract: "Domain generalizable (DG) person re-identiﬁcation (ReID) is a challenging problem because we cannot access any unseen target domain data during training. Almost all the existing DG ReID methods follow the same pipeline where they use a hybrid dataset from multiple source domains for training, and then directly apply the trained model to the unseen target domains for testing. These methods often neglect individual source domains’ discriminative characteristics and their relevances w.r.t. the unseen target domains, though both of which can be leveraged to help the model’s generalization. To handle the above two issues, we propose a novel method called the relevance-aware mixture of experts (RaMoE), using an effective voting-based mixture mechanism to dynamically leverage source domains’ diverse characteristics to improve the model’s generalization. Speciﬁcally, we propose a decorrelation loss to make the source domain networks (experts) keep the diversity and discriminability of individual domains’ characteristics. Besides, we design a voting network to adaptively integrate all the experts’ features into the more generalizable aggregated features with domain relevance. Considering the target domains’ invisibility during training, we propose a novel learning-to-learn algorithm combined with our relation alignment loss to update the voting network. Extensive experiments demonstrate that our proposed RaMoE outperforms the state-of-the-art methods."

# Summary. An optional shortened abstract.
summary: "CVPR 2021, poster, acceptance rate: 22.2%"

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
  caption: "Illustration of RaMoE model"
  focal_point: "Smart"
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
