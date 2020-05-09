```python
import pandas as pd 
```


```python
df = pd.read_excel('/Users/ryzhonkovme.com/Desktop/README.xlsx', sept='\n')
```


```python
df
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
      <th>Номер</th>
      <th>Название \n</th>
      <th>Содержание</th>
      <th>Используемые инструменты, библиотеки\n</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>1</td>
      <td>Исследование надежности заемщиков</td>
      <td>Заказчик — кредитный отдел банка. Нужно разобр...</td>
      <td>pandas\n</td>
    </tr>
    <tr>
      <td>1</td>
      <td>2</td>
      <td>Исследование объявлений о продаже квартир</td>
      <td>Определение рыночной стоимости объектов недвиж...</td>
      <td>pandas, matplotlib</td>
    </tr>
    <tr>
      <td>2</td>
      <td>3</td>
      <td>Определение перспективного тарифа для телеком ...</td>
      <td>Анализ тарифов мобильного оператора. Необходим...</td>
      <td>pandas, matplotlib, math, scipy, numpy\n\n</td>
    </tr>
    <tr>
      <td>3</td>
      <td>4</td>
      <td>Исследовательский анализ продаж компьютерных игр</td>
      <td>Интернет-магазин компьютерных игр и игр для ко...</td>
      <td>pandas, matplotlib, math, scipy, numpy, seabor...</td>
    </tr>
    <tr>
      <td>4</td>
      <td>5</td>
      <td>Аналитика в авиакомпании</td>
      <td>Анализ перелетов по моделям самолетов за опред...</td>
      <td>pandas, matplotlib, bokeh\n</td>
    </tr>
    <tr>
      <td>5</td>
      <td>6</td>
      <td>Анализ бизнес-показателей</td>
      <td>Стажировка в отделе аналитики Яндекс.Афиши. За...</td>
      <td>pandas, matplotlib, math, scipy, numpy, seabor...</td>
    </tr>
    <tr>
      <td>6</td>
      <td>7</td>
      <td>Аналитика крупного интернет-магазина</td>
      <td>Анализ результатов A/B-теста.</td>
      <td>pandas, matplotlib, math, scipy, numpy, seabor...</td>
    </tr>
    <tr>
      <td>7</td>
      <td>8</td>
      <td>Аналитика мобильного приложения</td>
      <td>ААВ-тестирование, множественное тестирование и...</td>
      <td>pandas, matplotlib, math, scipy, numpy, seabor...</td>
    </tr>
    <tr>
      <td>8</td>
      <td>9</td>
      <td>Дашборд для Яндекс.Дзен</td>
      <td>Cоздание агрегирующих таблиц, cоздание пайплай...</td>
      <td>getopt, sqlalchemy, dash, plotly</td>
    </tr>
    <tr>
      <td>9</td>
      <td>10</td>
      <td>Анализ сети фитнес-центров\n</td>
      <td>Прогнозирование вероятности оттока клиентов, к...</td>
      <td>pandas, matplotlib, plotly, seaborn, numpy, sk...</td>
    </tr>
    <tr>
      <td>10</td>
      <td>11</td>
      <td>Рынок заведений общественного питания Москвы (...</td>
      <td>Исследование текущего положение дел на рынке д...</td>
      <td>pandas, numpy, plotly\n</td>
    </tr>
    <tr>
      <td>11</td>
      <td>12</td>
      <td>Банки — Сегментация пользователей по потреблен...</td>
      <td>Анализ клиентов регионального банка и сегменти...</td>
      <td>pandas, plotly, matplotlib,\nseaborn, numpy, s...</td>
    </tr>
  </tbody>
</table>
</div>


