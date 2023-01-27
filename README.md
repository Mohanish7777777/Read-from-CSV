## Read-from-CSV
### AIM:
To read and proccess the csv file

## ALGORITHM:
### Step 1:
import pandas as pd

### Step 2:
open the file in read mode

### Step 3:
print the first 9 and the tail

### Step 4:
print the rows

### Step 5:
print the columns

## PROGRAM:
```python
#developed by: Mohanish K
#reference no: 22002294
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("rows",len(df.axes[0]))
print("columns",len(df.axes[1]))
```
## OUTPUT:
![image](https://user-images.githubusercontent.com/111619160/215031255-2d082190-afaa-4317-9a89-0ec99a34b0a0.png)


## RESULT:
hence the programe is executed successfully!
