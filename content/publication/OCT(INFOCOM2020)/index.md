---
title: "Online Concurrent Transmissions at LoRa Gateway"
authors:
- wangzhe
- Linghe Kong
- Kangjie Xu
- Liang He
- Guihai Chen
- Kaishun Wu
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
publication: In *2020 IEEE International Conference on Computer Communications*
publication_short: In *2020 IEEE INFOCOM*

abstract: Long Range (LoRa) communication, thanks to its wide network coverage and low energy operation, has attracted extensive attentions from both academia and industry. However, existing LoRa-based Wide Area Network (LoRaWAN) suffers from severe inter-network interference, due to the following two reasons. First, the densely-deployed LoRa ends usually share the same network configurations, such as spreading factor (SF), bandwidth (BW) and carrier frequency (CF), causing interference when operating in the vicinity. Second, LoRa is tailored for low-power devices, which excludes LoRaWAN from using the listen-before-talk (LBT) mechanisms commonly used in wireless communication technologies, such as WiFi and ZigBee —LoRaWAN has to use the duty-cycled medium access policy and thus being incapable of channel sensing or collision avoidance. To mitigate the inter-network interference, we propose a novel solution achieving the online concurrent transmissions at LoRa gateway, called OCT, which recovers collided packets at the gateway and thus improves LoRaWAN’s throughput. Moreover, OCT achieves the online concurrent transmission using only LoRa’s (de)modulation information, thus can be easily deployed at LoRa gateway. We have implemented and evaluated OCT on USRP platform and commodity LoRa ends, showing OCT achieves: (i) >90% packet reception rate (PRR), (ii) 3x10^{-3} bit error rate (BER), (iii) 2x and 3x throughput in the scenarios of two- and three- packet collisions respectively, and (iv) reducing 67% latency compared with state-of-the-art.
# Summary. An optional shortened abstract.
# summary:

tags:
- Source Themes
featured: true

#links:
#- name: Custom Link
#  url: http://example.org
# url_pdf: https://ieeexplore.ieee.org/document/8647405/
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

