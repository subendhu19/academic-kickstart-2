+++
title = "Compressing Transformer-Based Semantic Parsing Models using Compositional Code Embeddings"

# Date first published.
date = "2020-10-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Prafull Prakash", "Saurabh Kumar Shashidhar", "Wenlong Zhao", "Subendhu Rongali", "Haidar Khan", "Michael Kayser"]

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
publication = "In *Proceedings of Findings of Empirical Methods in Natural Language Processing 2020 (EMNLP Findings ’20)*"
publication_short = "In *Proceedings of EMNLP Findings 2020*"

# Abstract and optional shortened version.
abstract = "The current state-of-the-art task-oriented semantic parsing models use BERT or RoBERTa as pretrained encoders; these models have huge memory footprints. This poses a challenge to their deployment for voice assistants such as Amazon Alexa and Google Assistant on edge devices with limited memory budgets. We propose to learn compositional code embeddings to greatly reduce the sizes of BERT-base and RoBERTa-base. We also apply the technique to DistilBERT, ALBERT-base, and ALBERT-large, three already compressed BERT variants which attain similar state-of-the-art performances on semantic parsing with much smaller model sizes. We observe 95.15% ~ 98.46% embedding compression rates and 20.47% ~ 34.22% encoder compression rates, while preserving >97.5% semantic parsing performances. We provide the recipe for training and analyze the trade-off between code embedding sizes and downstream performances."

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
