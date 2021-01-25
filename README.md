# python-and-openpyxl
This code is to read the excel file on your system using python and openpyxl module.
My motive is to highlight error in 4 lines of code and the solution as these errors are normal but can create serious problem.

import openpyxl
import os
os.chdir("C:\\Users\\admin\\Desktop")
wb=openpyxl.load_workbook("C:\\Users\\admin\\Desktop\\cg.xlsx")
print(type(wb))
#1st line is to use openpyexcel in python.
#2nd and #3rd line is to change directory where the path is located, i have kept it on desktop.
#4th line is to load excel file----u will have to give compleate address or else it wil show name error.
