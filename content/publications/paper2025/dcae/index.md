---
title: '👑 CVPR 2025 | Learned Image Compression with Dictionary-based Entropy Model'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jingbo Lu
  - Leheng Zhang
  - Xingyu Zhou
  - Mu Li
  - Wen Li
  - Shuhang Gu

# Author notes (optional)
# author_notes:
#   - '*Corresponding author: Shuhang Gu'
#   - '†Jingbo Lu is the first author'

date: '2025-06-01'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition 2025*
publication_short: In *CVPR 2025*

# abstract: Learned image compression methods have attracted great research interest and exhibited superior rate-distortion performance to the best classical image compression standards of the present.The entropy model plays a key role in learned image compression, which estimates the probability distribution of the latent representation for further entropy coding.Most existing methods employed hyper-prior and auto-regressive architectures to form their entropy models.However, they only aimed to explore the internal dependencies of latent representation while neglecting the importance of extracting prior from training data.In this work, we propose a novel entropy model named Dictionary-based Cross Attention Entropy model, which introduces a learnable dictionary to summarize the typical structures occurring in the training dataset to enhance the entropy model.Extensive experimental results have demonstrated that the proposed model strikes a better balance between performance and latency, achieving state-of-the-art results on various benchmark datasets.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Image Compression
  - 2025
  - CVPR 2025
  - Visual Compression

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    arxiv: 2504.00496

# Custom links
links:
  - type: pdf
    url: https://arxiv.org/abs/2504.00496
  - type: code
    url: https://github.com/LabShuHangGU/DCAE

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Rate-speed comparison on Kodak'
  filename: 'latency_bd_rate.png'
  focal_point: ''
  preview_only: false
share: false
# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---

<!-- > [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
