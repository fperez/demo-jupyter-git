# A simple markdown demo

Markdown can contain _formatting_, 

* lists
* of
* items,

images:

![](logo.png)

mathematical $\alpha + \beta$ content:

$$
\rho \left( \frac{\partial \mathbf{u}}{\partial t} + \mathbf{u} \cdot \nabla \mathbf{u} \right) =
    -\nabla P + \eta \nabla^2 \mathbf{u} + \rho \mathbf{g}.
$$

and also code:

```python
import matplotlib.pyplot as plt
import numpy as np

g = np.random.normal(size=1000)
```

which can be executed as individual cells:

```python
plt.hist(g, bins=20);
```
