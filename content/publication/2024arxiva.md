+++
title = "SABLE: Staging Blocked Evaluation of Sparse Matrix Computations"
date = 2024-04-03T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Pratyush Das", "Adhitha Dias", "Anxhelo Xhebraj", "Artem Pelenitsyn", "Kirshanthan Sundararajah", "Milind Kulkarni"]

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

abstract = "Sparse Matrices found in the real world often have some structure in how the dense elements are organized. While the inspector-executor model inspects matrices for structure, its generality can overlook further specialization. We propose a system that - if the sparse matrix is stored in a blocked storage format - can generate more efficient code by constructing regular loops over these blocks. Our system performs a specified computation over every element of the block instead of avoiding computing any sparse element at all and achieving regularity in specialized code. The system is extensible, providing a dense block iterator for the user to express any computation over these dense blocks. We show that this approach can significantly speed up SpMV and SpMM operations over the state-of-the-art systems Partially-Strided Codelets and Sparse Register Tiling."

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
url_pdf = "https://arxiv.org/pdf/2407.00829"           
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