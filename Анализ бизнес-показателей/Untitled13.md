

```python
import pandas as pd  # <импорт библиотеки pandas>
```


```python
df = pd.read_csv('/datasets/data.csv')  # <чтение файла с данными с сохранением в df>
```


```python
df.head(10) # <получение первых 10 строк таблицы df>
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
      <th>children</th>
      <th>days_employed</th>
      <th>dob_years</th>
      <th>education</th>
      <th>education_id</th>
      <th>family_status</th>
      <th>family_status_id</th>
      <th>gender</th>
      <th>income_type</th>
      <th>debt</th>
      <th>total_income</th>
      <th>purpose</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>1</td>
      <td>-8437.673028</td>
      <td>42</td>
      <td>высшее</td>
      <td>0</td>
      <td>женат / замужем</td>
      <td>0</td>
      <td>F</td>
      <td>сотрудник</td>
      <td>0</td>
      <td>253875.639453</td>
      <td>покупка жилья</td>
    </tr>
    <tr>
      <td>1</td>
      <td>1</td>
      <td>-4024.803754</td>
      <td>36</td>
      <td>среднее</td>
      <td>1</td>
      <td>женат / замужем</td>
      <td>0</td>
      <td>F</td>
      <td>сотрудник</td>
      <td>0</td>
      <td>112080.014102</td>
      <td>приобретение автомобиля</td>
    </tr>
    <tr>
      <td>2</td>
      <td>0</td>
      <td>-5623.422610</td>
      <td>33</td>
      <td>Среднее</td>
      <td>1</td>
      <td>женат / замужем</td>
      <td>0</td>
      <td>M</td>
      <td>сотрудник</td>
      <td>0</td>
      <td>145885.952297</td>
      <td>покупка жилья</td>
    </tr>
    <tr>
      <td>3</td>
      <td>3</td>
      <td>-4124.747207</td>
      <td>32</td>
      <td>среднее</td>
      <td>1</td>
      <td>женат / замужем</td>
      <td>0</td>
      <td>M</td>
      <td>сотрудник</td>
      <td>0</td>
      <td>267628.550329</td>
      <td>дополнительное образование</td>
    </tr>
    <tr>
      <td>4</td>
      <td>0</td>
      <td>340266.072047</td>
      <td>53</td>
      <td>среднее</td>
      <td>1</td>
      <td>гражданский брак</td>
      <td>1</td>
      <td>F</td>
      <td>пенсионер</td>
      <td>0</td>
      <td>158616.077870</td>
      <td>сыграть свадьбу</td>
    </tr>
    <tr>
      <td>5</td>
      <td>0</td>
      <td>-926.185831</td>
      <td>27</td>
      <td>высшее</td>
      <td>0</td>
      <td>гражданский брак</td>
      <td>1</td>
      <td>M</td>
      <td>компаньон</td>
      <td>0</td>
      <td>255763.565419</td>
      <td>покупка жилья</td>
    </tr>
    <tr>
      <td>6</td>
      <td>0</td>
      <td>-2879.202052</td>
      <td>43</td>
      <td>высшее</td>
      <td>0</td>
      <td>женат / замужем</td>
      <td>0</td>
      <td>F</td>
      <td>компаньон</td>
      <td>0</td>
      <td>240525.971920</td>
      <td>операции с жильем</td>
    </tr>
    <tr>
      <td>7</td>
      <td>0</td>
      <td>-152.779569</td>
      <td>50</td>
      <td>СРЕДНЕЕ</td>
      <td>1</td>
      <td>женат / замужем</td>
      <td>0</td>
      <td>M</td>
      <td>сотрудник</td>
      <td>0</td>
      <td>135823.934197</td>
      <td>образование</td>
    </tr>
    <tr>
      <td>8</td>
      <td>2</td>
      <td>-6929.865299</td>
      <td>35</td>
      <td>ВЫСШЕЕ</td>
      <td>0</td>
      <td>гражданский брак</td>
      <td>1</td>
      <td>F</td>
      <td>сотрудник</td>
      <td>0</td>
      <td>95856.832424</td>
      <td>на проведение свадьбы</td>
    </tr>
    <tr>
      <td>9</td>
      <td>0</td>
      <td>-2188.756445</td>
      <td>41</td>
      <td>среднее</td>
      <td>1</td>
      <td>женат / замужем</td>
      <td>0</td>
      <td>M</td>
      <td>сотрудник</td>
      <td>0</td>
      <td>144425.938277</td>
      <td>покупка жилья для семьи</td>
    </tr>
  </tbody>
</table>
</div>




```python

```
