---
title: "Forward the Collision Decomposition in ZigBee"
authors:
- Yifeng Cao
- wangzhe
- Linghe Kong
- Guihai Chen
- Jiadi Yu
- Shaojie Tang
- Yingying Chen
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
publication: In *2019 IEEE International Conference on Network Protocols*
publication_short: In *2019 IEEE ICNP*

abstract: As wireless communication is tailored for low-power devices while the number of Internet of Things is growing exponentially, the collision problem in ZigBee is worsen. The classical approaches of solving collision problems lie in collision avoidance and packet retransmission, which could incur considerable overhead. The new trend is to decompose multipacket collision directly, however, the high bit error rate limits its practical applications. Toward this end, we observe three major issues in the existing solutions: 1) all existing solutions adopt the priori-chip-dependent decomposition pattern, leading to the error propagation; 2) the available samples for chip decoding can be scarce, resulting in severe scarce-sample errors; 3) existing solutions assume the consistent frequency offset for consecutive packets, leading to inaccurate frequency offset estimation. To solve the issues of collision decomposition in ZigBee, we propose FORWARD, a novel physical layer design to enable highly accurate collision decomposition in ZigBee. The key idea is to generate all possible collided combinations as reference waveforms. The decomposition is determined by comparing the collided signal with the reference waveforms. Such a priori-chip-independent design has the advantages to eliminate the cumulative errors incurred from error propagation. When decoding, FORWARD always choose the longest segment to ensure sufficient samples for decoding. Furthermore, the recursive calibration design is approaching the real-time frequency offset and dynamically compensates the reference waveform. We implement FORWARD on USRP based testbed and evaluate its performance. Experimental results demonstrate that FORWARD reduces bit error rate by 4.96× and increases throughput 1.46~2.8× compared with the state-of-the-art mZig.

# Summary. An optional shortened abstract.
summary: {collision avoidance;decoding;error statistics;frequency estimation;radio networks;wireless channels;Zigbee;recursive calibration;priori-chip-independent design;FORWARD physical layer design;Internet of Things;collision decomposition;cumulative errors;reference waveform;consecutive packets;scarce-sample errors;chip decoding;error propagation;priori-chip-dependent decomposition pattern;bit error rate;multipacket collision;packet retransmission;collision avoidance;low-power devices;wireless communication;ZigBee;Zigbee;Decoding;Bit error rate;Calibration;Throughput;Wireless communication;Physical layer.

tags:
- Source Themes
featured: true

#links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://ieeexplore.ieee.org/abstract/document/8888052
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

