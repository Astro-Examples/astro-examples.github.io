# `np.where()`

This function is used to identify the indices in an array where a condition is true. In this example, we will demonstrate its usage in several astronomical settings. 

As a general note, `np.where()` returns a *tuple*, but we generally only care about the indices (the first returned object), so it is common to see astronomers call
```
ind, = np.where(some_array>20)
```
in which the comma after `ind` implies an unpacking of the output (with the second being discarded). Equivalent to the above would be calling 
```
ind = np.where(some_array>20)[0]
```

## Examples

[back](http://astro-examples.github.io/numpy/overview)