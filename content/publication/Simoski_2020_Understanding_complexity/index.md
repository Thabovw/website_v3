---
title: Understanding the complexities of Bluetooth for representing real-life social networks
authors:
- B Simoski
- M Klein
- E Fernandes de Mello Araujo
- AT van Halteren
- TJ van Woudenberg
- KE Bevelander
- M Buijzen
- H Bal

date: 2020-08-13T00:00:00
doi: https://doi.org/10.1007/s00779-020-01435-x

# Schedule page publish date (NOT publication's date).
publishDate: "2020-08-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Personal and Ubiquitous Computing*"
publication_short: ""

abstract: Bluetooth (BT) data has been extensively used for recognizing social patterns and inferring social networks, as BT is widely present in everyday technological devices. However, even though collecting BT data is subject to random noise and may result in substantial measurement errors, there is an absence of rigorous procedures for validating the quality of the inferred BT social networks. This paper presents a methodology for inferring and validating BT-based social networks based on parameter optimization algorithm and social network analysis (SNA). The algorithm performs edge inference in a brute-force search over a given BT data set, for deriving optimal BT social networks by validating them with predefined ground truth (GT) networks. The algorithm seeks to optimize a set of parameters, predefined considering some reliability challenges associated to the BT technology itself. The outcomes show that optimizing the parameters can reduce the number of BT data false positives or generate BT networks with the minimum amount of BT data observations. The subsequent SNA shows that the inferred BT social networks are unable to reproduce some network characteristics present in the corresponding GT networks. Finally, the generalizability of the proposed methodology is demonstrated by applying the algorithm on external BT data sets, while obtaining comparable results.

# Summary. An optional shortened abstract.
summary: The aim of this study was to validate  Bluetooth based social networks based on a parameter optimization algorithm.

tags:
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://link.springer.com/content/pdf/10.1007/s00779-020-01435-x.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/OCfHTaB5THQ)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [MyMovez]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
