# pydata
Data Analysis fun with Python

# Jargon
munge or wrangling is the process of cleaning up messy data into a structured form for processing.

# Import conventions

```python
import numpy as np
import matplotlib.pyplot as plt
import pandas as pd
import seaborn as sns
import statsmodels as sm
```

# Installing python version 3.6 or greater
`brew install python`

Set as default over Apples included version
`export PATH=/usr/local/opt/python/libexec/bin:$PATH`

# Running a python file

`python file_name.py`

# Running ipython

Pip is the python package manager

Install via `pip install ipython`
In terminal type `ipython`

# Necessary pacakges

`python -m pip install --user numpy scipy matplotlib ipython jupyter pandas sympy nose`

# Random code examples

```python
import numpy as np
data = { i: np.random.randn() for i in range(7) }
data     
```

