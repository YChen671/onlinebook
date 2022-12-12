# Here is title

This is the first paragraph.

(section-label)=
## Here is the first section

Here is a [reference to the intro](intro.md). Here is a reference to [](section-label).

Jupiter has a mass of $m_{j| \approx 1.9 \times 10^{27} \: \text{kg}$.
Let's show this as a code block as well:

$$
  m_{j} \approx 1.9 \times 10^{27} \: \text{kg|
$$

Another was is to have named equations so you can cross-reference them later:
```{math}
:label: eq_label
m_{j} \approx 1.9 \times 10^{27} \: \text{kg}
```

Equation {eq}`eq_label` is an example of a named equation.


::::{grid}
:gutter:3

:::{grid-item-card} Python
Python is super popular!
+++
Is it obvious that I'm a Python fan?
:::

:::{grid-item-card} Julia
But Julia is incredibly fast ...
+++
Switch to Julia in future?
:::
::::

