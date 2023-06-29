```python
# Import pandas package
import pandas as pd
```


```python
# Read data frame
customers = pd.read_excel(r'C:\Users\Solomon\OneDrive - campus.tu-berlin.de\Documents\Python Essential Training\Customer Call List.xlsx')
customers
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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Not_Useful_Column</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>123/643/9775</td>
      <td>93 West Main Street</td>
      <td>No</td>
      <td>Yes</td>
      <td>False</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Walter</td>
      <td>/White</td>
      <td>7066950392</td>
      <td>298 Drugs Driveway</td>
      <td>N</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>123-543-2345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Yes</td>
      <td>Y</td>
      <td>True</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876|678|3469</td>
      <td>123 Dragons Road</td>
      <td>Y</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>304-762-2467</td>
      <td>768 City Parkway</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td>NaN</td>
      <td>1209 South Street</td>
      <td>No</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876|678|3469</td>
      <td>98 Clue Drive</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009</td>
      <td>Gandalf</td>
      <td>NaN</td>
      <td>N/a</td>
      <td>123 Middle Earth</td>
      <td>Yes</td>
      <td>NaN</td>
      <td>False</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td>NaN</td>
      <td>612 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012</td>
      <td>Harry</td>
      <td>...Potter</td>
      <td>7066950392</td>
      <td>2394 Hogwarts Avenue</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>N</td>
      <td>False</td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876|678|3469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson_</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>N</td>
      <td>False</td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123/643/9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018</td>
      <td>Clark</td>
      <td>Kent</td>
      <td>7066950392</td>
      <td>3498 Super Lane</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>18</th>
      <td>1019</td>
      <td>Creed</td>
      <td>Braton</td>
      <td>N/a</td>
      <td>N/a</td>
      <td>N/a</td>
      <td>Yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876|678|3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>N</td>
      <td>True</td>
    </tr>
    <tr>
      <th>20</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876|678|3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>N</td>
      <td>True</td>
    </tr>
  </tbody>
</table>
</div>



### Dropping Duplicates



```python
# Check for duplicate records
customers.duplicated()
```




    0     False
    1     False
    2     False
    3     False
    4     False
    5     False
    6     False
    7     False
    8     False
    9     False
    10    False
    11    False
    12    False
    13    False
    14    False
    15    False
    16    False
    17    False
    18    False
    19    False
    20     True
    dtype: bool




```python
# Dropping Duplicates
customers = customers.drop_duplicates()
customers
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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Not_Useful_Column</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>123/643/9775</td>
      <td>93 West Main Street</td>
      <td>No</td>
      <td>Yes</td>
      <td>False</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Walter</td>
      <td>/White</td>
      <td>7066950392</td>
      <td>298 Drugs Driveway</td>
      <td>N</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>123-543-2345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Yes</td>
      <td>Y</td>
      <td>True</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876|678|3469</td>
      <td>123 Dragons Road</td>
      <td>Y</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>304-762-2467</td>
      <td>768 City Parkway</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td>NaN</td>
      <td>1209 South Street</td>
      <td>No</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876|678|3469</td>
      <td>98 Clue Drive</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009</td>
      <td>Gandalf</td>
      <td>NaN</td>
      <td>N/a</td>
      <td>123 Middle Earth</td>
      <td>Yes</td>
      <td>NaN</td>
      <td>False</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td>NaN</td>
      <td>612 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012</td>
      <td>Harry</td>
      <td>...Potter</td>
      <td>7066950392</td>
      <td>2394 Hogwarts Avenue</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>N</td>
      <td>False</td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876|678|3469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson_</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>N</td>
      <td>False</td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123/643/9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018</td>
      <td>Clark</td>
      <td>Kent</td>
      <td>7066950392</td>
      <td>3498 Super Lane</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>18</th>
      <td>1019</td>
      <td>Creed</td>
      <td>Braton</td>
      <td>N/a</td>
      <td>N/a</td>
      <td>N/a</td>
      <td>Yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876|678|3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>N</td>
      <td>True</td>
    </tr>
  </tbody>
</table>
</div>



#### Deleting unnessecary column


```python
# Deleting column named 'Not_Useful_Column'
customers.drop(columns = "Not_Useful_Column")
customers
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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Not_Useful_Column</th>
      <th>Street_Address</th>
      <th>State</th>
      <th>Zip_Code</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
      <td>123 Shire Lane</td>
      <td>Shire</td>
      <td>None</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>123-643-9775</td>
      <td>93 West Main Street</td>
      <td>No</td>
      <td>Yes</td>
      <td>False</td>
      <td>93 West Main Street</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Walter</td>
      <td>White</td>
      <td></td>
      <td>298 Drugs Driveway</td>
      <td>No</td>
      <td>NaN</td>
      <td>True</td>
      <td>298 Drugs Driveway</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>123-543-2345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Yes</td>
      <td>Y</td>
      <td>True</td>
      <td>980 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td>18503</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876-678-3469</td>
      <td>123 Dragons Road</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
      <td>123 Dragons Road</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>304-762-2467</td>
      <td>768 City Parkway</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>True</td>
      <td>768 City Parkway</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td></td>
      <td>1209 South Street</td>
      <td>No</td>
      <td>No</td>
      <td>False</td>
      <td>1209 South Street</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876-678-3469</td>
      <td>98 Clue Drive</td>
      <td>No</td>
      <td>No</td>
      <td>False</td>
      <td>98 Clue Drive</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009</td>
      <td>Gandalf</td>
      <td>NaN</td>
      <td></td>
      <td>123 Middle Earth</td>
      <td>Yes</td>
      <td>NaN</td>
      <td>False</td>
      <td>123 Middle Earth</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
      <td>25th Main Street</td>
      <td>New York</td>
      <td>None</td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td></td>
      <td>612 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
      <td>612 Shire Lane</td>
      <td>Shire</td>
      <td>None</td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012</td>
      <td>Harry</td>
      <td>Potter</td>
      <td></td>
      <td>2394 Hogwarts Avenue</td>
      <td>Yes</td>
      <td>NaN</td>
      <td>True</td>
      <td>2394 Hogwarts Avenue</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>N</td>
      <td>False</td>
      <td>2039 Main Street</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876-678-3469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
      <td>343 City Parkway</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>No</td>
      <td>No</td>
      <td>False</td>
      <td>214 HR Avenue</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>N</td>
      <td>False</td>
      <td>2395 Hogwarts Avenue</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123-643-9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
      <td>121 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td>None</td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018</td>
      <td>Clark</td>
      <td>Kent</td>
      <td></td>
      <td>3498 Super Lane</td>
      <td>Yes</td>
      <td>NaN</td>
      <td>True</td>
      <td>3498 Super Lane</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>18</th>
      <td>1019</td>
      <td>Creed</td>
      <td>Braton</td>
      <td></td>
      <td>N/a</td>
      <td></td>
      <td>Yes</td>
      <td>True</td>
      <td></td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876-678-3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>N</td>
      <td>True</td>
      <td>910 Tatooine Road</td>
      <td>Tatooine</td>
      <td>None</td>
    </tr>
  </tbody>
</table>
</div>



#### Cleaning First Name Column


```python
# Cleaning column usign strip()
customers["Last_Name"]= customers["Last_Name"].str.lstrip("...")
customers["Last_Name"]= customers["Last_Name"].str.lstrip("/")
customers["Last_Name"]= customers["Last_Name"].str.rstrip("_")
customers

