```python
#导入pandas
import pandas as pd
#以一维序列或是面板形式体现
from pandas import Series, DataFrame
#设置表格名称
xlsx = pd.ExcelFile('C:/Users/Administrator/Desktop/caizheng.xlsx')
#具体展示哪一列表格
pd.read_excel(xlsx,'地级市面板')
```
