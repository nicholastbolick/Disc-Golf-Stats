# Disc-Golf-Stats
This ongoing project is my attempt to become the Nate Silver of disc golf.

The finished product will include a continually updated SQL database which relates
tournament results to course and weather conditions. I will then fit regression 
models to each golfer's results and try to predict what will happen in upcoming 
tournaments. 

Here are the Jupyter Notebooks you'll find:

golfers.ipynb
- Webscraped PDGA's database of touring pros into a Pandas DataFrame
- Cleaned data by stripping unwanted characters, filling/dropping NaNs, etc.
- Created useful columns using Pandas methods, loops and list comprehensions
- Performed exploratory analysis and displayed findings using MatPlotLib

courses.ipynb
- Webscraped dgcoursereviews.com's course database using BeautifulSoup 
- Cleaned data by stripping unwanted characters, filling/dropping NaNs, etc.
- Performed hypothesis testing using SciPy and Statsmodels

events.ipynb
- Webscraped PDGA's tournament results database


