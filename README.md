# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
# Name : C R SUDEEP RAJ
# Reg No : 212224040333


import pandas as pd

import numpy as np

import seaborn as sns

import matplotlib.pyplot as plt

 ## LINE PLOT :
 
 marks=[13,45,63,78]
 
 student=['ABC','QOR','EFB','TOB']
 
 plt.plot(marks,student)
 
 plt.xlabel('Marks')
 
 plt.ylabel('Student name')
 
 plt.show()
 
 student=['A','B','C','D']
 
 attendence=[90,85,73,88]
 
 plt.plot(attendence,student)
 
 plt.xlabel('Attendence')
 
 plt.ylabel('Student name')
 
 plt.show()

<img width="717" height="531" alt="Screenshot 2025-10-27 110022" src="https://github.com/user-attachments/assets/8420d722-2e4f-4a01-ab4b-0e22654a8eef" />

<img width="690" height="539" alt="Screenshot 2025-10-27 110033" src="https://github.com/user-attachments/assets/6a9c707f-2576-4eee-a6e5-571d0ed41051" />

## SCATTER PLOT :

 x=[10,20,30,40,50]

 y=[100,200,300,400,500]
 
 plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
 
 plt.show()

 x=np.arange(0,15)

 y=np.arange(0,15)
 
 x
 
 y
 
 plt.scatter(x,y,c='r')
 
 plt.xlabel('X axis')
 
 plt.ylabel('y axis')
 
 plt.title('Scatter plot')
 
 plt.show()

<img width="687" height="516" alt="Screenshot 2025-10-27 110329" src="https://github.com/user-attachments/assets/89fdebdd-e7be-4783-b612-4d1932bea132" />

<img width="697" height="549" alt="Screenshot 2025-10-27 110340" src="https://github.com/user-attachments/assets/3c9d8fef-552d-438c-ab45-9a488b2e64be" />

## PIE CHART :

 act=['eat','sleep','work','play']
 
 slices=[3,7,8,6]
 
 color=['r','y','g','b']
 
 plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 
 plt.legend()
 
 plt.show()
 
 feedback=['Good','excellent','Perfect','Ok']
 
 slices=[4,10,3,8]
 
 color=['y','r','b','g']
 
 plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 
 plt.legend()
 
 plt.show()

<img width="557" height="508" alt="Screenshot 2025-10-27 110520" src="https://github.com/user-attachments/assets/8c824115-3ba9-4d1f-bbee-26eb165e5b86" />

<img width="550" height="506" alt="Screenshot 2025-10-27 110530" src="https://github.com/user-attachments/assets/4e40e9bf-dce4-4310-b5ff-e453e3b50f7b" />

## AREA CHART :

 x = [1, 2, 3, 4, 5]
 
 y1 = [10, 12, 14, 16, 18]
 
 y2 = [5, 7, 9, 11, 13]
 
 y3 = [2, 4, 6, 8, 10]
 
 plt.fill_between(x, y1, color='blue')
 
 plt.fill_between(x, y2, color='green')
 
 plt.plot(x, y1, color='red')
 
 plt.plot(x, y2, color='black')
 
 plt.legend(['y1','y2'])
 
 plt.show()

 <img width="693" height="511" alt="image" src="https://github.com/user-attachments/assets/6c469bf6-1886-4a6b-847b-24bb990b44cf" />

## BAR CHART :

 height = [10, 24, 36, 40, 5]
 
 names = ['one', 'two', 'three', 'four', 'five']
 
 c1=['red', 'green'] 
 
 c2=['b', 'g']
 
 plt.bar (names, height, width=0.8, color=c1)
 
 plt.xlabel('x - axis')
 
 plt.ylabel('y - axis')
 
 plt.title('My bar chart!')
 
 plt.show()

<img width="701" height="558" alt="image" src="https://github.com/user-attachments/assets/e9377371-5498-4e96-a25b-4e271c7df5d3" />

## HISTOGRAM :

 x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 
 plt.hist(x, bins = 10, color='blue', alpha=0.5)
 
 plt.show()

<img width="668" height="511" alt="image" src="https://github.com/user-attachments/assets/572b74c8-1339-49f3-aa9a-793bf7602e65" />

## BOX PLOT :

 np.random.seed(0)
 
 data=np.random.normal(loc=0, scale=1, size=100)
 
 data

<img width="711" height="452" alt="image" src="https://github.com/user-attachments/assets/71a18306-f002-4c60-9944-506e4a6e8ff8" />

 fig, ax= plt.subplots()
 
 ax.boxplot(data)
 
 ax.set_xlabel('Data')
 
 ax.set_ylabel('Values')
 
 ax.set_title('Box Plot')

<img width="711" height="589" alt="image" src="https://github.com/user-attachments/assets/11f13f8f-b8ae-4fdd-8899-be5853d13d6e" />

# Result:
 
  Thus all the data visualization techniques of matplotlib has been implemented