#Simple and best way is to put all in one bracket
## customers["Last_Name"]= customers["Last_Name"].str.strip("123._/")
```

    C:\Users\Solomon\AppData\Local\Temp\ipykernel_9608\768032072.py:2: SettingWithCopyWarning: 
    A value is trying to be set on a copy of a slice from a DataFrame.
    Try using .loc[row_indexer,col_indexer] = value instead
    
    See the caveats in the documentation: https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#returning-a-view-versus-a-copy
      customers["Last_Name"]= customers["Last_Name"].str.lstrip("...")
    C:\Users\Solomon\AppData\Local\Temp\ipykernel_9608\768032072.py:3: SettingWithCopyWarning: 
    A value is trying to be set on a copy of a slice from a DataFrame.
    Try using .loc[row_indexer,col_indexer] = value instead
    
    See the caveats in the documentation: https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#returning-a-view-versus-a-copy
      customers["Last_Name"]= customers["Last_Name"].str.lstrip("/")
    C:\Users\Solomon\AppData\Local\Temp\ipykernel_9608\768032072.py:4: SettingWithCopyWarning: 
    A value is trying to be set on a copy of a slice from a DataFrame.
    Try using .loc[row_indexer,col_indexer] = value instead
    
    See the caveats in the documentation: https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#returning-a-view-versus-a-copy
      customers["Last_Name"]= customers["Last_Name"].str.rstrip("_")
    




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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Not_Useful_Column</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>123/643/9775</td>
      <td>93 West Main Street</td>
      <td>No</td>
      <td>Yes</td>
      <td>False</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Walter</td>
      <td>White</td>
      <td>7066950392</td>
      <td>298 Drugs Driveway</td>
      <td>N</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>123-543-2345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Yes</td>
      <td>Y</td>
      <td>True</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876|678|3469</td>
      <td>123 Dragons Road</td>
      <td>Y</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>304-762-2467</td>
      <td>768 City Parkway</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td>NaN</td>
      <td>1209 South Street</td>
      <td>No</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876|678|3469</td>
      <td>98 Clue Drive</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009</td>
      <td>Gandalf</td>
      <td>NaN</td>
      <td>N/a</td>
      <td>123 Middle Earth</td>
      <td>Yes</td>
      <td>NaN</td>
      <td>False</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td>NaN</td>
      <td>612 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012</td>
      <td>Harry</td>
      <td>Potter</td>
      <td>7066950392</td>
      <td>2394 Hogwarts Avenue</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>N</td>
      <td>False</td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876|678|3469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>N</td>
      <td>False</td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123/643/9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018</td>
      <td>Clark</td>
      <td>Kent</td>
      <td>7066950392</td>
      <td>3498 Super Lane</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>18</th>
      <td>1019</td>
      <td>Creed</td>
      <td>Braton</td>
      <td>N/a</td>
      <td>N/a</td>
      <td>N/a</td>
      <td>Yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876|678|3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>N</td>
      <td>True</td>
    </tr>
  </tbody>
</table>
</div>



#### Standardizing phone numbers


```python
# Standardizing phone numbers (removing '-','/','|')
customers["Phone_Number"]= customers["Phone_Number"].str.replace('[^a-zA-Z0-9]','')
customers

```

    C:\Users\Solomon\AppData\Local\Temp\ipykernel_9608\233114475.py:2: FutureWarning: The default value of regex will change from True to False in a future version.
      customers["Phone_Number"]= customers["Phone_Number"].str.replace('[^a-zA-Z0-9]','')
    C:\Users\Solomon\AppData\Local\Temp\ipykernel_9608\233114475.py:2: SettingWithCopyWarning: 
    A value is trying to be set on a copy of a slice from a DataFrame.
    Try using .loc[row_indexer,col_indexer] = value instead
    
    See the caveats in the documentation: https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#returning-a-view-versus-a-copy
      customers["Phone_Number"]= customers["Phone_Number"].str.replace('[^a-zA-Z0-9]','')
    




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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Not_Useful_Column</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>1235455421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>1236439775</td>
      <td>93 West Main Street</td>
      <td>No</td>
      <td>Yes</td>
      <td>False</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Walter</td>
      <td>White</td>
      <td>NaN</td>
      <td>298 Drugs Driveway</td>
      <td>N</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>1235432345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Yes</td>
      <td>Y</td>
      <td>True</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>8766783469</td>
      <td>123 Dragons Road</td>
      <td>Y</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>3047622467</td>
      <td>768 City Parkway</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td>NaN</td>
      <td>1209 South Street</td>
      <td>No</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>8766783469</td>
      <td>98 Clue Drive</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009</td>
      <td>Gandalf</td>
      <td>NaN</td>
      <td>Na</td>
      <td>123 Middle Earth</td>
      <td>Yes</td>
      <td>NaN</td>
      <td>False</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>1235455421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td>NaN</td>
      <td>612 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012</td>
      <td>Harry</td>
      <td>Potter</td>
      <td>NaN</td>
      <td>2394 Hogwarts Avenue</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>1235432345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>N</td>
      <td>False</td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>8766783469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson</td>
      <td>3047622467</td>
      <td>214 HR Avenue</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>1235455421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>N</td>
      <td>False</td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>1236439775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018</td>
      <td>Clark</td>
      <td>Kent</td>
      <td>NaN</td>
      <td>3498 Super Lane</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>18</th>
      <td>1019</td>
      <td>Creed</td>
      <td>Braton</td>
      <td>Na</td>
      <td>N/a</td>
      <td>N/a</td>
      <td>Yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>8766783469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>N</td>
      <td>True</td>
    </tr>
  </tbody>
</table>
</div>




```python
# Remove NAN/na
##customers["Phone_Number"]= customers["Phone_Number"].apply(lambda x:x[0:3] + '-' + x[3:6] + '-'  + x[6:10])

