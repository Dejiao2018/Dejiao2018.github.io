+++
title = "Simultaneous sparsity and parameter tying for deep learning using ordered weighted L1 regularization"
date = 2018-03-05
draft = false

author_list = "<b>Dejiao Zhang</b>, Julian Katz-Samuels, Mario A.T. Figueiredo, Laura Balzano"

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["4"]

# Publication name and optional abbreviated version.
publication = "In IEEE Statistical Signal Processing Workshop, SSP 2018"
# publication_short = "In *ICMEW*"

# Abstract and optional shortened version.
abstract = "A deep neural network (DNN) usually contains millions of parameters, making both storage and computation extremely expensive. Although this high capacity allows DNNs to learn sophisticated mappings, it also makes them prone to over- fitting. To tackle this issue, we adopt a recently proposed sparsity-inducing regularizer called OWL (ordered weighted L1, which has proven effective in sparse linear regression with strongly correlated covariates. Unlike the conventional sparsity-inducing regularizers, OWL simultaneously elimi- nates unimportant variables by setting their weights to zero, while also explicitly identifying correlated groups of variables by tying the corresponding weights to a common value. We evaluate the OWL regularizer on several deep learning bench- marks, showing that it can dramatically compress the network with slight or even no loss on generalization accuracy."
# abstract_short = "A mobile visual clothing search system is presented whereby a smart phone user can either choose a social networking image or capture a new photo of a person wearing clothing of interest and search for similar clothing in a large cloud-based ecommerce database. The phone's GPS location is used to re-rank results by retail store location, to inform the user of local stores where similar clothing items can be tried on."

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
url_pdf = "https://ieeexplore.ieee.org/abstract/document/8450819"
# url_preprint = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
# url_code = "https://github.com/Dejiao2018/GrOWL"
# url_project = ""
# url_slides = "#"
# url_video = "#"
# url_poster = "poster_iclr.pdf"
# url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Post", url = "http://example.org"}]

# Digital Object Identifier (DOI)
# doi = ""

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  # caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  image = "./featured.jpg"
  caption = "OWL"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Left"
+++

