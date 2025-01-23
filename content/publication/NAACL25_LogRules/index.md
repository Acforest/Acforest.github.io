---
title: 'LogRules: Enhancing Log Analysis Capability of Large Language Models through Rules'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xin Huang
  - Ting Zhang
  - Wen Zhao

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

# date: '2023-08-02T00:00:00Z'
# doi: '10.1109/IJCNN54540.2023.10191948'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-23T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "*Annual Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics (NAACL)*, 2025. (CCF B, Findings)"
publication_short: "*Annual Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics (NAACL)*, 2025. (CCF B, Findings)"

abstract: "Currently, large language models (LLMs) have achieved impressive performance in natural language processing tasks. However, LLMs still exhibit many hallucinations when analyzing system logs, which is due to the implicit knowledge and rules in logs that LLMs cannot capture. Based on this, we propose LogRules, a lightweight log analysis framework that generates and utilizes rules through LLMs. LogRules consists of three stages: an induction stage, an alignment stage, and a reasoning stage. Firstly, in the induction stage, an strong LLM (e.g., GPT-4o-mini) is tasked with generating a series of rules related to logs, which are then validated on the training set. When the rules are confirmed to produce correct reasoning results, they are added to a rule repository. Secondly, considering that the LLMs with small size ($\approx$8B parameters) still face challenges in utilizing rules, we design an alignment method based on rule-case contrastive preference optimization (CPO) to effectively enhance the rule reasoning capabilities of these LLMs. Finally, in the reasoning stage, the LLM constructs prompt using the rule repository and performs log analysis on the test set. Experiments show that LogRules outperforms LLM-based methods in log parsing and anomaly detection tasks, and achieves better performance compared to case-based methods."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Log Parsing, Log-based Anomaly Detection]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: 'https://arxiv.org/abs/2408.08640'
# url_code: 'https://github.com/wwzhuang01/Math-PUMA'
# url_dataset: 'https://huggingface.co/Math-PUMA'
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
