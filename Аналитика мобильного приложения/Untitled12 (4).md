

```python
import pandas as pd
```


```python
x = ['dfghdfhbfgbnvbnvbfgfgfdgfdgdfgdfgdgdgfbfdghfdgdgdfggdfgbfgbfgbnfgbnfgbnfgnbfgnfgnvgbncvbbncvbncvbncfgbfgbcfgb', '2', '3']
y = ['a', 'b', 'c']
z = ['q', 'c']
```


```python
pd.DataFrame(index=x, data = y)
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
      <td>dfghdfhbfgbnvbnvbfgfgfdgfdgdfgdfgdgdgfbfdghfdgdgdfggdfgbfgbfgbnfgbnfgbnfgnbfgnfgnvgbncvbbncvbncvbncfgbfgbcfgb</td>
      <td>a</td>
    </tr>
    <tr>
      <td>2</td>
      <td>b</td>
    </tr>
    <tr>
      <td>3</td>
      <td>c</td>
    </tr>
  </tbody>
</table>
</div>




```python
data= []
```


```python
pd.DataFrame({'sd':x, 'dsc':y})
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
      <th>sd</th>
      <th>dsc</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>dfghdfhbfgbnvbnvbfgfgfdgfdgdfgdfgdgdgfbfdghfdg...</td>
      <td>a</td>
    </tr>
    <tr>
      <td>1</td>
      <td>2</td>
      <td>b</td>
    </tr>
    <tr>
      <td>2</td>
      <td>3</td>
      <td>c</td>
    </tr>
  </tbody>
</table>
</div>




```python

```


```python

```
