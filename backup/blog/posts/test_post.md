---
title: Testing Blog post
date: 2024-03-25
authors: [emmanuel-garza]
# slug: adding-a-badge-to-your-project
description: >
  Here's a test blog
categories:
  - General
  - C++
  - Python
  - Software Development
---

# Test blog

__You enjoy working with Material for MkDocs? Share the love! You can now add
a badge to your project's README, showing that your project is built with
Material for MkDocs.__

Material for MkDocs' logo was just added to [Simple Icons], which is used by
[Shields.io] to include logos in badges. We generated a badge for you, which
you can add to your project's README:

<!-- [![Material for MkDocs][badge]](#usage) -->

<!-- more -->

## Usage

Just copy the following snippet and paste it into your project's `README.md`:

``` markdown
[![Built with Material for MkDocs](https://img.shields.io/badge/Material_for_MkDocs-526CFE?style=for-the-badge&logo=MaterialForMkDocs&logoColor=white)](https://squidfunk.github.io/mkdocs-material/)
```

```cpp title="test.cpp"
#include <iostream>

int main()
{
    std::cout << "Hello World!" << std::endl;
    return 0; // (1)
}
```

1.  :man_raising_hand: I'm a code annotation! I can contain `code`, __formatted
    text__, images, ... basically anything that can be written in Markdown.


## Testing a math equation

$$
\operatorname{ker} f=\{g\in G:f(g)=e_{H}\}{\mbox{.}}
$$

And my beloved integral equations

\begin{equation}
\int H(\mathbf{r}, \mathbf{r}') \phi(\mathbf{r}') \text{d} \sigma = - u^\text{inc}(\mathbf{r})
\end{equation}

!!! success annotate "Helmholtz Equation"

    \begin{equation}
    \nabla^2 u + k^2 u = 0
    \end{equation}


## Using Icons

!!! note annotate "Title of Note (1)"

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

1. Here we add an annotation to the note

??? bug

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

<div class="slides">
<iframe
    src="https://docs.google.com/presentation/d/e/2PACX-1vSeSk2jhqIznpQalaYyQURoBs7sSsdcaHZlgKkmVGvrhNXP2zhBCMVUpRtl7-HR8QUSp-cEZTsu6wsE/embed?start=false&loop=false&delayms=5000"
    frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true"
    webkitallowfullscreen="true"></iframe>
</div>
