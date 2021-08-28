+++
title = "Iterative Online Subspace Learning for Robust Image Alignment"
date = 2013-05-09
draft = false

author_list = "Jun He, <b>Dejiao Zhang</b>, Tao Tao, Laura Balzano"

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
publication = "In IEEE Automatic Face and Gesture Recognition Conference, FG 2013"
# publication_short = "In *ICMEW*"

# Abstract and optional shortened version.
abstract = "Robust high-dimensional data processing has witnessed an exciting development in recent years, as theoretical results have shown that it is possible using convex programming to optimize data fit to a low-rank component plus a sparse outlier component. This problem is also known as Robust PCA, and it has found application in many areas of computer vision. In image and video processing and face  recognition, an exciting opportunity for processing of massive image databases is emerging as people upload photo and video data online in unprecedented volumes. However, the data quality and consistency is not controlled in any way, and the massiveness of the data poses a serious computational challenge. In this paper we present t-GRASTA (transformed Grassmannian Robust Adaptive Subspace Tracking Algorithm). t-GRASTA performs incremental gradient descent constrained to the Grassmann manifold of subspaces in order to simultaneously estimate a decomposition of a collection of images into a lowrank subspace, a sparse part of occlusions and foreground objects, and a transformation such as rotation or translation of the image. We show that t-GRASTA is 4 times faster than state-ofthe-art algorithms, has half the memory requirement, and can achieve alignment for face images as well as jittered camera surveillance images."
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
url_pdf = "https://www.computer.org/csdl/proceedings/fg/2013/5545/00/06553759.pdf"
# url_preprint = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
url_code = "https://sites.google.com/site/hejunzz/t-grasta"
# url_project = ""
# url_slides = "#"
# url_video = "#"
# url_poster = "poster_icassp.pdf"
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

More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.
