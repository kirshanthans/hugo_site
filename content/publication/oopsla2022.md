+++
title = "UniRec: A Unimodular-Like Framework for Nested Recursions and Loops"
date = 2022-11-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Kirshanthan Sundararajah", "Charitha Saumya", "Milind Kulkarni"]

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

abstract = "Scheduling transformations reorder operations in a program to improve locality and/or parallelism. There are mature loop transformation frameworks such as the polyhedral model for composing and applying instance-wise scheduling transformations for loop nests.In recent years, there have been efforts to build frameworks for composing and applying scheduling transformations for nested recursion and loops, but these frameworks cannot employ the full power of transformations for loop nests since they have overly-restrictive representations. This paper describes a new framework, UniRec, that not only generalizes prior frameworks for reasoning about transformations on recursion, but also generalizes the unimodular framework, and hence unifies reasoning about perfectly-nested loops and recursion."

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
url_pdf = "https://dl.acm.org/doi/10.1145/3563333"           
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