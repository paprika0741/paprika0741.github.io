---
title: "Jupiter: Fast and Resource-Efficient Collaborative Inference of Generative LLMs on Edge Devices"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shengyuan Ye
  - Bei Ouyang
  - Liekang Zeng
  - Tianyi Qian
  - Xiaowen Chu
  - Jian Tang
  - Xu Chen

# Author notes (optional)
author_notes:
  - "Equal contribution"
  - "Equal contribution"
  - ""
  - ""
  - ""
  - "Corresponding author"

date: "2024-12-06"
#doi: "https://doi.org/10.1145/3673038.3673043"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-06"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Computer Communications*
publication_short: In *INFOCOM'25*

abstract: Generative large language models (LLMs) have garnered significant attention due to their exceptional capabilities in various AI tasks. Traditionally deployed in cloud datacenters, LLMs are now increasingly moving towards more accessible edge platforms to protect sensitive user data and ensure privacy preservation. The limited computational resources of individual edge devices, however, can result in excessively prolonged inference latency and overwhelmed memory usage. While existing research has explored collaborative edge computing to break the resource wall of individual devices, these solutions yet suffer from massive communication overhead and under-utilization of edge resources. Furthermore, they focus exclusively on optimizing the prefill phase, neglecting the crucial autoregressive decoding phase for generative LLMs. To address that, we propose Jupiter, a fast, scalable, and resource-efficient collaborative edge AI system for generative LLM inference. Jupiter introduces a flexible pipelined architecture as a principle and differentiates its system design according to the differentiated characteristics of the prefill and decoding phases. For prefilling, Jupiter submits a novel intra-sequence pipeline parallelism and develops a meticulous parallelism planning strategy to maximize resource efficiency; For decoding, Jupiter devises an effective outlinebased pipeline parallel decoding mechanism combined with speculative decoding, which further magnifies inference acceleration. Extensive evaluation based on realistic implementation demonstrates that Jupiter remarkably outperforms state-of-the-art approaches under various edge environment setups, achieving up to 26.1× end-to-end latency reduction while rendering on-par generation quality. Meanwhile, Jupiter demonstrates substantial scalability even under bandwidth-limited edge environments.

# Summary. An optional shortened abstract.
summary:  Shengyuan Ye , Bei Ouyang ,Liekang Zeng, Tianyi Qian, Xiaowen Chu, Jian Tang, Xu Chen<sup>&#8224; 
 
tags:
  - Large Language Models
  - Edge intelligence

# Display this page in the Featured widget? Featured Publications
# featured: true 使得页面可以在“Featured”小部件中显示。如果你希望某些内容在网站上被突出展示，通过设置这个属性可以将它们放在更显眼的位置。
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 
#"https://dl.acm.org/doi/pdf/10.1145/3673038.3673043"
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: #"PAC_slides.pdf"
url_source: ""
url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: "Image Jupiter"
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: #example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->

 