#str(customers["Phone_Number"])

#customers["Phone_Number"]=customers["Phone_Number"].apply(lambda x: str(x))

customers["Phone_Number"]=customers["Phone_Number"].apply(lambda x: x[0:3] + '-' + x[3:6] + '-' + x[6:10])
customers

```

    C:\Users\Solomon\AppData\Local\Temp\ipykernel_9608\4018391582.py:8: SettingWithCopyWarning: 
    A value is trying to be set on a copy of a slice from a DataFrame.
    Try using .loc[row_indexer,col_indexer] = value instead
    
    See the caveats in the documentation: https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#returning-a-view-versus-a-copy
      customers["Phone_Number"]=customers["Phone_Number"].apply(lambda x: x[0:3] + '-' + x[3:6] + '-' + x[6:10])
    




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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Not_Useful_Column</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>123-643-9775</td>
      <td>93 West Main Street</td>
      <td>No</td>
      <td>Yes</td>
      <td>False</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Walter</td>
      <td>White</td>
      <td>nan--</td>
      <td>298 Drugs Driveway</td>
      <td>N</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>123-543-2345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Yes</td>
      <td>Y</td>
      <td>True</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876-678-3469</td>
      <td>123 Dragons Road</td>
      <td>Y</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>304-762-2467</td>
      <td>768 City Parkway</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td>nan--</td>
      <td>1209 South Street</td>
      <td>No</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876-678-3469</td>
      <td>98 Clue Drive</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009</td>
      <td>Gandalf</td>
      <td>NaN</td>
      <td>Na--</td>
      <td>123 Middle Earth</td>
      <td>Yes</td>
      <td>NaN</td>
      <td>False</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td>nan--</td>
      <td>612 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012</td>
      <td>Harry</td>
      <td>Potter</td>
      <td>nan--</td>
      <td>2394 Hogwarts Avenue</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>N</td>
      <td>False</td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876-678-3469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>N</td>
      <td>False</td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123-643-9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018</td>
      <td>Clark</td>
      <td>Kent</td>
      <td>nan--</td>
      <td>3498 Super Lane</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>18</th>
      <td>1019</td>
      <td>Creed</td>
      <td>Braton</td>
      <td>Na--</td>
      <td>N/a</td>
      <td>N/a</td>
      <td>Yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876-678-3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>N</td>
      <td>True</td>
    </tr>
  </tbody>
</table>
</div>




```python
## Remove Na/na
customers["Phone_Number"]=customers["Phone_Number"].str.replace('nan--','')
customers["Phone_Number"]=customers["Phone_Number"].str.replace('Na--','')
customers
```

    C:\Users\Solomon\AppData\Local\Temp\ipykernel_9608\517566797.py:2: SettingWithCopyWarning: 
    A value is trying to be set on a copy of a slice from a DataFrame.
    Try using .loc[row_indexer,col_indexer] = value instead
    
    See the caveats in the documentation: https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#returning-a-view-versus-a-copy
      customers["Phone_Number"]=customers["Phone_Number"].str.replace('nan--','')
    C:\Users\Solomon\AppData\Local\Temp\ipykernel_9608\517566797.py:3: SettingWithCopyWarning: 
    A value is trying to be set on a copy of a slice from a DataFrame.
    Try using .loc[row_indexer,col_indexer] = value instead
    
    See the caveats in the documentation: https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#returning-a-view-versus-a-copy
      customers["Phone_Number"]=customers["Phone_Number"].str.replace('Na--','')
    




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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Not_Useful_Column</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>123-643-9775</td>
      <td>93 West Main Street</td>
      <td>No</td>
      <td>Yes</td>
      <td>False</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Walter</td>
      <td>White</td>
      <td></td>
      <td>298 Drugs Driveway</td>
      <td>N</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>123-543-2345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Yes</td>
      <td>Y</td>
      <td>True</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876-678-3469</td>
      <td>123 Dragons Road</td>
      <td>Y</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>304-762-2467</td>
      <td>768 City Parkway</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td></td>
      <td>1209 South Street</td>
      <td>No</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876-678-3469</td>
      <td>98 Clue Drive</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009</td>
      <td>Gandalf</td>
      <td>NaN</td>
      <td></td>
      <td>123 Middle Earth</td>
      <td>Yes</td>
      <td>NaN</td>
      <td>False</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td></td>
      <td>612 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012</td>
      <td>Harry</td>
      <td>Potter</td>
      <td></td>
      <td>2394 Hogwarts Avenue</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>N</td>
      <td>False</td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876-678-3469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>N</td>
      <td>False</td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123-643-9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018</td>
      <td>Clark</td>
      <td>Kent</td>
      <td></td>
      <td>3498 Super Lane</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>18</th>
      <td>1019</td>
      <td>Creed</td>
      <td>Braton</td>
      <td></td>
      <td>N/a</td>
      <td>N/a</td>
      <td>Yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876-678-3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>N</td>
      <td>True</td>
    </tr>
  </tbody>
</table>
</div>



#### Cleaning address column - Splitting


```python
# Splitting address 
##customers["Address"].str.split(',',2, expand=True)
customers[["Street_Address", "State", "Zip_Code"]]=customers["Address"].str.split(',',2, expand=True)
customers
```

    C:\Users\Solomon\AppData\Local\Temp\ipykernel_9608\1147926338.py:3: SettingWithCopyWarning: 
    A value is trying to be set on a copy of a slice from a DataFrame.
    Try using .loc[row_indexer,col_indexer] = value instead
    
    See the caveats in the documentation: https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#returning-a-view-versus-a-copy
      customers[["Street_Address", "State", "Zip_Code"]]=customers["Address"].str.split(',',2, expand=True)
    C:\Users\Solomon\AppData\Local\Temp\ipykernel_9608\1147926338.py:3: SettingWithCopyWarning: 
    A value is trying to be set on a copy of a slice from a DataFrame.
    Try using .loc[row_indexer,col_indexer] = value instead
    
    See the caveats in the documentation: https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#returning-a-view-versus-a-copy
      customers[["Street_Address", "State", "Zip_Code"]]=customers["Address"].str.split(',',2, expand=True)
    C:\Users\Solomon\AppData\Local\Temp\ipykernel_9608\1147926338.py:3: SettingWithCopyWarning: 
    A value is trying to be set on a copy of a slice from a DataFrame.
    Try using .loc[row_indexer,col_indexer] = value instead
    
    See the caveats in the documentation: https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#returning-a-view-versus-a-copy
      customers[["Street_Address", "State", "Zip_Code"]]=customers["Address"].str.split(',',2, expand=True)
    




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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Not_Useful_Column</th>
      <th>Street_Address</th>
      <th>State</th>
      <th>Zip_Code</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
      <td>123 Shire Lane</td>
      <td>Shire</td>
      <td>None</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>123-643-9775</td>
      <td>93 West Main Street</td>
      <td>No</td>
      <td>Yes</td>
      <td>False</td>
      <td>93 West Main Street</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Walter</td>
      <td>White</td>
      <td></td>
      <td>298 Drugs Driveway</td>
      <td>N</td>
      <td>NaN</td>
      <td>True</td>
      <td>298 Drugs Driveway</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>123-543-2345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Yes</td>
      <td>Y</td>
      <td>True</td>
      <td>980 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td>18503</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876-678-3469</td>
      <td>123 Dragons Road</td>
      <td>Y</td>
      <td>No</td>
      <td>True</td>
      <td>123 Dragons Road</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>304-762-2467</td>
      <td>768 City Parkway</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>True</td>
      <td>768 City Parkway</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td></td>
      <td>1209 South Street</td>
      <td>No</td>
      <td>No</td>
      <td>False</td>
      <td>1209 South Street</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876-678-3469</td>
      <td>98 Clue Drive</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
      <td>98 Clue Drive</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009</td>
      <td>Gandalf</td>
      <td>NaN</td>
      <td></td>
      <td>123 Middle Earth</td>
      <td>Yes</td>
      <td>NaN</td>
      <td>False</td>
      <td>123 Middle Earth</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
      <td>25th Main Street</td>
      <td>New York</td>
      <td>None</td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td></td>
      <td>612 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
      <td>612 Shire Lane</td>
      <td>Shire</td>
      <td>None</td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012</td>
      <td>Harry</td>
      <td>Potter</td>
      <td></td>
      <td>2394 Hogwarts Avenue</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
      <td>2394 Hogwarts Avenue</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>N</td>
      <td>False</td>
      <td>2039 Main Street</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876-678-3469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
      <td>343 City Parkway</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
      <td>214 HR Avenue</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>N</td>
      <td>False</td>
      <td>2395 Hogwarts Avenue</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123-643-9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
      <td>121 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td>None</td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018</td>
      <td>Clark</td>
      <td>Kent</td>
      <td></td>
      <td>3498 Super Lane</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
      <td>3498 Super Lane</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>18</th>
      <td>1019</td>
      <td>Creed</td>
      <td>Braton</td>
      <td></td>
      <td>N/a</td>
      <td>N/a</td>
      <td>Yes</td>
      <td>True</td>
      <td>N/a</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876-678-3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>N</td>
      <td>True</td>
      <td>910 Tatooine Road</td>
      <td>Tatooine</td>
      <td>None</td>
    </tr>
  </tbody>
</table>
</div>



#### Standardizing Paying Cusmtomer and Do_Not_Contact Columns


```python
# Payment Customer Column
customers["Paying Customer"]=customers["Paying Customer"].str.replace('Yes','Y')
customers["Paying Customer"]=customers["Paying Customer"].str.replace('No','N')
customers["Paying Customer"]=customers["Paying Customer"].str.replace('N/a','')
customers
```

    C:\Users\Solomon\AppData\Local\Temp\ipykernel_9608\3239404259.py:1: SettingWithCopyWarning: 
    A value is trying to be set on a copy of a slice from a DataFrame.
    Try using .loc[row_indexer,col_indexer] = value instead
    
    See the caveats in the documentation: https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#returning-a-view-versus-a-copy
      customers["Paying Customer"]=customers["Paying Customer"].str.replace('Yes','Y')
    C:\Users\Solomon\AppData\Local\Temp\ipykernel_9608\3239404259.py:2: SettingWithCopyWarning: 
    A value is trying to be set on a copy of a slice from a DataFrame.
    Try using .loc[row_indexer,col_indexer] = value instead
    
    See the caveats in the documentation: https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#returning-a-view-versus-a-copy
      customers["Paying Customer"]=customers["Paying Customer"].str.replace('No','N')
    C:\Users\Solomon\AppData\Local\Temp\ipykernel_9608\3239404259.py:3: SettingWithCopyWarning: 
    A value is trying to be set on a copy of a slice from a DataFrame.
    Try using .loc[row_indexer,col_indexer] = value instead
    
    See the caveats in the documentation: https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#returning-a-view-versus-a-copy
      customers["Paying Customer"]=customers["Paying Customer"].str.replace('N/a','')
    




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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Not_Useful_Column</th>
      <th>Street_Address</th>
      <th>State</th>
      <th>Zip_Code</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Y</td>
      <td>No</td>
      <td>True</td>
      <td>123 Shire Lane</td>
      <td>Shire</td>
      <td>None</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>123-643-9775</td>
      <td>93 West Main Street</td>
      <td>N</td>
      <td>Yes</td>
      <td>False</td>
      <td>93 West Main Street</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Walter</td>
      <td>White</td>
      <td></td>
      <td>298 Drugs Driveway</td>
      <td>N</td>
      <td>NaN</td>
      <td>True</td>
      <td>298 Drugs Driveway</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>123-543-2345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Y</td>
      <td>Y</td>
      <td>True</td>
      <td>980 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td>18503</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876-678-3469</td>
      <td>123 Dragons Road</td>
      <td>Y</td>
      <td>No</td>
      <td>True</td>
      <td>123 Dragons Road</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>304-762-2467</td>
      <td>768 City Parkway</td>
      <td>Y</td>
      <td>Yes</td>
      <td>True</td>
      <td>768 City Parkway</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td></td>
      <td>1209 South Street</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
      <td>1209 South Street</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876-678-3469</td>
      <td>98 Clue Drive</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
      <td>98 Clue Drive</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009</td>
      <td>Gandalf</td>
      <td>NaN</td>
      <td></td>
      <td>123 Middle Earth</td>
      <td>Y</td>
      <td>NaN</td>
      <td>False</td>
      <td>123 Middle Earth</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Y</td>
      <td>No</td>
      <td>True</td>
      <td>25th Main Street</td>
      <td>New York</td>
      <td>None</td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td></td>
      <td>612 Shire Lane, Shire</td>
      <td>Y</td>
      <td>No</td>
      <td>True</td>
      <td>612 Shire Lane</td>
      <td>Shire</td>
      <td>None</td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012</td>
      <td>Harry</td>
      <td>Potter</td>
      <td></td>
      <td>2394 Hogwarts Avenue</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
      <td>2394 Hogwarts Avenue</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Y</td>
      <td>N</td>
      <td>False</td>
      <td>2039 Main Street</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876-678-3469</td>
      <td>343 City Parkway</td>
      <td>Y</td>
      <td>No</td>
      <td>False</td>
      <td>343 City Parkway</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
      <td>214 HR Avenue</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>N</td>
      <td>N</td>
      <td>False</td>
      <td>2395 Hogwarts Avenue</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123-643-9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Y</td>
      <td>No</td>
      <td>False</td>
      <td>121 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td>None</td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018</td>
      <td>Clark</td>
      <td>Kent</td>
      <td></td>
      <td>3498 Super Lane</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
      <td>3498 Super Lane</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>18</th>
      <td>1019</td>
      <td>Creed</td>
      <td>Braton</td>
      <td></td>
      <td>N/a</td>
      <td></td>
      <td>Yes</td>
      <td>True</td>
      <td>N/a</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876-678-3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Y</td>
      <td>N</td>
      <td>True</td>
      <td>910 Tatooine Road</td>
      <td>Tatooine</td>
      <td>None</td>
    </tr>
  </tbody>
</table>
</div>




```python
## Payment Customer Column
# Now changing 'Y' to 'Yes' and 'N' to 'No'
customers["Paying Customer"]=customers["Paying Customer"].str.replace('Y','Yes')
customers["Paying Customer"]=customers["Paying Customer"].str.replace('N','No')
customers["Paying Customer"]=customers["Paying Customer"].str.replace('','')
customers
```

    C:\Users\Solomon\AppData\Local\Temp\ipykernel_9608\338697130.py:2: SettingWithCopyWarning: 
    A value is trying to be set on a copy of a slice from a DataFrame.
    Try using .loc[row_indexer,col_indexer] = value instead
    
    See the caveats in the documentation: https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#returning-a-view-versus-a-copy
      customers["Paying Customer"]=customers["Paying Customer"].str.replace('Y','Yes')
    C:\Users\Solomon\AppData\Local\Temp\ipykernel_9608\338697130.py:3: SettingWithCopyWarning: 
    A value is trying to be set on a copy of a slice from a DataFrame.
    Try using .loc[row_indexer,col_indexer] = value instead
    
    See the caveats in the documentation: https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#returning-a-view-versus-a-copy
      customers["Paying Customer"]=customers["Paying Customer"].str.replace('N','No')
    C:\Users\Solomon\AppData\Local\Temp\ipykernel_9608\338697130.py:4: SettingWithCopyWarning: 
    A value is trying to be set on a copy of a slice from a DataFrame.
    Try using .loc[row_indexer,col_indexer] = value instead
    
    See the caveats in the documentation: https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#returning-a-view-versus-a-copy
      customers["Paying Customer"]=customers["Paying Customer"].str.replace('','')
    




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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Not_Useful_Column</th>
      <th>Street_Address</th>
      <th>State</th>
      <th>Zip_Code</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
      <td>123 Shire Lane</td>
      <td>Shire</td>
      <td>None</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>123-643-9775</td>
      <td>93 West Main Street</td>
      <td>No</td>
      <td>Yes</td>
      <td>False</td>
      <td>93 West Main Street</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Walter</td>
      <td>White</td>
      <td></td>
      <td>298 Drugs Driveway</td>
      <td>No</td>
      <td>NaN</td>
      <td>True</td>
      <td>298 Drugs Driveway</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>123-543-2345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Yes</td>
      <td>Y</td>
      <td>True</td>
      <td>980 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td>18503</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876-678-3469</td>
      <td>123 Dragons Road</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
      <td>123 Dragons Road</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>304-762-2467</td>
      <td>768 City Parkway</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>True</td>
      <td>768 City Parkway</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td></td>
      <td>1209 South Street</td>
      <td>No</td>
      <td>No</td>
      <td>False</td>
      <td>1209 South Street</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876-678-3469</td>
      <td>98 Clue Drive</td>
      <td>No</td>
      <td>No</td>
      <td>False</td>
      <td>98 Clue Drive</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009</td>
      <td>Gandalf</td>
      <td>NaN</td>
      <td></td>
      <td>123 Middle Earth</td>
      <td>Yes</td>
      <td>NaN</td>
      <td>False</td>
      <td>123 Middle Earth</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
      <td>25th Main Street</td>
      <td>New York</td>
      <td>None</td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td></td>
      <td>612 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
      <td>612 Shire Lane</td>
      <td>Shire</td>
      <td>None</td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012</td>
      <td>Harry</td>
      <td>Potter</td>
      <td></td>
      <td>2394 Hogwarts Avenue</td>
      <td>Yes</td>
      <td>NaN</td>
      <td>True</td>
      <td>2394 Hogwarts Avenue</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>N</td>
      <td>False</td>
      <td>2039 Main Street</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876-678-3469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
      <td>343 City Parkway</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>No</td>
      <td>No</td>
      <td>False</td>
      <td>214 HR Avenue</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>N</td>
      <td>False</td>
      <td>2395 Hogwarts Avenue</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123-643-9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
      <td>121 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td>None</td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018</td>
      <td>Clark</td>
      <td>Kent</td>
      <td></td>
      <td>3498 Super Lane</td>
      <td>Yes</td>
      <td>NaN</td>
      <td>True</td>
      <td>3498 Super Lane</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>18</th>
      <td>1019</td>
      <td>Creed</td>
      <td>Braton</td>
      <td></td>
      <td>N/a</td>
      <td></td>
      <td>Yes</td>
      <td>True</td>
      <td>N/a</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876-678-3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>N</td>
      <td>True</td>
      <td>910 Tatooine Road</td>
      <td>Tatooine</td>
      <td>None</td>
    </tr>
  </tbody>
</table>
</div>




```python
# Do not Contact Column
customers["Do_Not_Contact"]=customers["Do_Not_Contact"].str.replace('Yes','Y')
customers["Do_Not_Contact"]=customers["Do_Not_Contact"].str.replace('No','N')
customers["Do_Not_Contact"]=customers["Do_Not_Contact"].str.replace('N/a','')
customers
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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Street_Address</th>
      <th>State</th>
      <th>Zip_Code</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>N</td>
      <td>123 Shire Lane</td>
      <td>Shire</td>
      <td></td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>123-643-9775</td>
      <td>93 West Main Street</td>
      <td>No</td>
      <td>Y</td>
      <td>93 West Main Street</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Walter</td>
      <td>White</td>
      <td></td>
      <td>298 Drugs Driveway</td>
      <td>No</td>
      <td></td>
      <td>298 Drugs Driveway</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>123-543-2345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Yes</td>
      <td>Y</td>
      <td>980 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td>18503</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876-678-3469</td>
      <td>123 Dragons Road</td>
      <td>Yes</td>
      <td>N</td>
      <td>123 Dragons Road</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>304-762-2467</td>
      <td>768 City Parkway</td>
      <td>Yes</td>
      <td>Y</td>
      <td>768 City Parkway</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td></td>
      <td>1209 South Street</td>
      <td>No</td>
      <td>N</td>
      <td>1209 South Street</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876-678-3469</td>
      <td>98 Clue Drive</td>
      <td>No</td>
      <td>N</td>
      <td>98 Clue Drive</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009</td>
      <td>Gandalf</td>
      <td></td>
      <td></td>
      <td>123 Middle Earth</td>
      <td>Yes</td>
      <td></td>
      <td>123 Middle Earth</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>N</td>
      <td>25th Main Street</td>
      <td>New York</td>
      <td></td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td></td>
      <td>612 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>N</td>
      <td>612 Shire Lane</td>
      <td>Shire</td>
      <td></td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012</td>
      <td>Harry</td>
      <td>Potter</td>
      <td></td>
      <td>2394 Hogwarts Avenue</td>
      <td>Yes</td>
      <td></td>
      <td>2394 Hogwarts Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>N</td>
      <td>2039 Main Street</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876-678-3469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>N</td>
      <td>343 City Parkway</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>No</td>
      <td>N</td>
      <td>214 HR Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>N</td>
      <td>2395 Hogwarts Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123-643-9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>N</td>
      <td>121 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td></td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018</td>
      <td>Clark</td>
      <td>Kent</td>
      <td></td>
      <td>3498 Super Lane</td>
      <td>Yes</td>
      <td></td>
      <td>3498 Super Lane</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>18</th>
      <td>1019</td>
      <td>Creed</td>
      <td>Braton</td>
      <td></td>
      <td>N/a</td>
      <td></td>
      <td>Y</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876-678-3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>N</td>
      <td>910 Tatooine Road</td>
      <td>Tatooine</td>
      <td></td>
    </tr>
  </tbody>
