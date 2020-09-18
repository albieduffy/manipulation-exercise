## Types of Breweries across USA


### Example of data set



<div>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>id</th>
      <th>name</th>
      <th>brewery_type</th>
      <th>city</th>
      <th>state</th>
      <th>postal_code</th>
      <th>created_at</th>
      <th>updated_at</th>
      <th>country</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>siluria-brewing-company</td>
      <td>Siluria Brewing Company</td>
      <td>planning</td>
      <td>Alabaster</td>
      <td>Alabama</td>
      <td>35007-8501</td>
      <td>2018-07-24 01:32:47.74914</td>
      <td>2018-08-23 23:20:26.994711</td>
      <td>United States</td>
    </tr>
    <tr>
      <th>1</th>
      <td>cheaha-brewing-co</td>
      <td>Cheaha Brewing Co</td>
      <td>brewpub</td>
      <td>Anniston</td>
      <td>Alabama</td>
      <td>36201-4526</td>
      <td>2018-07-24 01:32:47.439657</td>
      <td>2018-08-23 23:20:08.838388</td>
      <td>United States</td>
    </tr>
    <tr>
      <th>2</th>
      <td>avondale-brewing-co</td>
      <td>Avondale Brewing Co</td>
      <td>micro</td>
      <td>Birmingham</td>
      <td>Alabama</td>
      <td>35222-1932</td>
      <td>2018-07-24 01:32:47.255559</td>
      <td>2018-08-23 23:19:57.82527</td>
      <td>United States</td>
    </tr>
    <tr>
      <th>3</th>
      <td>trim-tab-brewing</td>
      <td>Trim Tab Brewing</td>
      <td>micro</td>
      <td>Birmingham</td>
      <td>Alabama</td>
      <td>35233-3401</td>
      <td>2018-07-24 01:32:47.815458</td>
      <td>2018-08-23 23:20:31.42326</td>
      <td>United States</td>
    </tr>
    <tr>
      <th>4</th>
      <td>cahaba-brewing-co</td>
      <td>Cahaba Brewing Co</td>
      <td>micro</td>
      <td>Birmingham</td>
      <td>Alabama</td>
      <td>35222-2911</td>
      <td>2018-07-24 01:32:47.400092</td>
      <td>2018-08-11 21:35:43.648666</td>
      <td>United States</td>
    </tr>
  </tbody>
</table>
</div>



### Breakdown of Breweries by US State


```python
state_plot = sns.countplot(y='state', data=breweries)
```


    
![png](state_plot.png)
    


### Breakdown of Breweries by Type


```python
type_plot = sns.countplot(x='brewery_type', data=breweries)
```


    
![png](type_plot.png)
    



```python

```
