**Import the necessary libraries and datasets of S&P 500 and S&P Financials**


```python
import pandas as pd
import numpy as np
```


```python
df_constituents = pd.read_csv('https://datahub.io/core/s-and-p-500-companies-financials/_r/-/data/constituents.csv')
df_constituents_financials = pd.read_csv('https://datahub.io/core/s-and-p-500-companies-financials/_r/-/data/constituents-financials.csv')
```


```python
df_constituents_financials.info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 503 entries, 0 to 502
    Data columns (total 14 columns):
     #   Column          Non-Null Count  Dtype  
    ---  ------          --------------  -----  
     0   Symbol          503 non-null    object 
     1   Name            503 non-null    object 
     2   Sector          503 non-null    object 
     3   Price           501 non-null    float64
     4   Price/Earnings  474 non-null    float64
     5   Dividend Yield  406 non-null    float64
     6   Earnings/Share  500 non-null    float64
     7   52 Week Low     501 non-null    float64
     8   52 Week High    501 non-null    float64
     9   Market Cap      501 non-null    float64
     10  EBITDA          472 non-null    float64
     11  Price/Sales     501 non-null    float64
     12  Price/Book      470 non-null    float64
     13  SEC Filings     503 non-null    object 
    dtypes: float64(10), object(4)
    memory usage: 55.1+ KB
    


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```
