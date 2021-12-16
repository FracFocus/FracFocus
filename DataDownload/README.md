# DataDownload
The FFcsvData2SQLite.ipynb will download the latest FracFocus database in csv format and create or update a local SQLite database "FF_data" for data analysis

Data Source:

FracFocus website: https://fracfocus.org/

FracFocus csv data: http://fracfocusdata.org/digitaldownload/FracFocusCSV.zip

FracFocus sql data: http://fracfocusdata.org/digitaldownload/fracfocusdata.zip

**Not familiar with Python?** Easy start with Anaconda package: https://www.anaconda.com/products/individual

# Step One:
Download FracFocus data and save to SQLite database with FFcsvData2SQLite.ipynb

# Step Two:
Create a chronicle of wells reported to FracFocus.org with a date stemp by running CreateFracChronicle.ipynb

# Update Step:
Download FracFocus data and save to SQLite database with FFcsvData2SQLite.ipynb
Run UpdateFracChronicle.ipynb to log new wells reported to FracFocus.org 
