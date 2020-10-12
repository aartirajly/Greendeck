# Greendeck Assignment

# Getting Started With Assignment
# Files
**README.md**  ->normal file for setup description
**setup.py** ->setup file to create a Python Library and host it on PyPi  
**credentials.json** ->GSheet credentials for API  
**token.pickel** ->token for GSheet to use in program  
**test.py** ->test file to check if the program is working or not  
# Greendeck folder
**__init__.py**  -> file where the program is implemented


# __init__.py file
This file contains a function named **gsheetplot()**. This function picks gsheet file and process it for graph representation. It asks for name of X and Y axis for which you want to plot the graph. You have to provide exactly the same name of column **(as asked in assignment)**. Although I have used my own credentials and tokens of my google drive, I have also snipped the code to take your input for ID of sheet and JSON file.


# Creating Python Library and Publishing on PyPI
Here is the link which will help you to create python library and publishing it on PyPI  
https://python-packaging.readthedocs.io/en/latest/minimal.html


# Installing the Library from PyPI
pip install Greendeck-ukanhaupa

# importing and calling the function
import Greendeck    
Greendeck.gsheetplot()


# How to select desired GSheet
Please go through the link to learn how to select a desired GSheet and enable API   
https://developers.google.com/sheets/api/quickstart/js
