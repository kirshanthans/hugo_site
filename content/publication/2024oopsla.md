+++
title = "SparseAuto: An Auto-scheduler for Sparse Tensor Computations using Recursive Loop Nest Restructuring"
date = 2024-10-08T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Adhitha Dias", "Logan Anderson", "Kirshanthan Sundararajah", "Artem Pelenitsyn", "Milind Kulkarni"]

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

abstract = "Automated code generation and performance enhancements for sparse tensor algebra have become essential in many real-world applications, such as quantum computing, physical simulations, computational chemistry, and machine learning. General sparse tensor algebra compilers are not always versatile enough to generate asymptotically optimal code for sparse tensor contractions. This paper shows how to generate asymptotically better schedules for complex sparse tensor expressions using kernel fission and fusion. We present generalized loop restructuring transformations to reduce asymptotic time complexity and memory footprint. Furthermore, we present an auto-scheduler that uses a partially ordered set (poset)-based cost model that uses both time and auxiliary memory complexities to prune the search space of schedules. In addition, we highlight the use of Satisfiability Module Theory (SMT) solvers in sparse auto-schedulers to approximate the Pareto frontier of better schedules to the smallest number of possible schedules, with user-defined constraints available at compile-time. Finally, we show that our auto-scheduler can select better-performing schedules and generate code for them. Our results show that the auto-scheduler provided schedules achieve orders-of-magnitude speedup compared to the code generated by the Tensor Algebra Compiler (TACO) for several computations on different real-world tensors."

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
url_pdf = "https://dl.acm.org/doi/10.1145/3689730"           
url_preprint = "https://arxiv.org/abs/2311.09549"
url_code = "https://zenodo.org/records/12764370"
url_dataset = ""
url_project = ""
url_slides = "files/slides/oopsla2024.key"
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