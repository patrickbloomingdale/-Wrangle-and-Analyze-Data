# Wrangle-and-Analyze-Data
Project 7, Udacity's Data Analyst Nanodegree

***

## Introduction
Real-world data rarely comes clean. Using Python and its libraries, you will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. This is called data wrangling. You will document your wrangling efforts in a Jupyter Notebook, plus showcase them through analyses and visualizations using Python (and its libraries) and/or SQL.

The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively for you to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. More on this soon.

## Rubric

### Code Functionality and Readability
| CRITERIA                       | MEETS SPECIFICATIONS                                                       |
| ------------------------------ |----------------------------------------------------------------------------|
| The student’s code is functional.  | All project code is contained in a Jupyter Notebook named wrangle_act.ipynb and runs without errors. |
| The student’s code is readable, i.e., uses good coding practices.  | The Jupyter Notebook has an intuitive, easy-to-follow logical structure. The code uses comments effectively and is interspersed with Jupyter Notebook Markdown cells. The steps of the data wrangling process (i.e. gather, assess, and clean) are clearly identified with comments or Markdown cells, as well. |

### Gathering Data
| CRITERIA                       | MEETS SPECIFICATIONS                                                       |
| ------------------------------ |----------------------------------------------------------------------------|
| The student is able to gather data from a variety of sources and file formats.  | Data is successfully gathered: From at least the three (3) different sources on the Project Details page. In at least the three (3) different file formats on the Project Details page. Each piece of data is imported into a separate pandas DataFrame at first. |

### Assessing Data
| CRITERIA                       | MEETS SPECIFICATIONS                                                       |
| ------------------------------ |----------------------------------------------------------------------------|
| The student is able to assess data visually and programmatically for quality and tidiness.  | Two types of assessment are used: 1. Visual assessment: each piece of gathered data is displayed in the Jupyter Notebook for visual assessment purposes. Once displayed, data can additionally be assessed in an external application (e.g. Excel, text editor). 2. Programmatic assessment: pandas' functions and/or methods are used to assess the data.|
| The student is able to thoroughly assess a dataset.  | At least eight (8) data quality issues and two (2) tidiness issues are detected, and include the issues to clean to satisfy the Project Motivation. Each issue is documented in one to a few sentences each. |

### Cleaning Data
| CRITERIA                       | MEETS SPECIFICATIONS                                                       |
| ------------------------------ |----------------------------------------------------------------------------|
|  The student uses the steps in the data cleaning process to guide their cleaning efforts. | The define, code, and test steps of the cleaning process are clearly documented. |
|  The student is able to thoroughly clean a dataset programmatically. | Copies of the original pieces of data are made prior to cleaning. All issues identified in the assess phase are successfully cleaned (if possible) using Python and pandas, and include the cleaning tasks required to satisfy the Project Motivation. A tidy master dataset (or datasets, if appropriate) with all pieces of gathered data is created.|

### Storing and Acting on Wrangled Data
| CRITERIA                       | MEETS SPECIFICATIONS                                                       |
| ------------------------------ |----------------------------------------------------------------------------|
|  The student is able to store a gathered, assessed, and cleaned dataset. | Students will save their gathered, assessed, and cleaned master dataset(s) to a CSV file or a SQLite database.|
|  The student is able to act on their wrangled data to produce insights (e.g. analyses, visualizations, and/or models).   | The master dataset is analyzed using pandas or SQL in the Jupyter Notebook and at least three (3) separate insights are produced. At least one (1) labeled visualization is produced in the Jupyter Notebook using Python’s plotting libraries or in Tableau. Students must make it clear in their wrangling work that they assessed and cleaned (if necessary) the data upon which the analyses and visualizations are based. |

### Report
| CRITERIA                       | MEETS SPECIFICATIONS                                                       |
| ------------------------------ |----------------------------------------------------------------------------|
| The student is able to reflect upon and describe their data wrangling efforts.  | The student’s wrangling efforts are briefly described. This document (wrangle_report.pdf or wrangle_report.html) is concise and approximately 300-600 words in length. |
| The student is able to describe some insights found in their wrangled dataset.  | The three (3) or more insights the student found are communicated. At least one (1) visualization is included. This document (act_report.pdf or act_report.html) is at least 250 words in length.|

***
## Project files
- **wrangle_act.ipynb:** code for gathering, assessing, cleaning, analyzing, and visualizing data
- **wrangle_report.pdf:** documentation for data wrangling steps: gather, assess, and clean
- **act_report.pdf:** documentation of analysis and insights into final data
- **twitter_archive_enhanced.csv:** file as given
- **image-predictions.tsv:** file downloaded programmatically
- **tweet_json.txt:** file constructed via API
- **twitter_archive_master.csv:** combined and cleaned data
***
