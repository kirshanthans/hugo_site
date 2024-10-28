+++
title = "Treelogy: A Benchmark Suite for Tree Traversals"
date = 2017-10-12T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Nikhil Hegde", "Jianqiao Liu", "Kirshanthan Sundararajah", "Milind Kulkarni"]

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
publication_short = "In *ISPASS*"

# Abstract and optional shortened version.

abstract = "An interesting class of irregular algorithms is tree traversal algorithms, which repeatedly traverse various trees to perform efficient computations. Tree traversal algorithms form the algorithmic kernels in an important set of applications in scientific computing, computer graphics, bioinformatics, and data mining, etc. There has been increasing interest in understanding tree traversal algorithms, optimizing them, and applying them in a wide variety of settings. Crucially, while there are many possible optimizations for tree traversal algorithms, which optimizations apply to which algorithms is dependent on algorithmic characteristics. In this work, we present a suite of tree traversal kernels, drawn from diverse domains, called Treelogy, to explore the connection between tree traversal algorithms and state-of-the-art optimizations. We characterize these algorithms by developing an ontology based on their structural properties. The attributes extracted through our ontology, for a given traversal kernel, can aid in quick analysis of the suitability of platform- and application-specific as well as independent optimizations. We provide reference implementations of these kernels for three platforms: shared memory multicores, distributed memory systems, and GPUs, and evaluate their scalability."

abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://ieeexplore.ieee.org/document/7975294"           
url_preprint = ""
url_code = "https://bitbucket.org/plcl/treelogy"
url_dataset = ""
url_project = ""
url_slides = "files/slides/ispass2017.pdf"
url_video = ""
url_poster = ""
url_source = ""
# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = true

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""
+++