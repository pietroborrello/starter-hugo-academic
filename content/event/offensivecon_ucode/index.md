---
title: Custom Processing Unit - OffensiveCon

event: OffensiveCon 2023
event_url: https://www.offensivecon.org/speakers/2023/pietro-borrello.html

location: "OffensiveCon 2023"
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: "Reverse Engineering and Customization of Intel Microcode."
abstract: "The ability to debug or simply observe the microarchitecture of closed-source CPUs has always been an exclusive privilege of the product vendors. For Intel CPUs, even the details of the high-level workings of CPU microcode were only available by digging into patents and not publicly documented.

In this talk, we present the first framework for static and dynamic analysis of Intel Atom microcode. Building upon prior research, we reverse engineer Goldmont microcode semantics and reconstruct the patching primitives for microcode customization. For static analysis, we implement a Ghidra processor module for decompilation and analysis of decrypted microcode. For dynamic analysis, we create a UEFI application that can trace and patch microcode to provide complete microcode control on Goldmont systems.

Leveraging our frameworks, we reverse engineer the confidential Intel microcode update algorithm and perform the first security analysis of its design and implementation. In three further case studies, we provide the first x86 Pointer Authentication Code (PAC) microcode implementation performing its security evaluation, design and implement fast software breakpoints (more than 1000x faster than standard breakpoints), and present constant-time microcode division, illustrating the potential security and performance benefits of microcode customization."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2023-05-20T00:00:00Z"
date_end: "2023-05-20T00:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2023-05-20T00:00:00Z"

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
projects:
- CPU
---

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Wowchemy's [*Slides*](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->
