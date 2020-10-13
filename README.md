# Description
**gsheet-chart** is a library which helps to make a scatter plot between the two chosen columns from your google sheet. 

### Installation
This package runs under Python 3 and above,
You can use [pip](https://pip.pypa.io/en/stable/) to install:
```pip install gsheet-chart==0.0.1```
This will also install [pandas](https://pypi.org/project/pandas/), [gspread](https://pypi.org/project/gspread/), [oauth2client](https://pypi.org/project/oauth2client/), [matplotlib](https://pypi.org/project/matplotlib/) as required dependenices for the library.

### QuickStart
After installing the library open the terminal type
```python -m gsheet-chart```
This will run the installed library

**Step 1:** For any google sheet on your google drive for which you want to create a graph, share that sheet to the **sunidhi@visualization-1602254198024.iam.gserviceaccount.com** and disable notify people.

**Step 2:** Enter the name of the file without any extensions.

**Step 3:** Enter the name of the Worksheet in the file.

**Step 4:** Enter the column names for which you want the graphs to be plotted between.

**Step 5:** You wiil be shown a scatter plot between the two columns as specified and also the plot will be saved with name **chart.jpg** in the same folder where you have installed the library.

[Link](https://pypi.org/project/gsheet-chart/1.0.0/)

### License
This repository is licensed under the MIT License. See [LICENSE](https://opensource.org/licenses/MIT) for details.