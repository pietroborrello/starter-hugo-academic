---
title: ÆPIC Leak

event: Black Hat USA 2022
event_url: https://www.blackhat.com/us-22/briefings/schedule/#aepic-leak-architecturally-leaking-uninitialized-data-from-the-microarchitecture-26559

location: "Black Hat USA 2022"
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: "Architecturally Leaking Uninitialized Data from the Microarchitecture."
abstract: "CPU vulnerabilities undermine the security guarantees provided by software- and hardware-security improvements. While the discovery of transient-execution attacks increased the interest in CPU vulnerabilities on a microarchitectural level, architectural CPU vulnerabilities are still understudied.

In this talk, we systematically analyze existing CPU vulnerabilities showing that CPUs suffer from vulnerabilities whose root causes match with those in complex software. We show that transient-execution attacks and architectural vulnerabilities often arise from the same type of bug and identify the blank spots. Investigating the blank spots, we focus on architecturally improperly initialized data locations.

We discover AEPIC Leak, the first architectural CPU bug that leaks stale data from the microarchitecture without using a side channel. AEPIC Leak works on all recent Sunny-Cove-based Intel CPUs (i.e., Ice Lake and Alder Lake) and does not require hyperthreading enabled. It architecturally leaks stale data incorrectly returned by reading undefined APIC-register ranges. AEPIC Leak samples data transferred between the L2 and last-level cache, including SGX enclave data, from the superqueue. We target data in use, e.g., register values and memory loads, as well as data at rest, e.g., SGX-enclave data pages. Even if AEPIC Leak is a sampling-based attack, we introduce techniques to precisely influence from which page and offset the attack leaks from.
Our end-to-end attack extracts AES-NI, RSA, and even the Intel SGX attestation keys from enclaves within a few seconds. We discuss mitigations and conclude that the only short-term mitigations for AEPIC Leak are to disable APIC MMIO or not rely on SGX."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2022-08-09T00:00:00Z"
date_end: "2022-08-09T00:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2022-08-09T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: "https://youtu.be/8ZWc7Hcsl8o"

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
projects:
- aepicleak
---

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Wowchemy's [*Slides*](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->
