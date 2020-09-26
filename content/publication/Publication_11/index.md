---
title: "Q-GADMM: Quantized Group ADMM for Communication Efficient Decentralized Machine Learning"
authors:
- Anis Elgabli
- Jihong Park
- Amrit S. Bedi
- Chaouki Ben Issaid
- Mehdi Bennis
- Vaneet Aggarwal
date: "2020-03-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Arxiv pre-Preprint
#publication_short: Arxiv

abstract: In this article, we propose a communication-efficient decentralized machine learning (ML) algorithm, coined quantized group ADMM (Q-GADMM). To reduce the number of communication links, every worker in Q-GADMM communicates only with two neighbors, while updating its model via the group alternating direct method of multiplier (GADMM). Next, each worker quantizes its model updates before transmission, thereby decreasing the communication payload size. However, due to the lack of centralized entity in decentralized ML, the communication link sparsification and payload compression may incur error propagation, hindering model training convergence. To overcome this, we develop a novel stochastic quantization method to adaptively adjust model quantization levels and their probabilities, while proving the convergence of Q-GADMM for convex objective functions. Furthermore, to demonstrate the feasibility of Q-GADMM for non-convex objective functions, we propose quantized stochastic GADMM (Q-SGADMM) that incorporates deep neural network architectures and stochastic gradient decent (SGD). Simulation results corroborate that Q-GADMM yields 7x less total communication cost while achieving almost the same accuracy and convergence speed compared to GADMM without quantization for a linear regression task. Similarly, for an image classification task, Q-SGADMM achieves 4x less total communication cost with identical accuracy and convergence speed compared to its counterpart without quantization, i.e., stochastic GADMM (SGADMM).

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/abs/1910.10453
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
