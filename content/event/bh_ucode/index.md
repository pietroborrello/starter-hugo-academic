---
title: Custom Processing Unit

event: Black Hat USA 2022
event_url: https://www.blackhat.com/us-22/briefings/schedule/#custom-processing-unit-tracing-and-patching-intel-atom-microcode-26711

location: "Black Hat USA 2022"
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: "Tracing and Patching Intel Atom Microcode."
abstract: "The ability to debug or simply observe the microarchitecture of closed-source CPUs has always been an exclusive privilege of the product vendors. For Intel CPUs, even the details of the high-level workings of CPU microcode were only available by digging into patents and not publicly documented.

In this talk, we present the first systematic study of Intel Atom Microcode and a software-only framework that can observe, trace, and even patch microcode execution, shedding unprecedented light into the internal workings of Intel CPUs.

We develop a Ghidra decompiler for Atom Microcode and reverse-engineer how the CPU internally uses its control register bus to manage its resources. Resorting to previously disclosed undocumented instructions, we then create a framework that can gain complete control over CPU microcode by replicating such interactions.

Our framework can assemble and patch micro-instructions, hook CPU events, and trace microcode execution. To showcase its power, we trace and reverse-engineer the routines involved in the obscure Intel CPU microcode update process.

For the first time, we disclose the details of the decryption algorithms for microcode updates and the binary format of the decrypted update: an amazing discovery is that a microcode update is, in fact, a custom language interpreted by the CPU. We will make our framework available as open source."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2022-08-10T00:00:00Z"
date_end: "2022-08-10T00:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2022-08-10T00:00:00Z"

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
