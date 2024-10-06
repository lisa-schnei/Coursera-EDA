# Project: Coursera Exploratory Data Analysis

---

## Project Objective
Objective for this project was to do an exploratory data analysis (EDA) with python for a dataset containing scrapped data from Coursera (https://www.coursera.org/) of available courses on the website. 


**Tools used:**
Python in jupyter notebook

**Questions to answer:**
- How many different course organsations have courses on Coursera? And which have the most courses?
- What types of course certfications are available and which are most/ least available?
- What are the most popular courses & organizations based on students enrollments?
- Is there a correlation between course ratings and certification type, course difficulty or popularity (enrollments)?


## Project Content

**Coursera EDA.ipynb** - jupyter notebook file containing python code and walk-through of the EDA<br>
**coursera_data.csv** - raw data file used for the analysis

## Business insights
_A full list of key findings and insights can be found in the notebook._

&#9658; High course ratings are not correlated with having more courses available. A high course rating can also be achieved with just one, potentially niche course as a less well-known organization. <br>
&#9658; If the goal is to raise awareness of the organization, having more courses in the catalogue could be a strategy. Organizations with more courses tend to have more enrollments per course. More students enrolled in courses tend, to a low extent, also lead to better course ratings.<br>
&#9658; Most popular courses are about data science & programming (60%), wellbeing (10%) and career development (30%)<br>
&#9658; There may be an opportunity to focus on offering course types with low current availability (Advanced, Professional Certificate) that still show equal or higher demand to more widely available courses. 

## Data & Context

Coursera is an online course provider offering which offering online courses, certifications, and degress on varying topics from organizations and universities around the world. 

The data was scrapped and collected in 2020. <br>

**Data source:** __[Coursera Course Dataset](https://www.kaggle.com/datasets/siddharthm1698/coursera-course-dataset?select=coursea_data.csv)__