</table>
</div>




```python
## D Not Contact 
# Now changing 'Y' to 'Yes' and 'N' to 'No'
customers["Do_Not_Contact"]=customers["Do_Not_Contact"].str.replace('Y','Yes')
customers["Do_Not_Contact"]=customers["Do_Not_Contact"].str.replace('N','No')
customers["Do_Not_Contact"]=customers["Do_Not_Contact"].str.replace('','')
customers
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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Street_Address</th>
      <th>State</th>
      <th>Zip_Code</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>123 Shire Lane</td>
      <td>Shire</td>
      <td></td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>123-643-9775</td>
      <td>93 West Main Street</td>
      <td>No</td>
      <td>Yes</td>
      <td>93 West Main Street</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Walter</td>
      <td>White</td>
      <td></td>
      <td>298 Drugs Driveway</td>
      <td>No</td>
      <td></td>
      <td>298 Drugs Driveway</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>123-543-2345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>980 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td>18503</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876-678-3469</td>
      <td>123 Dragons Road</td>
      <td>Yes</td>
      <td>No</td>
      <td>123 Dragons Road</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>304-762-2467</td>
      <td>768 City Parkway</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>768 City Parkway</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td></td>
      <td>1209 South Street</td>
      <td>No</td>
      <td>No</td>
      <td>1209 South Street</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876-678-3469</td>
      <td>98 Clue Drive</td>
      <td>No</td>
      <td>No</td>
      <td>98 Clue Drive</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009</td>
      <td>Gandalf</td>
      <td></td>
      <td></td>
      <td>123 Middle Earth</td>
      <td>Yes</td>
      <td></td>
      <td>123 Middle Earth</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>No</td>
      <td>25th Main Street</td>
      <td>New York</td>
      <td></td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td></td>
      <td>612 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>612 Shire Lane</td>
      <td>Shire</td>
      <td></td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012</td>
      <td>Harry</td>
      <td>Potter</td>
      <td></td>
      <td>2394 Hogwarts Avenue</td>
      <td>Yes</td>
      <td></td>
      <td>2394 Hogwarts Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>No</td>
      <td>2039 Main Street</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876-678-3469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>No</td>
      <td>343 City Parkway</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>No</td>
      <td>No</td>
      <td>214 HR Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>No</td>
      <td>2395 Hogwarts Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123-643-9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>No</td>
      <td>121 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td></td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018</td>
      <td>Clark</td>
      <td>Kent</td>
      <td></td>
      <td>3498 Super Lane</td>
      <td>Yes</td>
      <td></td>
      <td>3498 Super Lane</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>18</th>
      <td>1019</td>
      <td>Creed</td>
      <td>Braton</td>
      <td></td>
      <td>N/a</td>
      <td></td>
      <td>Yes</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876-678-3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>No</td>
      <td>910 Tatooine Road</td>
      <td>Tatooine</td>
      <td></td>
    </tr>
  </tbody>
</table>
</div>



#### Removing N/A from the entire dataframe


```python
# Remove null values
customers.fillna('')
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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Street_Address</th>
      <th>State</th>
      <th>Zip_Code</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>123 Shire Lane</td>
      <td>Shire</td>
      <td></td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>123-643-9775</td>
      <td>93 West Main Street</td>
      <td>No</td>
      <td>Yes</td>
      <td>93 West Main Street</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Walter</td>
      <td>White</td>
      <td></td>
      <td>298 Drugs Driveway</td>
      <td>No</td>
      <td></td>
      <td>298 Drugs Driveway</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>123-543-2345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>980 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td>18503</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876-678-3469</td>
      <td>123 Dragons Road</td>
      <td>Yes</td>
      <td>No</td>
      <td>123 Dragons Road</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>304-762-2467</td>
      <td>768 City Parkway</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>768 City Parkway</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td></td>
      <td>1209 South Street</td>
      <td>No</td>
      <td>No</td>
      <td>1209 South Street</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876-678-3469</td>
      <td>98 Clue Drive</td>
      <td>No</td>
      <td>No</td>
      <td>98 Clue Drive</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009</td>
      <td>Gandalf</td>
      <td></td>
      <td></td>
      <td>123 Middle Earth</td>
      <td>Yes</td>
      <td></td>
      <td>123 Middle Earth</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>No</td>
      <td>25th Main Street</td>
      <td>New York</td>
      <td></td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td></td>
      <td>612 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>612 Shire Lane</td>
      <td>Shire</td>
      <td></td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012</td>
      <td>Harry</td>
      <td>Potter</td>
      <td></td>
      <td>2394 Hogwarts Avenue</td>
      <td>Yes</td>
      <td></td>
      <td>2394 Hogwarts Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>No</td>
      <td>2039 Main Street</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876-678-3469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>No</td>
      <td>343 City Parkway</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>No</td>
      <td>No</td>
      <td>214 HR Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>No</td>
      <td>2395 Hogwarts Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123-643-9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>No</td>
      <td>121 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td></td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018</td>
      <td>Clark</td>
      <td>Kent</td>
      <td></td>
      <td>3498 Super Lane</td>
      <td>Yes</td>
      <td></td>
      <td>3498 Super Lane</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>18</th>
      <td>1019</td>
      <td>Creed</td>
      <td>Braton</td>
      <td></td>
      <td>N/a</td>
      <td></td>
      <td>Yes</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876-678-3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>No</td>
      <td>910 Tatooine Road</td>
      <td>Tatooine</td>
      <td></td>
    </tr>
  </tbody>
