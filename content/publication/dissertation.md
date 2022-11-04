+++
title = "Low Resource Language Understanding in Voice Assistants"

# Date first published.
date = "2022-09-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Subendhu Rongali"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["5"]

# Publication name and optional abbreviated version.
publication = "Doctoral Dissertations. 2717. University of Massachusetts Amherst"
publication_short = "Doctoral Dissertations. 2717. University of Massachusetts Amherst"

# Abstract and optional shortened version.i
abstract = """
Voice assistants such as Amazon Alexa, Apple Siri, and Google Assistant have become ubiquitous. They rely on spoken language understanding, which typically consists of an Automatic Speech Recognition (ASR) component and a Natural Language Understanding (NLU) component. ASR takes user speech as input and generates a text transcription. NLU takes the text transcription as input and generates a semantic parse to identify the requested actions, called intents (play music, turn on lights, etc.) and any relevant entities, called slots (which song to play? which lights to turn on?). These components require massive amounts of training data to achieve good performance. In this dissertation, I identify and explore various data-related challenges to improve language understanding in voice assistants, specifically, the NLU component and the pipelined ASR-NLU architecture.

I first present a state-of-the-art NLU system based on sequence-to-sequence neural models that simplifies the traditional semantic parsing architecture, while also allowing it to handle complex user utterances consisting of multiple nested intents and slots. This work serves as an anchor for future data-constraint work. Next, I present an architecture to completely replace the pipelined ASR-NLU system with a fully end-to-end system. Our system is jointly trained on multiple speech-to-text and text-to-text tasks, allowing for transfer learning and also creating a shared representation for both speech and text. It outperforms previous pipelined and end-to-end systems, and performs end-to-end semantic parsing on a new domain by only training on a few text-to-text annotated NLU examples. Next, I demonstrate how to train large sequence-to-sequence NLU systems using a handful of examples by using auxiliary tasks to pre-train various components of the system. Finally, I demonstrate methods to perform low-resource domain adaptation. In low-resource domain adaptation, the goal is to parse utterances from a new domain using some simple metadata about the new domain and a small number of annotated training examples (few-shot) or no training examples (zero-shot) from that domain.
"""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = ["semparse"]

# Links (optional).
url_pdf = ""
url_preprint = "https://scholarworks.umass.edu/dissertations_2/2717"
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
