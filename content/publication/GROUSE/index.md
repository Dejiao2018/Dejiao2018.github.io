+++
title = "Convergence of a Grassmannian Gradient Descent Algorithm for Subspace Estimation from Undersampled Data"
date = 2018-10-09
draft = false

#authors = ["Dejiao Zhang", "Laura Balzano"]
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
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In preparation"
#journal = "Submitted to The Journal of the Society for the Foundations of Computational Mathematics (FOCM)"
# publication_short = "In *ICMEW*"

# Abstract and optional shortened version.
abstract = "Subspace learning and matrix factorization problems have great many applications in science and engineering, and efficient algorithms are critical as dataset sizes continue to grow. Many relevant problem formulations are non-convex, and in a variety of contexts it has been observed that solving the non-convex problem directly is not only efficient but reliably accurate. We discuss convergence theory for a particular method: first order incremental gradient descent constrained to the Grassmannian. The output of the algorithm is an orthonormal basis for a d-dimensional subspace spanned by an input streaming data matrix. We study two sampling cases: where each data vector of the streaming matrix is fully sampled, or where it is undersampled by a sampling matrix. Our results cover two cases, where $A_t$ is Gaussian or a subset of rows of the identity matrix. We propose an adaptive stepsize scheme that depends only on the sampled data and algorithm outputs. We prove that with fully sampled data, the stepsize scheme maximizes the improvement of our convergence metric at each iteration, and this method converges from any random initialization to the true subspace, despite the non-convex formulation and orthogonality constraints. For the case of undersampled data, we establish monotonic expected improvement on the defined convergence metric for each iteration with high probability."
#abstract_short = ""

# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects = ["SubspaceLearn"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["SubspaceLearn"]
#tags=[]

# Links (optional).
url_pdf = "https://arxiv.org/pdf/1610.00199.pdf"
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
#[image]
  # Caption (optional)
  # caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  #image = "./featured.jpg"
  #caption = "GROUSE"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++

