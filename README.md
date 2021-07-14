# terminal-plot-python
simple numpy array plotter  in the terminal


Example code usage:


```python
import numpy as np
from stplt import stplt.plot_arr 
 
example_arr = np.linspace(0, 10, 8, endpoint=True) #this create 8 points  in x axis
plot_arr(example_arr,10)#plot_arr(arr,number of rows)
```

Built in example

```python
from stplt import stplt.sample 
sample()#uses random points and plott it
```
