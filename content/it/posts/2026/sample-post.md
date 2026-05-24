---
title: 'Post di esempio'
date: 2026-05-23T09:00:00+01:00
tags: ["tag1", "tag2", "tag3"]
build:
  list: never
  render: always
---

{{< img src="/images/sunshine_over_seaice.jpg" alt="Sea ice floes." width="700px" >}}

# Header h1 {#custom-heading1}
## Header h2 {#custom-heading2}
### Header h3 {#custom-heading3}
#### Header h4 {#custom-heading4}

---

#### Rendering di equazioni (KaTeX)
Inline math:
{{< math >}}e^{i\pi} + 1 = 0{{< /math >}}

Display math:
$$
e^{i\pi} + 1 = 0
\tag{1}
$$

```python
def f(x):
    return x
```

#### Citazioni

> Questa è una citazione.

#### Nota a piè pagina

Reference in nota[^1].

[^1]: Questa è una nota a piè pagina
