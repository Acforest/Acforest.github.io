---
title: 'LogContrast: A Weakly Supervised Anomaly Detection Method Leveraging Contrastive Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 'Ting Zhang'
  - '**Xin Huang**'
  - 'Wen Zhao'
  - 'Guozhao Mo'
  - 'Shaohuang Bian'

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-12-25T00:00:00Z'
doi: '10.1109/QRS60937.2023.00015'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-09T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Software Quality, Reliability, and Security (QRS)*, 2023
publication_short: In *QRS*, 2023

abstract: We propose a novel log-based anomaly detection method that leverages weakly supervised contrastive learning, named LogContrast. LogContrast aims to address the issues of limited and noisy labeled logs in real-world scenarios. During the training stage, LogContrast first augments the current log feature through dropout. Subsequently, it treats the current log feature and the augmented feature as a positive pair, while treating the current log feature and other log features in the same batch as negative pairs. The objective is to pull the positive pairs closer together and push the negative pairs farther apart, thereby encouraging similar logs to be closer to each other and dissimilar logs to be farther apart in the feature space. The experimental results demonstrate the excellent performance of LogContrast even with limited labeled logs and greater noise resistance compared to fully supervised methods. In addition, we explore the role of semantic features and demonstrate that semantic features have strong adaptability to constantly evolving logs.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Log-based Anomaly Detection]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
