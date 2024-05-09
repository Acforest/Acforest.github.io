---
title: 'LogPrompt: A Log-based Anomaly Detection Framework Using Prompts'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ting Zhang
  - Xin Huang
  - Wen Zhao
  - Shaohuang Bian
  - Peng Du

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-08-02T00:00:00Z'
doi: '10.1109/IJCNN54540.2023.10191948'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-09T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Joint Conference on Neural Networks (IJCNN)*, 2023
publication_short: In *International Joint Conference on Neural Networks (IJCNN)*, 2023

abstract: "Log data are widely used in anomaly detection tasks of software system. At present, log anomaly detection methods based on deep learning have greatly progressed. However, the existing methods have the following limitations: (1) Logs are at large scale but labeled logs are rare, so training a detection model that requires a number of labeled log data from scratch is costly and impractical; (2) Log anomaly detection tasks usually need to comprehensively consider the semantic and sequential information in logs, but most of the current log anomaly detection frameworks only build models from either aspect; (3) Normal and abnormal logs are imbalanced in real world, which seriously reduces the detection recalls. This paper proposes a log anomaly detection framework called LogPrompt to solve the problems mentioned above. LogPrompt leverages prompts to guide the pretrained language model (PLM) to better learn the semantic and sequential information of logs, and avoids training a model from scratch. Even with few training data, the model achieves good detection performance. Moreover, it uses focal loss instead of cross entropy loss to guide the model optimization during training stage, for alleviating the class imbalance problem. Experiments show that LogPrompt can detect log anomalies more effectively and efficiently by prompts, and it can significantly improve the recalls and F1 scores."

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
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
