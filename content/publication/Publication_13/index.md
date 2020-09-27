---
title: "Harnessing wireless channels for scalable and privacy-preserving federated learning"
authors:
- Anis Elgabli
- Jihong Park
- Chaouki Ben Issaid
- Mehdi Bennis

date: "2020-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ArXiv preprint
#publication_short: Arxiv

abstract: Wireless connectivity is instrumental in enabling scalable federated learning (FL), yet wireless channels bring challenges for model training, in which channel randomness perturbs each worker's model update while multiple workers' updates incur significant interference under limited bandwidth. To address these challenges, in this work we formulate a novel constrained optimization problem, and propose an FL framework harnessing wireless channel perturbations and interference for improving privacy, bandwidth-efficiency, and scalability. The resultant algorithm is coined analog federated ADMM (A-FADMM) based on analog transmissions and the alternating direct method of multipliers (ADMM). In A-FADMM, all workers upload their model updates to the parameter server (PS) using a single channel via analog transmissions, during which all models are perturbed and aggregated over-the-air. This not only saves communication bandwidth, but also hides each worker's exact model update trajectory from any eavesdropper including the honest-but-curious PS, thereby preserving data privacy against model inversion attacks. We formally prove the convergence and privacy guarantees of A-FADMM for convex functions under time-varying channels, and numerically show the effectiveness of A-FADMM under noisy channels and stochastic non-convex functions, in terms of convergence speed and scalability, as well as communication bandwidth and energy efficiency.

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/pdf/2007.01790.pdf
# url_code: '#'
# url_dataset: '#'
# url_poster: http://2018.ds3-datascience-polytechnique.fr/wp-content/uploads/2018/06/DS3-342.pdf
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

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

