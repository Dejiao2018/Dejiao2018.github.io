+++
title = "Online estimation of coherent subspaces with adaptive sampling"
date = 2018-03-05
draft = false


# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
# authors = ["Greg Ongie", "David Hong", "Dejiao Zhang", "Laura Balzano"]
author_list="Greg Ongie, David Hong, <b>Dejiao Zhang</b>, Laura Balzano"

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
abstract = "This work investigates adaptive sampling strategies for online subspace estimation from streaming input vectors where the underlying subspace is coherent, i.e., aligned with some subset of the coordinate axes. We adapt the previously proposed Grassmannian rank-one update subspace estimation (GROUSE) algorithm to incorporate an adaptive sampling strategy that substantially improves over uniform random sampling. Our approach is to sample some proportion of the entries based on the leverage scores of the current subspace estimate. Experiments on synthetic data demonstrate that the adaptive measurement scheme greatly improves the convergence rate of GROUSE over uniform random measurements when the underlying subspace is coherent."
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
url_pdf = "https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8450830"
# url_preprint = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
# url_code = " "
# url_project = ""
# url_slides = "#"
# url_video = "#"
# url_poster = "#"
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
  caption = "AdaGROUSE"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++

