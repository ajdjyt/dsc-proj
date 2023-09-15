# Data Science Community project

This is a project on EDA (Exploratory Data Analysis) on a given dataset about students containing the following columns.  
```console  
['Name', 'Age', 'Gender', 'Hours_Studied', 'IQ', 'Physics_Marks',
       'Math_Marks', 'Chemistry_Marks', 'Has_Part_Time_Job','Study_Hours_Group']
```  
Charts are saved in the 'charts' folder.  
```console
[ajdj@lin:~/clones/dsc-proj]$ ls charts
age.png  box_iq_by_part_time.png  box_marks_by_part_time.png  hours_by_iq.png  hours_studied.png  
iq.png  marks-z-score.png  marks.png  marks_by_age.png  marks_by_part_time.png  
```  
The notebook depends on:  
```
matplotlib,pandas,seaborn,numpy    
``` 
The requirements can be installed using  
```console
pip install -r eda-requirements.txt  
```
## Conculusions  
1. The IQs distribution is very even  
2. The 'class' has no age restrictions  
3. 110 IQ may be an outlier  
4. The class average score is somewhere in the low 70s, high 60s  
5. IQ has no relation with if a person is employed
6. People with less than 50 are less desired due to less than wanted skill level
7. The z-score for marks higher than 90 needs to be explored and may be a problem in the dataset 