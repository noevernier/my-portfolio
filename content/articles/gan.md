---
title: Diffusion Models
type: page
description: The math from scratch behind diffusion models used by DALL-E 2
topic: career
image : "/images/equation-2.png"
---

Mathematical notation in a Hugo project can be enabled by using third party JavaScript libraries.

### Examples

```bash
{{ if or .Params.math .Site.Params.math }}
{{ partial "math.html" . }}
{{ end }}
```
```python
def test(n):
    return 0
```
Block math:
$$
 \varphi = 1+\frac{1} {1+\frac{1} {1+\frac{1} {1+\cdots} } }
$$
Inline math: \\(\varphi = \dfrac{1+\sqrt5}{2}= 1.6180339887\ldots\\)
