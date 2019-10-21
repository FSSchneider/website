+++
title = "DeepOBS: A Deep Learning Optimizer Benchmark Suite"
date = 2019-02-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Frank Schneider", "Lukas Balles", "Philipp Hennig"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *International Conference on Learning Representations (ICLR) 2019*."
publication_short = "In *ICLR*"

# Abstract and optional shortened version.
abstract = "Because the choice and tuning of the optimizer affects the speed, and ultimately the performance of deep learning, there is significant past and recent research in this area. Yet, perhaps surprisingly, there is no generally agreed-upon protocol for the quantitative and reproducible evaluation of optimization strategies for deep learning. We suggest routines and benchmarks for stochastic optimization, with special focus on the unique aspects of deep learning, such as stochasticity, tunability and generalization. As the primary contribution, we present DeepOBS, a Python package of deep learning optimization benchmarks. The package addresses key challenges in the quantitative assessment of stochastic optimizers, and automates most steps of benchmarking. The library includes a wide and extensible set of ready-to-use realistic optimization problems, such as training Residual Networks for image classification on ImageNet or character-level language prediction models, as well as popular classics like MNIST and CIFAR-10. The package also provides realistic baseline results for the most popular optimizers on these test problems, ensuring a fair comparison to the competition when benchmarking new optimizers, and without having to run costly experiments. It comes with output back-ends that directly produce LaTeX code for inclusion in academic publications. It is written in TensorFlow and available open source."
abstract_short = "We provide a software package that drastically simplifies, automates, and improves the evaluation of deep learning optimizers."

# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects = ["internal-project"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://uni-tuebingen.de/index.php?eID=tx_securedownloads&p=134446&u=0&g=0&t=1560000706&hash=05bff9a3e20648fd88d931369ab7fc4c589ee17f&file=/fileadmin/Uni_Tuebingen/Fakultaeten/MatNat/Fachbereiche/Informatik/Lehrstuehle/MethMaschLern/Dokumente/paper_pdf/Schneider19a.pdf"
url_preprint = "https://arxiv.org/abs/1903.05499"
url_code = "https://github.com/fsschneider/deepobs"
#url_dataset = "#"
#url_project = "https://openreview.net/forum?id=rJg6ssC5Y7"
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "OpenReview", url = "https://openreview.net/forum?id=rJg6ssC5Y7"}, {name = "Documentation", url = "https://deepobs.readthedocs.io/"}]

# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  # caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "TopLeft"
+++
