+++
title = "Deep Unsupervised Clustering Using Mixture of Autoencoders"
date = 2017-12-25
draft = false

author_list = "<b>Dejiao Zhang</b>, Yifan Sun, Brian Eriksson, Laura Balzano"

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
publication = "UMich Deep Blue Technical Report, 2017"
# publication_short = "In *ICMEW*"

# Abstract and optional shortened version.
abstract = "Unsupervised clustering is one of the most fundamental challenges in machine learning. A popular hypothesis is that data are generated from a union of low-dimensional nonlinear manifolds; thus an approach to clustering is identifying and separating these manifolds. In this paper, we present a novel approach to solve this problem by using a mixture of autoencoders. Our model consists of two parts: 1) a collection of autoencoders where each autoencoder learns the underlying manifold of a group of similar objects, and 2) a mixture assignment neural network, which takes the concatenated latent vectors from the autoencoders as input and infers the distribution over clusters. By jointly optimizing the two parts, we simultaneously assign data to clusters and learn the underlying manifolds of each cluster."
# abstract_short = "A mobile visual clothing search system is presented whereby a smart phone user can either choose a social networking image or capture a new photo of a person wearing clothing of interest and search for similar clothing in a large cloud-based ecommerce database. The phone's GPS location is used to re-rank results by retail store location, to inform the user of local stores where similar clothing items can be tried on."

# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["DeepClustering"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["DeepClustering"]

# Links (optional).
url_pdf = "https://arxiv.org/pdf/1712.07788.pdf"
# url_preprint = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
# url_code = "https://github.com/Dejiao2018/GrOWL"
# url_project = ""
# url_slides = "#"
# url_video = "#"
url_poster = ""
# url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Post", url = "http://example.org"}]

# Digital Object Identifier (DOI)
# doi = ""

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  # caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  image = "./featured.jpg"
  caption = "IMAE"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Left"
+++

More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.
