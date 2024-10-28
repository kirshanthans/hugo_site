+++
title = "Composable, Sound Transformations of Nested Recursion and Loops"
date = 2019-06-08T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Kirshanthan Sundararajah", "Milind Kulkarni"]

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

abstract = "Scheduling transformations reorder a program’s operations to improve locality and/or parallelism. The polyhedral model is a general framework for composing and applying instance-wise scheduling transformations for loop-based programs, but there is no analogous framework for recursive programs. This paper presents an approach for composing and applying scheduling transformations—like inlining, interchange, and code motion—to nested recursive programs. This paper describes the phases of the approach—representing dynamic instances, composing and applying transformations, reasoning about correctness—and shows that these techniques can verify the soundness of composed transformations."

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
url_pdf = "https://dl.acm.org/doi/pdf/10.1145/3314221.3314592"           
url_preprint = "https://docs.lib.purdue.edu/ecetr/756/"
url_code = "https://github.com/kirshanthans/polyrec"
url_dataset = ""
url_project = ""
url_slides = "files/slides/pldi2019a.pptx"
url_video = "https://www.youtube.com/watch?v=gueEan6ssYY&ab_channel=ACMSIGPLAN"
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