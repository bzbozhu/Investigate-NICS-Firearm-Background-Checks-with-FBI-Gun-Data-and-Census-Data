# Investigate-NICS-Firearm-Background-Checks-with-FBI-Gun-Data-and-Census-Data
Udacity data analyst nanodegree project 2

## FBI Gun Data (original source on [GitHub](https://github.com/BuzzFeedNews/nics-firearm-background-checks))

The data comes from the FBI's National Instant Criminal Background Check System. The NICS is used by to determine whether a prospective buyer is eligible to buy firearms or explosives. Gun shops call into this system to ensure that each customer does not have a criminal record or isn’t otherwise ineligible to make a purchase. The data has been supplemented with state level data from [census.gov](https://www.census.gov/).

- The [NICS data](https://d17h27t6h515a5.cloudfront.net/topher/2017/November/5a0a4db8_gun-data/gun-data.xlsx) is found in one sheet of an .xlsx file. It contains the number of firearm checks by month, state, and type.
- The [U.S. census data](https://d17h27t6h515a5.cloudfront.net/topher/2017/November/5a0a554c_u.s.-census-data/u.s.-census-data.csv) is found in a .csv file. It contains several variables at the state level. Most variables just have one data point per state (2016), but a few have data for more than one year.

## Example Questions
- What census data is most associated with high gun per capita?
- Which states have had the highest growth in gun registrations?
- What is the overall trend of gun purchases?

## Introduction
For the final project, you will conduct your own data analysis and create a file to share that documents your findings. You should start by taking a look at your dataset and brainstorming what questions you could answer using it. Then you should use pandas and NumPy to answer the questions you are most interested in, and create a report sharing the answers. You will not be required to use inferential statistics or machine learning to complete this project, but you should make it clear in your communications that your findings are tentative. This project is open-ended in that we are not looking for one right answer.

## Step One - Choose Your Data Set
Click this [link](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/July/5b57919a_data-set-options/data-set-options.pdf) (available in a [Google doc](https://docs.google.com/document/d/e/2PACX-1vTlVmknRRnfy_4eTrjw5hYGaiQim5ctr9naaRd4V9du2B5bxpd8FEH3KtDgp8qVekw7Cj1GLk1IXdZi/pub?embedded=True) here) to open a document with links and information about data sets that you can investigate for this project. You **must** choose one of these datasets to complete the project.

## Step Two - Get Organized
Eventually you’ll want to submit your project (and share it with friends, family, and employers). Get organized before you begin. We recommend creating a single folder that will eventually contain:
- The **report** communicating your findings
- Any **Python code** you wrote as part of your analysis
- The **data set** you used (which you will not need to submit)
You may wish to use a Jupyter notebook, in which case you can submit both the code you wrote and the report of your findings in the same document. Otherwise, you will need to submit your report and code separately. If you would like a **notebook template** to help organize your investigation, you can click [here](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/April/5ac7a08a_investigate-a-dataset-template.ipynb/investigate-a-dataset-template.ipynb.zip). Or there may be a page in the project here called Project Workspace: Complete and Submit Project, where you can do all your work and submit the project.

## Step Three - Analyze Your Data
Brainstorm some questions you could answer using the data set you chose, then start answering those questions. You can find some questions in the [data set options](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/July/5b57919a_data-set-options/data-set-options.pdf) to help you get started.

Try and suggest questions that promote looking at relationships between multiple variables. You should aim to analyze at least one dependent variable and three independent variables in your investigation. Make sure you use NumPy and pandas where they are appropriate!

## Step Four - Share Your Findings
Once you have finished analyzing the data, create a report that shares the findings you found most interesting. If you use a Jupyter notebook, share your findings alongside the code you used to perform the analysis. Make sure that your report text is contained in Markdown cells to clearly distinguish your comments and findings from your code work. You should also feel free to use other tools and software to craft your final report, but make sure that you can submit your report as an HTML or PDF file so that it can be opened easily.

## Step Five - Review
Use the [Project Rubric](https://review.udacity.com/#!/projects/3176718735/rubric) to review your project. If you are happy with your submission, then you're ready to submit your project. If you see room for improvement, keep working to improve your project!
