---
title: "Research and Development of a system for Bias Identification in Recommender Systems"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
author_notes: ""

date: "2022-03-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Recently, researchers have increased their scrutiny of ethical issues on artificial intelligence (AI), especially οn the field of Machine Learning. However, most previous studies on the area of Ethical Machine Learning have only focused on classification and regression tasks, while only a few studies have investigated ethical issues on recommender systems. The aim of this Diploma Thesis is to contribute to the understanding of biases that appear in recommender systems. In this direction, a web-app was developed to help users understand how biases are introduced in recommender systems. Moreover, we could thereby estimate the extend of bias in these systems. The app is comprised by four main pages. The first page visualizes datasets to help users find possible biases. In the second page, the user can build a recommender system by choosing between a vast collection of algorithms and hyperparameter tuning options in a user-friendly way. Additionally, we developed a page for the evaluation of a recommender system as per popularity bias, fairness, diversity, novelty and coverage. The evaluation consists of a) bias monitoring through different types of plots for a single dataset or dataset comparison b) cut-off analysis and c) hyperparameter analysis. Finally, we developed a page for popularity bias mitigation using one of the four algorithms that are available, FAR, PFAR, FA*IR and Calibrated recommendations. With reference to the broader field of ethical issues, this thesis shares special interest to popularity bias, diversity, novelty and item coverage. An extensive experimental study was conducted to gain a better understanding of the sources of bias and analyze the effect of different bias mitigation algorithms. This was implemented by utilizing the aforementioned web app. Four datasets were used in the present study, one real dataset provided by a major electronics retailer, and three datasets collected from the internet. The first part of the study examines the role of the hyperparameter tuning for every algorithm that was used and the role of dataset characteristics, in bias and accuracy. It also compares the above-mentioned datasets. The second part consists of bias mitigation using three reranking algorithms, FAR, PFAR and Calibrated recommendations and an in-processing algorithm. This study has identified that data characteristics, and especially the sparsity of user-item matrix, can highly affect the bias that is introduced. Moreover, another significant finding is that the post-processing mitigation algorithms that were examined can improve the bias-accuracy tradeoff, but have several limitations too. In conclusion, developers of recommender systems need to be aware of sources of biases and of the accuracy-bias tradeoff. This work contributes to this direction and lays the groundwork for future research into bias in recommender systems.

# Summary. An optional shortened abstract.
summary:  Under the supervision of Associate Professor [Christos Makris](https://scholar.google.gr/citations?user=Aer3e90AAAAJ&hl=el) and co-supervision of Yiannis Kanellopoulos, Founder & CEO at [Code4Thought](https://code4thought.eu/).

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://nemertes.library.upatras.gr/jspui/bitstream/10889/15929/1/Thesis_Romanos_Kapsalis_1056289.pdf'
url_code: 'https://github.com/rkapsalis/Thesis'
url_dataset: ''
url_poster: ''
url_project: 'https://share.streamlit.io/rkapsalis/bias_in_recsys/elliot-master/recsys_bias.py'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Home page'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: []
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