</table>
</div>




```python
#Remove N/a from Street_Address column
customers["Street_Address"]=customers["Street_Address"].str.replace('N/a', '')
customers
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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Street_Address</th>
      <th>State</th>
      <th>Zip_Code</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>123 Shire Lane</td>
      <td>Shire</td>
      <td></td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>123-643-9775</td>
      <td>93 West Main Street</td>
      <td>No</td>
      <td>Yes</td>
      <td>93 West Main Street</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Walter</td>
      <td>White</td>
      <td></td>
      <td>298 Drugs Driveway</td>
      <td>No</td>
      <td></td>
      <td>298 Drugs Driveway</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>123-543-2345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>980 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td>18503</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876-678-3469</td>
      <td>123 Dragons Road</td>
      <td>Yes</td>
      <td>No</td>
      <td>123 Dragons Road</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>304-762-2467</td>
      <td>768 City Parkway</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>768 City Parkway</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td></td>
      <td>1209 South Street</td>
      <td>No</td>
      <td>No</td>
      <td>1209 South Street</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876-678-3469</td>
      <td>98 Clue Drive</td>
      <td>No</td>
      <td>No</td>
      <td>98 Clue Drive</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009</td>
      <td>Gandalf</td>
      <td></td>
      <td></td>
      <td>123 Middle Earth</td>
      <td>Yes</td>
      <td></td>
      <td>123 Middle Earth</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>No</td>
      <td>25th Main Street</td>
      <td>New York</td>
      <td></td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td></td>
      <td>612 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>612 Shire Lane</td>
      <td>Shire</td>
      <td></td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012</td>
      <td>Harry</td>
      <td>Potter</td>
      <td></td>
      <td>2394 Hogwarts Avenue</td>
      <td>Yes</td>
      <td></td>
      <td>2394 Hogwarts Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>No</td>
      <td>2039 Main Street</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876-678-3469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>No</td>
      <td>343 City Parkway</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>No</td>
      <td>No</td>
      <td>214 HR Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>No</td>
      <td>2395 Hogwarts Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123-643-9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>No</td>
      <td>121 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td></td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018</td>
      <td>Clark</td>
      <td>Kent</td>
      <td></td>
      <td>3498 Super Lane</td>
      <td>Yes</td>
      <td></td>
      <td>3498 Super Lane</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>18</th>
      <td>1019</td>
      <td>Creed</td>
      <td>Braton</td>
      <td></td>
      <td>N/a</td>
      <td></td>
      <td>Yes</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876-678-3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>No</td>
      <td>910 Tatooine Road</td>
      <td>Tatooine</td>
      <td></td>
    </tr>
  </tbody>
</table>
</div>



#### Filtering Rows of Data
#### List of customers that can be contacted


```python
## 1. Filtering Do_Not_Contact. Removing all the 'Y's
## Using loop and indexing 
for x in customers.index:
    if customers.loc[x,"Phone_Number"]=='':
        customers.drop(x, inplace=True)
