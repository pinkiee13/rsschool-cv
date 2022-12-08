# **Anna Moroz**
## **Contacts**
  * **Phone:**    +375298506088
  * **Email:**    morozann277@gmail.com
  * **Telegram:** @pin_kie
## **About me**
Just graduated from university with a degree in information resource management.  
Writting plugins for BIM-modeling in Python for Revit Autodesk.  
I have just started my way in the world of programming and that's why I'm open to everything new. Specially Web Development.  
Started learning Front Development.  
And I am sure that my great desire to develop myself as an IT specialist will make me professional Front Developук.
## **Skils**
  * Python, C#
  * Revit API
  * VS Code
## **Code example**
Converting PDF-tables to Excel
```
try:
  input_file=easygui.fileopenbox(title='Choose .pdf-file.',filetypes=['*.pdf'])
except:
  showerror(tirtle='Error',message='Can't open file. Please choose .pdf format and try again.')
  
 try:
  df=tabula.(input_file,pages='all',multiple_tables=True,stream=True)
  table=pandas.DataFrame()
  
  for df2 in enumerate(df):
    df2=pandas.DataFrame(df2)
    
    column_num=input('Enter number of columns to delete\t')
    for col_n in column_num:
      del df2[int(col_n)]
      
    row_num=input('Enter number of rows to delete\t')
    for row_n in row_num:
      df2.drop([int(row_n)],axis=0)
      
    table=pandas.contact([table,df2],axis=0)
   
  table.to_excel(f'smeta.xlsx',sheet_name='Sheet1',index=True,encoding='utf-8-sig)
   
 except:
  showerror(title='Error',message='Failed to convert the file.')
 
```
## **Languages**
  * Russian - native
  * English - C1 (Streamline courses)
  * German - B1 (Goethe Institut)
