---
title: 'Empowering LLM-based Machine Translation with Cultural Awareness'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin *
  - Ming Jiang
  - Diyi Yang
  - Junjie Hu

# Author notes (optional)
author_notes:
  - ''
#   - 'Equal contribution'

date: '2022-06-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: Conference
publication_short: Preprint

abstract: Traditional neural machine translation (NMT) systems often fail to translate sentences that contain culturally specific information. Most previous NMT methods have incorporated external cultural knowledge during training, which requires fine-tuning on low-frequency items specific to the culture. Recent in-context learning utilizes lightweight prompts to guide large language models (LLMs) to perform machine translation, however, whether such an approach works in terms of injecting culture awareness into machine translation remains unclear. To this end, we introduce a new data curation pipeline to construct a culturally relevant parallel corpus, enriched with annotations of cultural-specific entities. Additionally, we design simple but effective prompting strategies to assist this LLM-based translation. Extensive experiments show that our approaches can largely help incorporate cultural knowledge into LLM-based machine translation, outperforming traditional NMT systems in translating cultural-specific sentences.

# Summary. An optional shortened abstract.
summary:  Based on clinical depression diagnostic criteria ICD-11 and DSM-5, we construct the D4-a Chinese Dialogue Dataset for Depression-Diagnosis-Oriented Chat which simulates the dialogue between doctors and patients during the diagnosis of depression.

tags: ["machine translation","cultural awareness"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2305.14328.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Cultural Translation Errors'
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

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