customers
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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Street_Address</th>
      <th>State</th>
      <th>Zip_Code</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>123 Shire Lane</td>
      <td>Shire</td>
      <td></td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>123-643-9775</td>
      <td>93 West Main Street</td>
      <td>No</td>
      <td>Yes</td>
      <td>93 West Main Street</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>123-543-2345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>980 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td>18503</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876-678-3469</td>
      <td>123 Dragons Road</td>
      <td>Yes</td>
      <td>No</td>
      <td>123 Dragons Road</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>304-762-2467</td>
      <td>768 City Parkway</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>768 City Parkway</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876-678-3469</td>
      <td>98 Clue Drive</td>
      <td>No</td>
      <td>No</td>
      <td>98 Clue Drive</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>No</td>
      <td>25th Main Street</td>
      <td>New York</td>
      <td></td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>No</td>
      <td>2039 Main Street</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876-678-3469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>No</td>
      <td>343 City Parkway</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>No</td>
      <td>No</td>
      <td>214 HR Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>No</td>
      <td>2395 Hogwarts Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123-643-9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>No</td>
      <td>121 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td></td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876-678-3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>No</td>
      <td>910 Tatooine Road</td>
      <td>Tatooine</td>
      <td></td>
    </tr>
  </tbody>
</table>
</div>




