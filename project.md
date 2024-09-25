# Semester Project

**Due:** Sunday, December 8 by 11:59pm

The main goal of this semester project is for you to take the knowledge and background that you are learning this semester about data visualization and put it to good use in a new, creative effort.  The end product is a static *explanatory* visualization (i.e., a single chart or group of charts presented as a faceted chart) that reveals something interesting.  (Three previous projects are highlighted in this [blog post](https://ws-dl.blogspot.com/2022/12/2022-12-02-visualization-class-projects.html) under the CS 625 heading, though note that they had a slightly different assignment.)

This project has two internal milestones. You are welcome to submit your milestones before the deadline -- the earlier you submit, the earlier you can receive feedback that can be applied to the next part of the project.

|milestone|main tasks|deadline|
|---|---|---|
|1|choose your topic, potential datasets, brainstorm interesting questions|Sun, Oct 27|
|2|explore data, narrow questions, sketch proposed charts|Sun, Nov 17 |
|final|final chart, video, and report|Sun, Dec 8|

The full semester project is due Sunday, December 8 by 11:59pm.

Detailed requirements will be found below, but here are general guidelines:

* This is an individual assignment. No group work allowed.
* You may use any tool of your choice to perform your data cleaning and exploratory analysis.
* If you are a Computer Science student, you must use either Python or Vega-Lite to build your final chart. Otherwise, you may use any tool of your choice to build your final chart.
* The goal is to present your findings about your chosen topic. Although you may do exploratory analysis to understand your data, your visualization should focus on showing the audience what you learned.

Because you will be building a static chart, there will be an emphasis on your attention to detail. I expect to see high-quality charts produced in this project.

## Milestone 1 - Topic/Datasets/Questions

In this first step of the project, you will choose a topic and dataset and brainstorm questions to explore about the data. To submit this milestone, you will post in a Canvas Discussion Board so that you and your classmates can provide feedback on each others' work.

**Topic Selection:**  Since you can ask better questions about data you know about, you should pick a topic that you have some knowledge about or that you are personally interested in learning more about. If you have taken CS 620 (Intro to Data Science), you may use the same topic/dataset from your final project if it is appropriate.

This is also an opportunity to use ChatGPT or other AI tool to help you brainstorm ideas and/or learn more about your topic.  As an example, I used the following prompts on the topic of climate change:

* `Help me brainstorm about visualization project topics related to climate change.`
* `Where can I find data about oceans and acidifcation?`
* `What are some climate factors that could affect ocean acidification?`

**Data Sources:** [Data Sources](data.md) contains links to several public data sources. Be careful about the size of the dataset. You probably want on the order of 100s-1000s of items rather than millions.

**Questions:** Propose at least 2 questions about your topic that you could answer via visualization. For each question, state one or more hypotheses of what you might find in the data. (It doesn't matter if they turn out to be true or not.)

Good questions may involve data from multiple data sources or comparisons between attributes in a large dataset, looking for correlations or patterns in the data. For example, "[How have CO2 levels and air temperature changed over time?](http://coastalslr.blogspot.com/2018/01/sea-level-rise-for-hampton-roads-2017.html)" or "What has been the main factor in winning percentage for the top 25 college football teams -- total yards offense per game, total turnovers per game, passing yards per game, or rushing yards per game?". These should be non-trivial questions that could lead to further questions, like "why is there a difference?". Make sure that the questions are ones that would be appropriate for visualization. For example, "What is the ODU football team's highest winning percentage?" is just a matter of sorting and can be answered without visualization. See [Examples of Combining Datasets in Visualizations](combining-datasets.md) for more examples.

### Submission

See the [Project Milestone 1 - Topic](https://canvas.odu.edu/courses/161806/discussion_topics/859467) Discussion Board for the items required for submission.

## Milestone 2 - Data Exploration/Sketch Charts

After choosing your topic and initial questions, you should start exploring your data. You may want to use exploratory data analysis (EDA) techniques that you have learned in this and other classes. Through this exploration, you should be narrowing down and refining your initial questions into *a single question* that can be addressed in your visualization.

Then, sketch **at least 2 potential charts that could address your question**.  The charts should be different idioms to allow you to evaluate which will end up being the most effective representation. These sketches should preferably be done on paper, but you may use a simple drawing tool as well. At this point, I *do not* want to see charts created by any tool like Excel, Tableau, or any code.

You may end up creating or coding up charts along the way as you go through the EDA process, but I want you to *sketch* potential designs for your final chart before you spend time trying to figure out how to code it up. These sketches are meant to help you evaluate which idiom might be best to represent your data and answer your question.

### Submission

See the [Project Milestone 2 - Sketches](https://canvas.odu.edu/courses/161806/discussion_topics/859466) Discussion Board for the items required for submission.

## Final Chart

Use principles from data journalism/storytelling to implement and refine **one of your proposed charts** from Milestone 2.  You *must* include a headline that summarizes the main finding of your chart (as opposed to a title that only describes your chart) and appropriate axis labels. You are strongly encouraged to include annotations or context as needed.  This will be your final chart, so care should be taken in choosing fonts, colors, and other design/aesthetic aspects.

This final chart is to be a *single chart*. The goal is to have an explanatory visualization that explains something about your data to the viewer. This is not meant to provide an exploratory view of your data. The EDA process should be done by you through Milestone 2 to help you determine how to present your final findings.  Your single chart may be a faceted chart, but it may not consist of multiple separate charts.

Reminder: Students in the Computer Science MS or PhD programs must use either Python or Vega-Lite to implement their final chart.

### Demo Video

Create a short demo video where you walk through and explain your final visualization. You should point out the question you are addressing and how the visualization idiom you chose helps to answer the question.  Point out interesting aspects of your visualization and mention any parts that you are particularly proud of (for example, if there was something difficult that you figured out how to implement).  This demo video should be at most 5 minutes long and will be shared with your classmates (see [Submission](#submission) for instructions).

*By Friday, December 13 at 11:59pm (last day of final exams), you must have provided some positive, constructive feedback or asked a question in the Discussion Board regarding at least one of your classmate's videos.*

### Report

As always, I expect your report to include your name, CS625, date, and appropriate headings and Markdown markup for clarity and neatness. You will lose points if there are many spelling or grammatical errors.

Your report, named `project-report.md`, should include the following information:

* a brief description of your chosen dataset(s) (including link to the original source of the data)
* final question that you addressed
* appropriately-sized image of your final chart
* link to your final chart (similar to [HW3](HW3-idioms.md), include whatever links or files are needed to view the implementation of your final chart)
* explanation of how your final chart answers the question and how your headline fits your chart
* "Final Thoughts" section that provides a commentary on the development process, including roughly how much time you spent developing your visualization and what aspects took the most time
* "References" section that includes links to any examples and references that you used in completing this assignment

### Submission

You should be working in the private GitHub repo that was created for you in the odu-cs625-datavis organization. If you are working locally, make sure that you have committed and pushed your local repo, including any images you reference, to GitHub.

Submit the URL of your report (not the URL of your repo) in Canvas under Semester Project.  *If you make changes to your report after submitting in Canvas, we will use the last commit time in your repo as your assignment submission time.*

Submit the URL of your demo video in the [Project Demo Videos](https://canvas.odu.edu/courses/161806/discussion_topics/859469) Discussion Board.  In your reply, note if the video is publicly available (e.g., via YouTube) or if it requires an ODU login (e.g., ODU Zoom video published via Kaltura or in ODU OneDrive).

# Appendix

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
