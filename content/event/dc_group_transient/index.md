---
title: Transient Execution Attacks

event: DEFCON Group Meeting
event_url: https://defcon11396.it/meetings/meeting-may31/

location: "DEFCON Group Meeting"
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: Deep dive into transient execution attacks.
abstract: "Deep dive into how modern processor optimizations such as branch prediction and out-of-order execution may lead to the leak of secrets through the CPU's microarchitectural state. 
Numerous attacks have been proposed, and we will give an overview of these techniques' state of the art.

In the second talk, we will continue our journey into the never-ending story of Transient Execution Attacks to understand how modern processor microcomponents may still lead to arbitrary secret leakage.
Meltdown and Spectre were only the beginning. Microarchitectural Data Sampling attacks can leak data across any protection boundary.
We will understand why data may be not securely kept in any privilege boundary, and how may be impossible to enforce process, kernel or even virtual machines isolation in an SMT environment."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2019-05-31T16:00:00Z"
date_end: "2019-05-31T18:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

links:
- name: "PDF1"
  url: Transient_Execution_Attacks_explained_to_your_Grandma.pdf
- name: "PDF2"
  url: Transient_Execution_Attacks_Episode_II.pdf
- name: "Meeting"
  url: https://defcon11396.it/meetings/meeting-may31/
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
# - example
---

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Wowchemy's [*Slides*](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->