```python
## 1. Filtering Do_Not_Contact. Removing all the 'Y's or 'Yes'
## Using loop and indexing 
for x in customers.index:
    if customers.loc[x,"Do_Not_Contact"]=='Yes':
        customers.drop(x, inplace=True)
customers
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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Street_Address</th>
      <th>State</th>
      <th>Zip_Code</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>123 Shire Lane</td>
      <td>Shire</td>
      <td></td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876-678-3469</td>
      <td>123 Dragons Road</td>
      <td>Yes</td>
      <td>No</td>
      <td>123 Dragons Road</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876-678-3469</td>
      <td>98 Clue Drive</td>
      <td>No</td>
      <td>No</td>
      <td>98 Clue Drive</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>No</td>
      <td>25th Main Street</td>
      <td>New York</td>
      <td></td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>No</td>
      <td>2039 Main Street</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876-678-3469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>No</td>
      <td>343 City Parkway</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>No</td>
      <td>No</td>
      <td>214 HR Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>No</td>
      <td>2395 Hogwarts Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123-643-9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>No</td>
      <td>121 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td></td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876-678-3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>No</td>
      <td>910 Tatooine Road</td>
      <td>Tatooine</td>
      <td></td>
    </tr>
  </tbody>
</table>
</div>



#### Resetting the index


```python
customers=customers.reset_index(drop=True)
customers
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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Street_Address</th>
      <th>State</th>
      <th>Zip_Code</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>123 Shire Lane</td>
      <td>Shire</td>
      <td></td>
    </tr>
    <tr>
      <th>1</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876-678-3469</td>
      <td>123 Dragons Road</td>
      <td>Yes</td>
      <td>No</td>
      <td>123 Dragons Road</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>2</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876-678-3469</td>
      <td>98 Clue Drive</td>
      <td>No</td>
      <td>No</td>
      <td>98 Clue Drive</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>3</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>No</td>
      <td>25th Main Street</td>
      <td>New York</td>
      <td></td>
    </tr>
    <tr>
      <th>4</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>No</td>
      <td>2039 Main Street</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>5</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876-678-3469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>No</td>
      <td>343 City Parkway</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>6</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>No</td>
      <td>No</td>
      <td>214 HR Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>7</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>No</td>
      <td>2395 Hogwarts Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>8</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123-643-9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>No</td>
      <td>121 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td></td>
    </tr>
    <tr>
      <th>9</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876-678-3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>No</td>
      <td>910 Tatooine Road</td>
      <td>Tatooine</td>
      <td></td>
    </tr>
  </tbody>
