---
title: "A Case Study of Accelerating Apache Spark with FPGA"
subtitle: Best Demo Award
authors:
- Junjie Hou
- Yongxin Zhu
- Linghe Kong
- wangzhe
- Sen Du
- Shijin Song
- Tian Huang
#date: "2013-07-01T00:00:00Z"
#doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2018 IEEE International Conference On Trust, Security And Privacy In Computing And Communications*
publication_short: In *2018 IEEE TRUSTCOM*

abstract: Apache Spark is an efficient distributed computing framework for big data processing. It supports in-memory computation of RDDs (Resilient Distributed Dataset) and provides a provision of reusability, fault tolerance, and real-time stream processing. However, the tasks in Spark framework are only performed on CPU. The low degree of parallelism and power inefficiency of CPU may restrict the performance and scalability of the cluster. In order to improve the performance and power dissipation of the data center, heterogeneous accelerators such as FPGA, GPU, MIC (Many Integrated Core) exhibit more efficient performance than the general-purpose processor in big data processing. In this work, we propose a framework to integrate FPGA accelerator into a Spark cluster. We use FPGA to accelerate the Spark tasks developed with Python, and in this way, the main computing load is performed on FPGA instead of CPU. We illustrate the performance of the FPGA based Spark framework with a case study of 2D-FFT algorithm acceleration. The results showed that FPGA based Spark implementation acquires 1.79x speedup than CPU implementation.

# Summary. An optional shortened abstract.
summary: IEEE TRUSTCOM 2018 Best Demo Award

tags:
- Source Themes
featured: true

#links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://ieeexplore.ieee.org/document/8647405/
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

