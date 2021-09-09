+++
title = "TreeFuser: A Framework for Analyzing and Fusing General Recursive Tree Traversals"
date = 2017-04-24T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Laith Sakka", "Kirshanthan Sundararajah", "Milind Kulkarni"]

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
publication_short = "In *OOPSLA*"

# Abstract and optional shortened version.

abstract = "Series of traversals of tree structures arise in numerous contexts: abstract syntax tree traversals in compiler passes, rendering traversals of the DOM in web browsers, kd-tree traversals in computational simulation codes. In each of these settings, a tree is traversed multiple times to compute various values and modify various portions of the tree. While it is relatively easy to write these traversals as separate small updates to the tree, for efficiency reasons, traversals are often manually fused to reduce the number of times that each portion of the tree is traversed: by performing multiple operations on the tree simultaneously, each node of the tree can be visited fewer times, increasing opportunities for optimization and decreasing cache pressure and other overheads. This fusion process is often done manually, requiring careful understanding of how each of traversals of the tree interact. This paper presents an automatic approach to traversal fusion: tree traversals can be written independently, and then our framework analyzes the dependences between the traversals to determine how they can be fused to reduce the number of visits to each node in the tree. A critical aspect of our framework is that it exploits two opportunities to increase the amount of fusion: i) it automatically integrates code motion, and ii) it supports partial fusion, where portions of one traversal can be fused with another, allowing for a reduction in node visits without requiring that two traversals be fully fused. We implement our framework in Clang, and show across several case studies that we can successfully fuse complex tree traversals, reducing the overall number of traversals and substantially improving locality and performance."

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
url_pdf = "https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7975294"           
url_preprint = ""
url_code = "https://github.com/laithsakka/Grafter"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = "https://www.youtube.com/watch?v=WDHlP6g5rxo&ab_channel=SplashConference2017"
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