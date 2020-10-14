+++
title = "Unsupervised Parsing with S-DIORA: Single Tree Encoding for Deep Inside-Outside Recursive Autoencoders"

# Date first published.
date = "2020-10-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Andrew Drozdov", "Subendhu Rongali", "Yi-Pei Chen", "Tim O'Gorman", "Mohit Iyyer", "Andrew McCallum"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *Proceedings of 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP ’20)*"
publication_short = "In *Proceedings of EMNLP 2020*"

# Abstract and optional shortened version.
abstract = "The deep inside-outside recursive autoencoder (DIORA) is a self-supervised neural model that learns to induce syntactic tree structures for input sentences without access to labeled training data. In this paper, we discover that while DIORA exhaustively encodes all possible binary trees of a sentence with a soft dynamic program, its vector averaging approach is locally greedy and cannot recover from errors when computing the highest scoring parse tree in bottom-up chart parsing. To fix this issue, we introduce S-DIORA, an improved variant of DIORA that encodes a single tree rather than a softly-weighted mixture of trees by employing a hard argmax operation and a beam at each cell in the chart. Our experiments show that through fine-tuning a pre-trained DIORA with our new algorithm, we improve the state of the art in unsupervised constituency parsing on the English WSJ Penn Treebank by 2.2-6% F1, depending on the data used for fine-tuning."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Links (optional).
url_pdf = ""
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

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]

+++
