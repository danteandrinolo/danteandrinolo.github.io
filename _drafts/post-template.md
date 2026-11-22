---
# HOW TO WRITE A POST
# 1. Copy this file into _posts/ and rename it YYYY-MM-DD-short-title.md (for example 2026-12-01-intro-to-mri-sampling.md).
# 2. Edit the fields below and write the post in Markdown under the second "---".
# 3. Commit and push. Files in _drafts/ are never published.
layout: post
title: my post title
date: 2026-12-01
description: one sentence shown in the blog list
tags: [tutorial] # e.g. tutorial, opinion, mri, signal-processing
categories: [tutorials] # e.g. tutorials, thoughts
related_posts: false
toc:
  sidebar: left # table of contents on the left; delete these two lines for short posts
# featured: true # pins the post to the top of the blog page
# giscus_comments: true # comments (needs the giscus section of _config.yml set up)
---

Write normal Markdown here.

## A section

Inline math works: $$ y = Ax + n $$. Display math too:

$$
\hat{x} = \arg\min_x \|Ax - y\|_2^2 + \lambda \|x\|_1
$$

Code blocks with syntax highlighting:

```python
import numpy as np
x = np.fft.ifft2(kspace)
```

Images: put the file in assets/img/ and use

{% include figure.liquid loading="eager" path="assets/img/your-image.jpg" class="img-fluid rounded z-depth-1" %}

More examples of what posts can do (tables, charts, Jupyter notebooks, citations) are in the al-folio demo posts in \_posts/ (they are hidden with published: false).
