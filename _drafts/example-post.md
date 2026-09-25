---
title: "Example post: how to write here"
description: One-line summary shown on the blog index and in link previews.
tags: [self-supervised, video]
math: true        # set to true only if the post uses equations
---

This file lives in `_drafts/`, so it is **not published**. To publish a post, copy it
to `_posts/` and name it `YYYY-MM-DD-short-title.md` (the date and title go in the URL).

## Text

Normal Markdown: **bold**, *italic*, [links](https://arxiv.org), lists, tables, quotes.

> Blockquotes work too.

## Math

Inline: $$\mathcal{L} = -\sum_i q_i \log p_i$$ inside a sentence.

Display (blank line before and after):

$$
\mathcal{L}_{\text{SCD}} = H\big(s_v,\, q_i\big)
$$

## Code

```python
import torch
z = model(x)          # (B, N, D) patch features
loss = F.cross_entropy(z @ prototypes.T / tau, targets)
```

## Images

Put images in `images/blog/` and reference them like this:

![Method overview](/images/3dpov.jpg)
