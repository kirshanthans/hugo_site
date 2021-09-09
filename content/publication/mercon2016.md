+++
title = "Model-based Input-adaptive Vectorization"
date = 2016-04-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Kirshanthan Sundararajah", "Sanath Jayasena"]

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
publication_short = "In *MERCon*"

# Abstract and optional shortened version.

abstract = "In a program, not all the bits of a variable are always used during execution. Identifying the minimum number of bits necessary to represent a variable in a program can potentially provide optimization opportunities. Providing the knowledge of bitwidths to a compilation and execution framework will be advantageous if it could use that information to optimize the execution of the program, for instance, being able to select instructions for SIMD vectorization. This paper introduces a framework to exploit the potential vectorizations hidden in a program which is not exposed during static compilation time. Our framework unlocks instruction level data parallelism by using the bitwidths of array like variables that depend on runtime input. Our framework shows a maximum achievable performance gain of 37% and a mean achievable performance gain of 11% against the ICC compiler on our micro benchmark suite."

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
url_pdf = "https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7480117"           
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