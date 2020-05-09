

```python
import pandas as pd
```


```python
x = ["3123dfsafsfsdfsdsdv", "zvxczvcxv"]
y = ["a", "b"]
```


```python
pd.DataFrame(index=y, data = x)
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>0</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>a</td>
      <td>3123dfsafsfsdfsdsdv</td>
    </tr>
    <tr>
      <td>b</td>
      <td>zvxczvcxv</td>
    </tr>
  </tbody>
</table>
</div>




```python

```
