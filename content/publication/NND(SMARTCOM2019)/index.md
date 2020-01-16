---
title: "NnD: Shallow Neural Network BasedÂ Collision Decoding in IoT Communications"
authors:
- wangzhe
- Linghe Kong
- Guihai Chen
- Ming Ni
subtitle: Best Student Paper Award
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
publication: In *2019 International Conference on Smart Computing and Communication*
publication_short: In *2019 SmartCom*

abstract: Internet of Things (IoT) has been widely used in intelligent warehouse, environment monitoring and smart buildings. In these application scenarios, concurrent transmissions frequently occur in which multiple transmitters send packets to one receiver simultaneously, causing severe collisions and low throughput. The state-of-the-art methods are able to decompose collided packets from different transmitters. However, they rely heavily on random time offsets and has poor performance under inferior channel conditions. In this paper, we present a new physical layer mechanism Open image in new window (nnD) to resolve multi-packet collisions. We first collect collision-free symbols or history single packets as the training set. In order to improve the decoding accuracy, we model the mapping relationship between overlapped symbols and their symbol values by neural networks. Since overlapping combinations of symbols are limited which are decided by corresponding chips’ value, we can predict values of unknown symbols by classifying different kinds of overlapping combinations. By introducing neural networks, nnD can not only achieve a high decoding precision but also can dynamically choose neural network architecture to adapt to different collision scenarios. To evaluate the performance of nnD, extensive trace-driven simulations are conducted. The results demonstrate that nnD outperforms existing methods in terms of bit error rate and the number of concurrent transmissions.

# Summary. An optional shortened abstract.
summary: SmartCom2019 Best Student Paper Award

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

