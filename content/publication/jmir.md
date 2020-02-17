+++
title = "Learning Latent Space Representations to Predict Patient Outcomes"

# Date first published.
date = "2020-02-14"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Subendhu Rongali", "Adam J. Rose", "David D. McManus", "Adarsha S. Bajracharya", "Alok Kapoor", "Edgard Granillo", "Hong Yu"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In the *Journal of Medical Internet Research (JMIR)*"
publication_short = "In the *Journal of Medical Internet Research (JMIR)*"

# Abstract and optional shortened version.
abstract = """
Background: Scalable and accurate health outcome prediction using electronic health record data (EHR) has gained much attention in research recently. Previous machine learning models mostly ignore relations between different types of clinical data (i.e., laboratory, ICD, and medication).

Objective: In this study, we model such clinical data types and build predictive models using Intensive Care Units’ (ICUs) EHR data. We developed innovative neural network (NN) models and compared them with the widely used logistic regression model and other state-of-the-art NN models to predict patient’s mortality using his/her own longitudinal EHR data.

Methods: We built a set of NN models we collectively called as long short-term memory (LSTM) outcome prediction using comprehensive feature relations (CLOUT). Our CLOUT models use a correlational neural network model to identify a latent space representation between different types of discrete clinical features during a patient's encounter and integrate the latent representation into a LSTM based predictive model framework. In addition, we designed an ablation experiment to identify risk factors from our CLOUT models. Using physicians’ input as the gold standard, we compared the risk factors identified by both CLOUT and logistic regression models.

Results: Experiments on the MIMIC-III (Medical Information Mart for Intensive Care) dataset show that CLOUT has surpassed logistic regression and other baseline NN models. Also, physicians’ agreement with the CLOUT-derived risk factor rankings was statistically significantly higher than the agreement with the logistic regression model.

Conclusions: Our results strongly support the applicability of CLOUT for real-world clinical use in identifying patients at high risk of mortality.
"""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = ["health"]

# Links (optional).
url_pdf = ""
url_preprint = "https://preprints.jmir.org/preprint/16374/submitted"
url_code = "https://github.com/subendhu19/CLOUT"
url_dataset = "https://mimic.physionet.org/"
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
