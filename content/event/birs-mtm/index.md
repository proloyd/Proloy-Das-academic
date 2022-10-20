---
title: Multitaper Analysis of Non-stationary and Non-linear Neural Activity

event: Multitaper Spectral Analysis 
# event_url: https://example.org

location: BIRS (Banff International Research Station) Workshop
address:
  # street: 450 Serra Mall
  city: Banff
  region: Alberta
  # postcode: '94305'
  country: Canada

summary: ''
abstract: ''

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2022-06-25T16:02:00Z'
date_end: '2022-06-25T16:34:00Z'
all_day: false

# # Schedule page publish date (NOT talk date).
# publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin
  - Anuththara Rupasinghe
tags: []

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: http://www.birs.ca/events/2022/2-day-workshops/22w2230/videos/watch/202206251602-Das.html

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
#   - example
---

{{% callout note %}}
Click on the **Video** button above to view the talk.
{{% /callout %}}

Although multitaper spectral analysis of second-order stationary (s.o.s.) time-series is well established, some of the key characteristics of neural data such as non-stationarity and non-linearity of neuronal activity cannot be readily captured by existing techniques. For instance, the classical sliding window multitaper method used in analyzing non-stationary time series may undermine the underlying dynamics and lacks a precise statistical characterization of the estimates. Furthermore, existing methods for multitaper analysis of neuronal spiking observations require estimation of latent time-series that underlie spiking activity from the spiking statistics. The time-domain smoothing in the estimation procedure inadvertently introduces distortion in the subsequent spectral-domain analysis. Here, we address these issues by explicitly modeling the spectral dynamics using a state-space model where the underlying states pertain to the eigen-spectra of a quasi-stationary process. Once these states are estimated within a Bayesian framework, the spectrograms and their respective confidence intervals can be readily constructed. Next, we propose a multitaper variant tailored for neural spiking data. Assuming an s.o.s. latent process, we construct auxiliary spiking statistics akin to tapered data following point process theory, from which the corresponding eigen-spectra can be directly inferred. Finally, we develop a unified framework to infer multitaper semi-stationary spectra of neuronal ensembles from multivariate spiking observations, by combining the aforementioned approaches. We demonstrate the performance gains of our proposed methods over existing techniques through extensive simulations and application to experimentally recorded neuronal data, as well as theoretical analyses of the bias-variance trade-off.