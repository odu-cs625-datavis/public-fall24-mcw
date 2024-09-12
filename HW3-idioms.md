# Homework 3: Create Visualization Idioms from Real-World Data
**Due:** Sunday, September 29, 2024 by 11:59pm  

## Assignment

The goal of this assignment is to give you experience creating charts from real-world data. You will be using US Census Bureau data to create a bar chart, a scatterplot, and a multiple line chart using at least two different visualization tools.

## Data

You must choose your data from the [2012 Statistical Abstract of the United States](https://www.census.gov/library/publications/2011/compendia/statab/131ed.html), which was the last year that this report was compiled and released.

Here are some tips for dealing with the data:

* Don't get overwhelmed by the choices, just pick a topic and go from there.
* You don't need to show the data for every state or every category in the dataset -- choose a reasonable subset that lets you demonstrate the visualization idiom.
* You don't have to keep the data in the same format as the original spreadsheet. In fact, for this assignment I recommend that you copy out just the data you need into a separate spreadsheet.
* You can do whatever is needed to get the data in the proper format for your visualization tool, it doesn't have to be done via programming.
* You don't have to use the same dataset for each type of idiom, as not all idioms will be appropriate for every dataset.

*There are a ton of different datasets here. We expect to see variety in the datasets that are chosen and in what is chosen to be visualized.*

## Creating the Charts

As stated above, create charts using three different idioms:

* bar chart
* scatterplot
* multiple line chart - *a line chart that contains multiple lines (one line per value of a categorical attribute)*

All of the charts must have a similar style ("look and feel") and must have meaningful axis labels.

You may use whatever visualization tool you wish, but CS students must use Python or Vega-Lite for at least 2 of their HW assignments (and the project) this semester.

After you have created the three charts, you must **recreate** one of the charts using a different tool. This recreation should look as close as possible to the original.

In summary, you will be creating **four charts**: three charts using one tool, and the fourth chart using a different tool.

**Note:** I do not want to see "complex" charts like stacked bar charts, grouped bar charts, or area charts. Show us that you know how to create the simple charts that are asked for and get the details right.

## Files to Include

Your GitHub repo should contain any files you used to create the charts. This includes smaller datafiles, Excel spreadsheets, Tableau workbooks, Python ipynb notebooks, Python source code, etc. Your repo should also contain images of the created charts so they can be included in your report.

## Report

Your report is an important part of this assignment. It should be written as a narrative and not just a set of bullet points.  Your report should include your name, CS625-HW3, date, and appropriate headings and Markdown markup for clarity and neatness. You will lose points if there are many spelling or grammatical errors. 

Your report must contain the following sections:

**Data**

* name the table and section of the dataset(s) you've chosen
   * for example, in class we looked at Table 133 from Section 2 Births, Deaths, Marriages, and Divorces, <https://www.census.gov/library/publications/2011/compendia/statab/131ed/births-deaths-marriages-divorces.html>
* describe any manipulation you performed on the data to prepare it for visualization, this includes choosing to use only subsets of the data (justify your decisions)

**Chart Description** 

For each chart you create, provide the following:

* explain how the visualization idiom you used was an appropriate choice for your dataset
* an idiom/mark/data/encode table
> Below is the table for [Example 2 of Grouped Bar Charts](https://github.com/odu-cs625-datavis/public-fall24-mcw/blob/main/Wk4-Chart-Redesigns.md#example-2) in [Chart Redesigns](https://github.com/odu-cs625-datavis/public-fall24-mcw/blob/main/Wk4-Chart-Redesigns.md) ([markdown code](#markdown-code-for-table)).  
>
> Idiom: Grouped Bar Chart / Mark: Line
> | Data: Attribute | Data: Attribute Type  | Encode: Channel | 
> | --- |---| --- |
> | year | key, ordered | outer horizontal spatial region (x-axis) |
> | race | key, categorical | inner horizontal spatial region (x-axis) |
> | unemployment rate | value, quantitative | vertical position on a common scale (y-axis) |
> | race | categorical | color hue |
* an appropriately-sized image of and link to each chart you created
    * Excel, Tableau - link to your spreadsheet/workbook in your GitHub repo
    * Vega-Lite - provide a link to your notebook (see ["Note about Using Observable"](#note-about-using-observable) for sharing instructions)
    * Seaborn in Google Colab - provide a link to your notebook (make sure to share with GTA and instructor) or link to your ipynb file in your GitHub repo
    * Seaborn locally - link to your Python code in your GitHub repo
    * other tools - ask if you have questions about what should be submitted
* discuss any special customizations you used

**Discussion** - For the chart that you recreated in another tool, give an assesment of which tool you thought was easier to use and customize.

**References** - List any resources you consulted. *It is not acceptable to leave this part blank.* It is OK, and even expected, that you to refer to some code examples, but they must be documented here.

## Grading

We will be focusing on the following items when grading:

* was the mapping of data to idiom appropriate?
* was the idiom/mark/data/encode table correct?
* did the charts have meaningful axis labels?
* was the report complete and free of significant formatting or grammatical errors?

## Submission

You should be working in the private GitHub repo that was created for you in the odu-cs625-datavis organization. If you are working locally, make sure that you have committed and pushed your local repo, including any images you reference, to GitHub.

Submit the URL of your report (not the URL of your repo) in Canvas under HW3. This should be something like

`https://github.com/odu-cs625-datavis/fall24-mcw-username/blob/main/HW3-report.md` 

*If you make changes to your report after submitting in Canvas, we will use the last commit time in your repo as your assignment submission time.*

# Appendix

## Markdown Code for Table

```
Idiom: Grouped Bar Chart / Mark: Line
| Data: Attribute | Data: Attribute Type  | Encode: Channel | 
| --- |---| --- |
| year | key, ordered | outer horizontal spatial region (x-axis) |
| unemployment rate | value, quantitative | vertical position on a common scale (x-axis) |
| race | categorical | inner horizontal spatial region |
| race | categorical | color hue |
```

## Note about Using Observable

Once you've been added to the @oducs-vis Observable Team, you can create private notebooks that you can use for your homework assignments.

To create a new private notebook:

* start at https://observablehq.com/@oducs-vis
* click New
* make sure **Workspace** is set to "ODUCS Vis" and **Visibility** is set to "Only You"
* click Create Notebook

To share with your instructor and GTA (for help or for grading):

* click Share
* in the **Search for a teammate** box, enter navya-teja-ogirala, weiglemc so that both Navya (GTA) and Dr. Weigle can access it
* choose "Can Edit"
* click Add
* click Save

Note that after the semester, you will be removed from the Team. We'll send an email to remind you and give you time to copy your notebooks elsewhere before that happens (you can transfer ownership to your own account). We would appreciate that you remove mention of CS 625 from the notebooks before making them public.
