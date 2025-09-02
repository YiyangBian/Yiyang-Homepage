---
title: "MODis: Generating Skyline Datasets for Data Science Models"
authors:
  - Mengying Wang
  - Hanchao Ma
  - Yiyang Bian
  - Yangxin Fan
  - Yinghui Wu
date: "2025-03-25T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-03-25T00:00:00Z"

# Publication type.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 28th International Conference on Extending Database Technology (EDBT)*
publication_short: In *EDBT 2025*

abstract: Preparing high-quality datasets for data science models is a critical yet challenging task. Traditional data discovery approaches often focus on a single optimization criterion, which can introduce bias and limit downstream performance. This paper introduces **MODis**, a multi-objective data discovery framework that generates *skyline datasets* tailored to user-defined model performance measures (e.g., accuracy, training cost). MODis formalizes the skyline dataset generation problem using a finite state transducer (FST), and provides three algorithms:(1) a **reduce-from-universal** strategy that prunes unpromising data while approximating Pareto-optimal sets, (2) a **bi-directional search** that interleaves augmentation and reduction with correlation-based pruning, and (3) a **diversification algorithm** to mitigate dataset bias. Experiments with benchmark datasets and scientific applications show that MODis can improve model accuracy by up to 2× while reducing training cost, outperforming baseline data integration and feature selection methods.

tags:
  - Data Management Systems
  - Data Discovery
  - Machine Learning
  - Multi-objective Optimization

featured: true

url_pdf: "https://arxiv.org/pdf/2502.11262.pdf"
url_code: ""
url_dataset: ""
url_project: ""
url_slides: ""
url_source: ""
# url_video: ""

image:
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---
