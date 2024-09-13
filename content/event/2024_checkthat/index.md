---
title: UniBO at CheckThat! 2024 Multi-lingual and Multi-label Persuasion Technique Detection in News with Data Augmentation and Sequence-Token Classifiers

event: CheckThat! at CLEF 2024
event_url: http://clef2024.clef-initiative.eu/

location: Université Grenoble Alpes
address:
  # street: 
  city: Grenoble
  region: France
  postcode: 
  country: 
    # France

summary: UniBO's top-performing participation to CheckThat! 2024 Task 3.
abstract: 'We explored persuasion technique detection in multilingual news as part of the CheckThat! Lab Task 3. Our pipeline comprises two parts. The first part is a data augmentation module, which uses a BERT-based model fine-tuned for word-alignment to project labels from source texts to machine-translated target texts. The second one is a persuasion technique classification module, leveraging two
fine-tuned BERT-based models: a sequence classifier for detecting sentences containing persuasion techniques and a set of 23 token-level classifiers for specific techniques. Our approach sis competitive in all language settings, showing hints of crosslingual transfer. Despite the research efforts in this direction, detecting persuasion techniques, especially across languages, remains challenging due to their implicit and subtle nature.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-09-12T'
date_end: '2024-09-12T16:30:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2024-09-02T16:40:00Z'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
    # 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: 'https://github.com/giorluca/checkthat24_DIT'
url_pdf: 'https://ceur-ws.org/Vol-3740/paper-39.pdf'
url_slides: ''
# url_video: 'https://youtube.com'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - example
---

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page.
 -->