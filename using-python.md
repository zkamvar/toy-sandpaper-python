---
title: 'Using Python'
teaching: 10
exercises: 2
---

:::::::::::::::::::::::::::::::::::::: questions 

- How do you write a lesson using Python and `{sandpaper}`?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Explain how to use Python with the new lesson template

::::::::::::::::::::::::::::::::::::::::::::::::

## Introduction


```python
import numpy as np
a = np.arange(6)
a2 = a[np.newaxis, :]
a2.shape
```

```{.output}
(1, 6)
```

