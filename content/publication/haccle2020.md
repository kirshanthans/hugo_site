+++
title = "HACCLE: An Ecosystem for Building Secure Multi-Party Computations"
date = 2020-09-03T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Yuyan Bao", "Kirshanthan Sundararajah", "Raghav Malik", "Qianchuan Ye", "Christopher Wagner", "Nouraldin Jaber", "Fei Wang", "Mohammad Hassan Ameri", "Donghang Lu", "Alexander Seto", "Benjamin Delaware", "Roopsha Samanta", "Aniket Kate", "Christina Garman", "Jeremiah Blocki", "Pierre-David Letourneau", "Benoit Meister", "Jonathan Springer", "Tiark Rompf", "Milind Kulkarni"]

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

abstract = "Cryptographic techniques have the potential to enable distrusting parties to collaborate in fundamentally new ways, but their practical implementation poses numerous challenges. An important class of such cryptographic techniques is known as secure multi-party computation (MPC). In an effort to provide an ecosystem for building secure MPC applications using higher degrees of automation, we present the HACCLE (High Assurance Compositional Cryptography: Languages and Environments) toolchain. The HACCLE toolchain contains an embedded domain-specific language (Harpoon) for software developers without cryptographic expertise to write MPC-based programs. Harpoon programs are compiled into acyclic circuits represented in HACCLE's Intermediate Representation (HIR) that serves as an abstraction for implementing a computation using different cryptographic protocols such as secret sharing, homomorphic encryption, or garbled circuits. Implementations of different cryptographic protocols serve as different backends of our toolchain. The extensible design of HIR allows cryptographic experts to plug in new primitives and protocols to realize computations.We have implemented HACCLE, and used it to program interesting algorithms and applications (e.g., secure auction, matrix-vector multiplication, and merge sort). We show that the performance is improved by using our optimization strategies and heuristics."

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
url_pdf = "https://arxiv.org/pdf/2009.01489.pdf"           
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