</table>
</div>



#### Store the cleaned dataframe


```python
customer_cleaned_dataset = customers
```


```python
customer_cleaned_dataset
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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Street_Address</th>
      <th>State</th>
      <th>Zip_Code</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>123 Shire Lane</td>
      <td>Shire</td>
      <td></td>
    </tr>
    <tr>
      <th>1</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876-678-3469</td>
      <td>123 Dragons Road</td>
      <td>Yes</td>
      <td>No</td>
      <td>123 Dragons Road</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>2</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876-678-3469</td>
      <td>98 Clue Drive</td>
      <td>No</td>
      <td>No</td>
      <td>98 Clue Drive</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>3</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>No</td>
      <td>25th Main Street</td>
      <td>New York</td>
      <td></td>
    </tr>
    <tr>
      <th>4</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>No</td>
      <td>2039 Main Street</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>5</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876-678-3469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>No</td>
      <td>343 City Parkway</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>6</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>No</td>
      <td>No</td>
      <td>214 HR Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>7</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>No</td>
      <td>2395 Hogwarts Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>8</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123-643-9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>No</td>
      <td>121 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td></td>
    </tr>
    <tr>
      <th>9</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876-678-3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>No</td>
      <td>910 Tatooine Road</td>
      <td>Tatooine</td>
      <td></td>
    </tr>
  </tbody>
</table>
</div>




```python

```
