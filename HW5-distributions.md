# Homework 5: Analyzing Data Using Distribution Charts

**Due:** Sunday, November 3, 2024 by 11:59pm  

The goal of this assignment is gain experience creating distribution charts (histogram, eCDF, boxplot) and using them to help guide further analysis of the underlying data.

## Datasets

All of the datasets for this assignment come from [Section 1. Population](https://www.census.gov/library/publications/2010/compendia/statab/130ed/population.html) from the [2011 Statistical Abstract of the United States](https://www.census.gov/library/publications/2010/compendia/statab/130ed.html). In addition to looking at the Excel spreadsheets for the Tables listed below, you should also view the [Section 1 PDF](https://www2.census.gov/library/publications/2010/compendia/statab/130ed/tables/pop.pdf). 

Both the PDF tables and the Excel spreadsheets contain Notes that you should read. In particular, many of the population figures are in thousands, so you may need to do some adjustments to your data to produce accurate distributions.

### Notes about data and data manipulation

First, make sure to include only the 50 US states in your analysis (exclude the District of Columbia). 

Many of the Census tables are in "wide" format, but most of the visualization tools will want data formatted in "long" format. Python Pandas provides the [`melt()`](https://pandas.pydata.org/docs/reference/api/pandas.melt.html) function that can convert from long to wide.  Here are a couple articles/tutorials that you might want to review if you are not familiar with melt:
* [Pandas melt() and unmelt using pivot() function](https://www.digitalocean.com/community/tutorials/pandas-melt-unmelt-pivot-function)
* [What is meant by 'tidy' data?](https://anvil.works/blog/tidy-data)

Another issue you may encounter is a hidden row 1 in the Excel spreadsheets. If you encounter a problem related to this, you can export the data to CSV format and then remove row 1 using a text editor, like Notepad++.

Finally, if you are having trouble getting Python's `read_csv()` to interpret numbers with commas as numbers, try adding the `thousands=','` parameter to the call.

## Assignment

### Part 1: Create Distribution Charts

To start your analysis, create a **boxplot**, **histogram**, and **eCDF** for the distributions described below. 

You may use whatever tools you wish to manipulate the data and create the charts. Remember that CS students must create their charts using Python or Vega-Lite in at least two HW assignments. All students may pull the datasets into a separate application and format as needed.  

Pick **one** of the three datasets to work with:

1) Table 12 - Resident Population--States (pg. 18 in PDF)
   * boxplot: Show the distributions of the population of all states in **1970, 1985, 1995, and 2009**
      * this should result in 4 separate boxplot glyphs in a single chart
   * histogram: Show the distribution of the population of all states in **one** of the years (your chart title must indicate which year)
      * your histogram should use a reasonable bin size for the data
   * eCDF: Show the distributions of the population of all states in **two** of the years (your legend must indicate which years)
   
2) Table 13 - State Population--Rank, Percent Change, And Population Density (pg. 19 in PDF)
   * boxplot: Show the distributions of the population density of all states (Population per square mile of land area) in **1970, 1980, 2000, and 2009** 
      * this should result in 4 separate boxplot glyphs in a single chart
   * histogram: Show the distribution of population density of all states in **one** of the years (your chart title must indicate which year)
      * your histogram should use a reasonable bin size for the data
   * eCDF: Show the distributions of the population density of all states in **two** of the years (your legend must indicate which years)

3) Table 29 - Urban and Rural Population by State (pg. 36 in PDF)
   * boxplot: Show the distributions of the **urban and rural populations in 2000** 
      * this should result in 2 separate boxplot glyphs in a single chart
   * histogram: Show the distribution of **either** the urban or rural population in 2000 (your chart title must indicate which)
      * your histogram should use a reasonable bin size for the data
   * eCDF: Show the distributions of **urban and rural populations in 2000**

### Part 2: Further Analysis

Use the charts that you created in Part 1 to guide further investigation of the data.  I expect to see additional charts created in this part.  This could be other types of charts that reveal something interesting.

State at least 2 interesting findings about the data and explain how you used one or more of the distribution charts to guide the investigation into this finding. These findings must be something more than a simple observation from the base charts. For example, I want something more than "80% of the states in the US have more than 1 million people". (This may or may not be true, it's just an example.)

It is fine if you want to consult additional datasets as part of your analysis.

### Things to Remember
* Look at the data before you start creating charts.
* Do a sanity-check on your results.  Do they make sense? 
* Review the in-class tutorial and read the documentation before you search the web for examples.
* Include informative axis labels and chart titles.

## Files to Include

Your GitHub repo should contain any files you used to create the charts. This includes smaller datafiles, Excel spreadsheets, Tableau workbooks, Python ipynb notebooks, Python source code, etc. Your repo should also contain images of the created charts so they can be included in your report.

## Report

Your report is an important part of this assignment.  It should be written as a narrative and not just a set of bullet points.  Your report should include your name, CS625-HW5, date, and appropriate headings and Markdown markup for clarity and neatness. You will lose points if there are many spelling or grammatical errors. 

For Part 1, you must include the following items in your report:
* describe any data manipulation you needed to perform before creating the charts
* include an appropriately-sized image of the chart
* link to the chart
    * Excel, Tableau - link to your spreadsheet/workbook in your GitHub repo
    * Vega-Lite - provide a link to your notebook (see ["Note about Using Observable"](#note-about-using-observable) for sharing instructions)
    * Seaborn in Google Colab - provide a link to your notebook (make sure to share with GTA and instructor) or link to your ipynb file in your GitHub repo
    * Seaborn locally - link to your Python code in your GitHub repo
    * other tools - ask if you have questions about what should be submitted
* describe each of your charts and how they were created (explain the code you used and include code snippets)
* discuss the advantages and disadvantages of each type of distribution chart idiom for showing these distributions (talk specifically about *these* distributions, not just their advantages and disadvantages in general)
* name 1-2 simple observations you can draw from each chart

For Part 2, you must include a full explanation of your analysis in your report, including any additional charts that were created.  How did you arrive at your findings by starting with one of the distribution charts?

As always, you must include a section titled "References", including links to any examples that you used in completing this assignment.

## Submission

You should be working in the private GitHub repo that was created for you in the odu-cs625-datavis organization. If you are working locally, make sure that you have committed and pushed your local repo, including any images you reference, to GitHub.

Submit the URL of your report (not the URL of your repo) in Canvas under HW5. This should be something like

`https://github.com/odu-cs625-datavis/fall24-mcw-username/blob/main/HW5-report.md`

*If you make changes to your report after submitting in Canvas, we will use the last commit time in your repo as your assignment submission time.*

## Note about Using Observable

Once you've been added to the @oducs-vis Observable Team, you can create private notebooks that you can use for your homework assignments. (If you have not yet been added to the team, email the GTA.)

To create a new private notebook:

* start at https://observablehq.com/@oducs-vis
* click New
* make sure **Workspace** is set to "ODUCS Vis" and **Visibility** is set to "Only You"
* click Create Notebook

To share with your instructor and GTA (for help or for grading):

* click Share
* in the **Search for a teammate** box, enter navya-teja-ogirala, weiglemc
* choose "Can Edit"
* click Add
* click Save
