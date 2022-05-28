```
!pip install xlrd 
!pip install xlwt
import pandas as pd
def read_excel_data(path):
    df=pd.read_excel(path,header=None)
    row={}
    row['ID']=df.iloc[4,10]
    row['姓名']=df.iloc[3,2]
    row['开始日期']=df.iloc[1,9].to_pydatatime()
    row['结束日期']=df.iloc[1,11].to_pydatatime()
    total=df.loc[df[1]=='总计']
    row['酒店']=total.iloc[0,4]
    row['交通费']=total.iloc[0,5]
    row['油费']=total.iloc[0,6]
    row['餐饮']=total.iloc[0,7]
    row['电话']=total.iloc[0,8]
    row['招待费']=total.iloc[0,9]
    row['杂费']=total.iloc[0,10]
    row['总计']=total.iloc[0,11]
    return row
    
df_all=pd.DataFrame([row])  #可以多组[row1, row2 ,row3]
df_all
```   
```
Writer=pd.ExcelWriter(path=保存的表格位置,engine='xlwt')
df_all.to_excel(Writer)
Writer.save()
```   
* df_all  返回一个excel表格   
* 写并建立excel表格储存的位置
* 把df_all转换成excel表格放到该位置
* 并保存    
