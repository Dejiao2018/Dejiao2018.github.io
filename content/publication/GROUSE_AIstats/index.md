+++
title = "Global Convergence of a Grassmannian Gradient Descent Algorithm for Subspace Estimation"
date = 2016-05-09
draft = false

# authors = ["Dejiao Zhang", "Laura Balzano"]
author_list ="<b>Dejiao Zhang</b>, Laura Balzano"

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
publication = "In Proceedings of the 19th International Conference on Artificial Intelligence and Statistics, AISTATS 2016"
# publication_short = "In *ICMEW*"

# Abstract and optional shortened version.
abstract = "It has been observed in a variety of contexts that gradient descent methods have great success in solving low-rank matrix factorization problems, despite the relevant problem formulation being non-convex. We tackle a particular instance of this scenario, where we seek the d-dimensional subspace spanned by a streaming data matrix. We apply the natural first order incremental gradient descent method, constraining the gradient method to the Grassmannian. In this paper, we propose an adaptive step size scheme that is greedy for the noiseless case, that maximizes the improvement of our metric of convergence at each data index t, and yields an expected improvement for the noisy case. We show that, with noise-free data, this method converges from any random initialization to the global minimum of the problem. For noisy data, we provide the expected convergence rate of the proposed algorithm per iteration."
# abstract_short = "A mobile visual clothing search system is presented whereby a smart phone user can either choose a social networking image or capture a new photo of a person wearing clothing of interest and search for similar clothing in a large cloud-based ecommerce database. The phone's GPS location is used to re-rank results by retail store location, to inform the user of local stores where similar clothing items can be tried on."

# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["SubspaceLearn"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["SubspaceLearn"]

# Links (optional).
url_pdf = "http://proceedings.mlr.press/v51/zhang16b-supp.pdf"
# url_preprint = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
# url_code = "https://github.com/Dejiao2018/GrOWL"
# url_project = ""
# url_slides = "#"
# url_video = "#"
url_poster = "aistats_poster1.pdf"
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
  caption = "GROUSE"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Left"
+++

