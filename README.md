# Pandas-Data-Science-Tasks
Set of real world data science tasks completed using the Python Pandas library.

## Setup

To access all of the files I recommend you fork this repo and then clone it locally. Instructions on how to do this can be found here: https://help.github.com/en/github/getting-started-with-github/fork-a-repo

The other option is to click the green "clone or download" button and then click "Download ZIP". You then should extract all of the files to the location you want to edit your code.

Installing Jupyter Notebook: https://jupyter.readthedocs.io/en/latest/install.html <br/>
Installing Pandas library: https://pandas.pydata.org/pandas-docs/stable/install.html 

## Background Information:

In this project we use Python Pandas, seaborn & Python Matplotlib to analyze and answer survey questions about stackoverflow users for diffrent years. The data contains hundreds of thousands of responses from respondents. 

For example, we observed a significant evolution in the way developers educate themselves. For the rising cohort of coders under the age of 18, online resources like videos and blogs are more popular than books and school combined

Looking into this aspects of developers:

- Key territories
- Experiences
- Developers roles
- Education
- Demographics

We start by cleaning our data. Tasks during this section include:
- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype) etc.

Once we have cleaned up our data a bit, we move the data exploration section.
- The number of countries from which there are responses in the survey and plot the ten countries with the highest number of responses
- State with the most number of developers in the <b>United States of America</b>
- Percentage of <b>Nigerian</b> developers that took part in the survey.
- The distribution of responses for the Gender.
- Compare the responses of respondents who hold a computer science degree and does who do not to see if a formal eduaction in computer science is important or not. And lot more

To answer these questions we walk through many different pandas & matplotlib methods. They include:
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using diffrent functions.
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs
