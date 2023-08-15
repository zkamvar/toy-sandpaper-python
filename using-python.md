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
```

```{.error}
Error: ModuleNotFoundError: No module named 'numpy'
```

```python
a = np.arange(6)
```

```{.error}
Error: NameError: name 'np' is not defined
```

```python
a2 = a[np.newaxis, :]
```

```{.error}
Error: NameError: name 'a' is not defined
```

```python
a2.shape
```

```{.error}
Error: NameError: name 'a2' is not defined
```

