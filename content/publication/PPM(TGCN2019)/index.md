---
title: "PPM: Preamble and Postamble-Based Multi-Packet Reception for Green ZigBee Communication:
- wangzhe
- Kangjie Xu
- Linghe Kong
- Guihai Chen
- Liang He
#date: "2013-07-01T00:00:00Z"
#doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *2019 IEEE Transactions on Green Communications and Networking*
publication_short: In *2019 IEEE TGCN*

abstract: ZigBee, a low-power wireless communication technology, has been used in various applications, such as smart health/home/buildings. The proliferation of ZigBee-based applications (and thus devices), however, makes the concurrent transmissions-i.e., multiple transmitters send packets to the same receiver at the same time-common in practice, leading to inevitable collisions. Either retransmissions caused by collisions or the collision avoidance mechanism, e.g., CSMA/CA, introduces plenty of energy consumption. To facilitate the green and concurrent transmissions of ZigBee, we design pre/post-amble-based multi-packet reception (PPM), a method that recovers the collided ZigBee messages by exploiting their collision-free chips and the overlapped chips in their pre/post-ambles. We elaborately attach short postamble to standard ZigBee packet by manipulating the ZigBee payload, which can be compatible with standard ZigBee and only introduce negligible energy overhead. We further propose two design enhancements, cross-validation and reference chips calibration, to ensure the accuracy of PPM. Such a collision recovery of PPM reduces the retransmissions caused by collisions and eliminates the energy overhead of CSMA/CA simultaneously, facilitating the realization of green ZigBee. We have prototyped and evaluated PPM with USRP, showing PPM recovers the collided messages with bit-error-rates in the order of 10-6 , which is magnitudes lower than state-of-the-art methods. Experimental results show that PPM can achieve packet reception ratio more than 90% and less than 20 retransmissions in a concurrent transmission experiment with 400 packets resulting in negligible packet retransmission cost of energy.

# Summary. An optional shortened abstract.
summary: carrier sense multiple access;energy consumption;error statistics;telecommunication congestion control;telecommunication power management;telecommunication traffic;Zigbee;packet reception ratio;green ZigBee communication;low-power wireless communication technology;energy consumption;collided ZigBee messages;collision-free chips;overlapped chips;ZigBee payload;reference chips calibration;collision recovery;PPM;concurrent transmissions;ZigBee packet;energy overhead;CSMA-CA;USRP;bit error rates;postamble-based multipacket reception;preamble-based multipacket reception;Zigbee;Standards;Physical layer;Energy consumption;Bit error rate;Transmitters;Collision avoidance;ZigBee;green;collision;decomposition.

tags:
- Source Themes
featured: true

#links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://ieeexplore.ieee.org/abstract/document/8698329
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

