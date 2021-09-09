+++
title = "Sound, Fine-grained Traversal Fusion for Heterogeneous Trees"
date = 2019-06-08T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Laith Sakka", "Kirshanthan Sundararajah", "Ryan R Newton", "Milind Kulkarni"]

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
publication_short = "In *PLDI*"

# Abstract and optional shortened version.

abstract = "Applications in many domains are based on a series of traversals of tree structures, and fusing these traversals together to reduce the total number of passes over the tree is a common, important optimization technique. In applications such as compilers and render trees, these trees are heterogeneous: different nodes of the tree have different types. Unfortunately, prior work for fusing traversals falls short in different ways: they do not handle heterogeneity; they require using domain-specific languages to express an application; they rely on the programmer to aver that fusing traversals is safe, without any soundness guarantee; or they can only perform coarse-grain fusion, leading to missed fusion opportunities. This paper addresses these shortcomings to build a framework for fusing traversals of heterogeneous trees that is automatic, sound, and fine-grained. We show across several case studies that our approach is able to allow programmers to write simple, intuitive traversals, and then automatically fuse them to substantially improve performance."

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
url_pdf = "https://dl.acm.org/doi/pdf/10.1145/3314221.3314626"           
url_preprint = ""
url_code = "https://github.com/laithsakka/Grafter"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = "https://www.youtube.com/watch?v=j2henSFtZds&ab_channel=laithsakka"
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