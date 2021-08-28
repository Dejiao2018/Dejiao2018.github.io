+++
title = "Learning to Share: Simultaneous Parameter Tying and Sparsification in Deep Learning"
date = 2018-04-30
draft = false

# authors = ["Dejiao Zhang", "Haozhu Wang", "Mario A.T. Figueiredo", "Laura Balzano"]
author_list = "<b>Dejiao Zhang</b>, Haozhu Wang, Mario A.T. Figueiredo, Laura Balzano"

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
# Does this page contain LaTeX math? (true/false)
math = true

# Publication name and optional abbreviated version.
publication = "Accepted by the Sixth International Conference on Learning Representations, ICLR 2018"
# publication_short = "In *ICMEW*"

# Abstract and optional shortened version.
abstract = "Deep neural networks (DNNs) may contain millions, even billions, of parameters/weights, making storage and computation very expensive and motivating a large body of work aimed at reducing their complexity by using, e.g., sparsity-inducing regularization. Parameter sharing/tying is another well-known approach for controlling the complexity of DNNs by forcing certain sets of weights to share a common value. Some forms of weight sharing are hard-wired to express certain invariances; a notable example is the shift-invariance of convolutional layers. However, other groups of weights may be tied together during the learning process to  further reduce the network complexity. In this paper, we adopt a recently proposed regularizer,  GrOWL (group ordered weighted L1), which encourages sparsity and, simultaneously, learns which groups of parameters should share a common value. GrOWL has been proven effective in linear regression, being able to identify and cope with strongly correlated covariates. Unlike standard sparsity-inducing regularizers (e.g., L1 a.k.a. Lasso), GrOWL not only eliminates unimportant neurons by setting all their weights to zero, but also explicitly identifies strongly correlated neurons by tying the corresponding weights to a common value. This ability of GrOWL motivates the following two-stage procedure: (i) use GrOWL regularization during training to simultaneously identify significant neurons and groups of parameters that should be tied together; (ii) retrain the network, enforcing the structure that was unveiled in the previous phase, i.e.,  keeping only the significant neurons and enforcing the learned tying structure. We evaluate this approach on several benchmark datasets, showing that it can dramatically compress the network with slight or even no loss on generalization accuracy."


# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["NNCompression"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["NNCompression"]

# Links (optional).
url_pdf = "https://openreview.net/pdf?id=rypT3fb0b"
# url_preprint = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
url_code = "https://github.com/Dejiao2018/GrOWL"
# url_project = ""
# url_slides = "#"
# url_video = "#"
url_poster = "poster_iclr.pdf"
# url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Post", url = "http://example.org"}]

# Digital Object Identifier (DOI)
# doi = ""



# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  # caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  image = "./featured.png"
  caption = "GrOWL"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++


