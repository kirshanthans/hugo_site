+++
title = "Targeted Control-flow Transformations for Mitigating Path Explosion in Dynamic Symbolic Execution"
date = 2023-08-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Charitha Saumya", "Rohan Gangaraju", "Kirshanthan Sundararajah", "Milind Kulkarni"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication_short = "In *Arxiv*"

# Abstract and optional shortened version.

abstract = "Dynamic symbolic execution (DSE) suffers from path explosion problem when the target program has many conditional branches. Classical approach for managing the path explosion problem is dynamic state merging. Dynamic state merging combines similar symbolic program states together to avoid the exponential growth of states in DSE. However, state merging still requires solver invocations at each branch point of the program even when both paths of the branch is feasible and, the best path search strategy for DSE may not create the best state merging opportunities. Some drawbacks of state merging can be mitigated by compile-time state merging i.e. branch elimination by converting control-flow into data-flow. In this paper, we propose a non-semantics preserving but failure-preserving compiler technique for removing expensive symbolic branches in a program to improve the scalability of DSE. We develop a framework for detecting spurious bugs that can be inserted by our transformation. Finally, we show that our transformation can significantly improve the performance of exhaustive DSE on variety of benchmarks and helps in achieving more coverage in a large real-world subjects within a limited time budget."

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
url_pdf = "https://arxiv.org/pdf/2308.01554.pdf"           
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
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