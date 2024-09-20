# CS 625, Fall 2024 Syllabus

[Jump to Summary Schedule](#summary-schedule) | [Download printable PDF version](https://github.com/odu-cs625-datavis/public-fall24-mcw/raw/main/syllabus.pdf)

Asynchronous Online

## Course Overview

*"The purpose of visualization is insight, not pictures." -Ben Shneiderman*

**Catalog Description:** This course covers the theory and application of data visualization. This includes issues in data cleaning to prepare data for visualization, theory behind mapping data to appropriate visual representations, introduction to visual analytics, and tools used for data analysis and visualization. Modern visualization software and tools will be used to analyze and visualize real-world datasets to reinforce the concepts covered in the course.

**Comparison to CS 725/825:** If you have already taken CS 725/825, then CS 625 is not appropriate for you. CS 625 is a prerequisite to CS 725/825.

## Instructor Contact and Office Hours

[Dr. Michele Weigle](https://www.cs.odu.edu/~mweigle/), mweigle at odu.edu

Office hours are times that I set aside each week to meet with students and answer questions about the course. No appointment is necessary. This semester, all office hours will be via Zoom and will be held outside of regular work hours to accomodate working students.

My office hours will be:

* Tuesday 5-6pm
* Wednesday 7:30-8:30pm
* Friday 8-9**AM**

See [Canvas](https://canvas.odu.edu/courses/161806) for the link, students will be placed into the waiting room if I am already meeting with another student.

If you cannot attend during regular office hours, please contact me to set up an alternate appointment time.

<!-- Graduate Teaching Assistant: [Kritika Garg](https://github.com/kritikagarg), kgarg001 at odu.edu-->

## Course Objectives

After completing this course, you should be able to do the following:

* Use OpenRefine to explore and clean real-world data.
* Explain the difference between exploratory (discover task) and explanatory (present task) visualizations.
* Describe the channels of visual encoding and order them from most effective to least effective.
* Identify a visualization where an inappropriate arrange design choice was made and explain why the choice was inappropriate.
* Explain how different data types map most effectively to various visualization idioms (i.e., charts).
* Explain the importance choosing an appropriate colormap.
* Given a dataset, develop questions about the data that can effectively be answered with a visualization.
* Critique and redesign an existing visualization.
* Use Tableau, Python, Vega-Lite, or other API or software to create effective standard charts, such as line charts, scatterplots, bar charts.
* Use Tableau, Python, Vega-Lite, or other API or software to create an effective visualization of real-world data.
* Explain and defend the design choices that you made in creating your visualization.

## Course Delivery Method

This course will be offered in the online asynchronous mode.

All course materials will be made available in Canvas (<https://canvas.odu.edu/courses/161806>) or via GitHub (<https://github.com/odu-cs625-datavis/public-fall24-mcw>).

### How to Be Successful in This Course

The weekly schedule will run **Monday - Sunday**.

Course materials for the coming week will be generally released on **Friday evening** or **Monday morning** at the latest.

Each week there will be a reading assignment and set of Learning Checks to test your basic comprehension of the material. For weeks when we have a textbook reading, there will also be a video from Dr. Munzner, the textbook author, walking through the chapter. In addition, I will record some lecture videos to provide additional explanation and examples.

You are encouraged to complete the reading assignment and Learning Checks and at least read over any homework assignment by **Wednesday** to ensure that you have time to ask questions before the due date.

My lecture videos will contain additional explanations and examples beyond the textbook reading and/or Dr. Munzner's video. You are encouraged to watch these by **Friday**.

Most assignments will be due **Sunday by 11:59pm**.

*If you have questions about content or assignment requirements, you must ask - either via Canvas Discussion Boards or during office hours.*

## Requirements

### Prerequisites

There are no specific course prerequisites for this course, but I expect you to be comfortable with basic statistics. Extensive programming experience is not required, but you should be familiar with basic programming concepts (variables, arrays, functions, conditionals, etc.).

Additionally, if you choose to use certain APIs (not required), you should be familiar with Unix, HTML, CSS, JavaScript, and jQuery. If you need a refresher on Unix, see the [CS 252](https://www.cs.odu.edu/~zeil/cs252/latest/Directory/outline/index.html) webpage. There are many excellent resources available online for common web languages.

### Course Materials

The required textbook for this course is *Visualization Analysis and Design* by Tamara Munzner ([online version accesssible for free via ODU](https://go.oreilly.com/old-dominion-university//library/view/visualization-analysis-and/9781466508910/))

The author maintains a [website](http://www.cs.ubc.ca/~tmm/vadbook/) with additional resources that will be used throughout our course

* author's full set of slides ([VAD-2021.pdf](https://www.cs.ubc.ca/~tmm/talks/vad/VAD-2021.pdf))
* author's [YouTube playlist of videos covering the entire book](https://www.youtube.com/playlist?list=PLT4XLHmqHJBeB5LwmRmo6ln-m7K3lGvrk)
* [PDF versions of all figures](https://www.cs.ubc.ca/~tmm/vadbook/#figures)
* [textbook errata](http://www.cs.ubc.ca/~tmm/vadbook/errata.html)
* [author's keynote at d3.unconf](https://www.youtube.com/watch?v=jVC6SQS23ak) (55 min), overview of material from book

You will be required to write clearly about your visualization designs and design process. For writing help, I always suggest two inexpensive books:

* *Writing for Computer Science* by Justin Zobel
* *The Elements of Style* by Strunk and White

In addition, see the [New Student Resources](https://weiglemc.github.io/new-student/#writing) collected by Dr. Weigle.

## Grading

### Assignment Types

Your grade in this class will be based on the following components:

**Participation** - 5%

* demonstrates engagement with the instructor and classmates
* comprised of "meaningful interactions", which can include posting a question in the Canvas Discussion Board, providing the first correct/helpful answer to a classmate's question in the Discussion Board, posting about an interesting visualization in the Discussion Board, attending office hours (or alternate meeting time) to ask a question, etc.
* rubric (0-4):
  * 4 pts - 4 or more weeks with a meaningful interaction
  * 3 pts - 3 weeks with a meaningful interaction
  * 2 pts - 2 weeks with a meaningful interaction
  * 1 pt - 1 week with a meaningful interaction
  * 0 pt - no meaningful interactions during the semester

**Learning Checks** - 15%

* demonstrates basic understanding of reading assignment
* assigned weekly
* I will not correct your answers, but correct answers with references will be viewable in Canvas after the due date
* rubric (0-2):
  * 2 pts - answered all questions and submitted on time
  * 1 pt - did not answer all questions or late submission
  * 0 pt - not submitted within 48 hours of due date

**Homework** - 30%

* demonstrates understanding of practical elements of course concepts through implementation
* requires an accompanying report that explains the implementation
* students in the MS in Computer Science program are required to complete at least two homework assignments in Python or Vega-Lite
* ~5 homework assignments during the semester
* rubric (0-10):
   * 10 pts - A+, Excellent! All questions/tasks addressed appropriately, report is clear and thorough, only minor formatting/spelling/grammatical errors, if any.
   * 9 pts - A, Good job! Most, if not all, questions/tasks addressed appropriately, report is clear but could include more explanation, and/or a few formatting/spelling/grammatical errors.
   * 8 pts - B, OK job. Not all questions/tasks addressed appropriately and/or some fairly significant formatting/spelling/grammatical errors.
   * 7 pts - C, Needs work. Several questions/tasks not addressed appropriately and/or major formatting/spelling/grammatical errors.
   * 0-5 pts - F, Not acceptable. An attempt was made to address the questions/tasks, but it did not meet the intention of the assignment.
   * +/- 0.5 pts may be applied based on individual submissions.

**Midterm Exam** - 25%

* demonstrates comprehension and application of concepts discussed during the first half of the semester
* open book, open notes

**Project** - 25%

* demonstrates understanding of course concepts by developing a single *explanatory* visualization that reveals something interesting
* requires a demo video and a report explaining design decisions and how they relate to course concepts
* same rubric as Homework

### Grading Scale

The overall grading scale is as follows:

| percentage | letter |
| --- | --- |
| 100-94 | A |
| 93-90 | A- |
| 89-88 | B+ |
| 87-84 | B |
| 83-80 | B- |
| 79-78 | C+ |
 | 77-74 | C |
| 73-70 | C- |
| 69-0 | F|

### Late Homework Assignments

Any assignment submitted after its deadline is considered late. Late assignments lose 1 point for every 24 hours they are late. Submissions over 72 hours late are not accepted. This time limit includes weekends -- they are counted just like weekdays.

* 0-24 hours late: -1 point
* 25-48 hours late: -2 points
* 49-72 hours late: -3 points
* over 72 hours late: not accepted

 I reserve the right to specify that late submissions will not be accepted for particular assignments.

## Summary Schedule

*Note: This is a tentative schedule and may change during the semester. The complete schedule with assignments and due dates will be posted on Canvas.*

[ODU Fall academic schedule](https://www.odu.edu/academics/calendar/fall)

|Week |Start Date|Topic| Textbook Reading|
|---|---|---|---|
|1| Aug 26| What's Vis and Why Do It? | Ch 1|
|2| Tue, Sep 3| Data and Data Cleaning | Ch 2|
|3| Sep 9| Marks and Channels | Ch 5|
|4| Sep 16 |Arrange Tables | Ch 7|
|5| Sep 23 | Tour through the Visualization Zoo | |
|6| Sep 30 | Map Color and Other Channels | Ch 10|
|7| Oct 7 | Reduce Items and Attributes | Ch 13 |
|8| Oct 14 | **Fall Break** (Oct 12-15)<br/>**MID-TERM EXAM** (Oct 18-20)| |
|9| Oct 21 | Exploratory Data Analysis (EDA) |  |
|10| Oct 28| Multiple Views | Ch 12 |
|11| Nov 4 | Maps, Rules of Thumb, Chart Design| Ch 8.1-8.3, Ch 6 |
|12| Nov 11 | Storytelling Vis | |
|13| Nov 18 | Visualization Literacy |  |
|14| Nov 25 | **Thanksgiving Break** (Nov 27-Dec 1) | |
|15| Dec 2 | Project Demos | |

## Course Policies

### Email/Canvas

Each student must check the class Canvas site and email daily. You should use our class Canvas Discussion Boards to ask and answer general course-related questions. I will use Canvas Announcements to notify you about important updates (assignment deadline changes, office hours cancellations, etc.).

### Seeking Help

The course Canvas site should be your first reference for questions about the class. If you have questions about course requirements or materials, post questions using the class Canvas Discussion Boards. For extra help, attend office hours.

### Use of ChatGPT and other AI Tools

The use of ChatGPT or other AI tools is permitted *to some extent* in this class. These tools are being rapidly adopted, so it is important that you have some experience with their use. 

These tools are best used to help you *work smarter*, not do your work for you. An essential part of being in graduate school is to develop skills that you will need to be successful in the workplace. If you use these tools to blindly do your homework for you, your learning will suffer and their unauthorized use will be obvious. But, if you use the tools to help clarify misunderstandings as you go, you will work and learn faster and hopefully build a solid foundation. 

To use AI tools to help improve your writing, you should write your answer first and then ask the tool to improve the style or grammar. *I want to see your ideas, not the ideas generated through the use of GenAI.* ***Do not simply use the homework question as a prompt. This is not acceptable use.***

For all homework assignments, you must include a list of websites or other references that you consult in solving the assignment. This includes AI tools. Not only must you include the website for the tool, but you must include a link to, or screenshot of, the conversation you had with the tool. (ChatGPT has the option to create a link to a conversation.) You must also write out in your HW report the initial prompt that you used.

I would also like to know how you have been using AI tools. Have you used these to help learn a new API or programming language? To help correct spelling and grammar or otherwise improve your writing?  Please share any useful prompts you've discovered to the "Useful AI Prompts" Discussion board in Canvas.

**Extra Credit:** If you find an error when using an AI tool for something related to our course content, including a programming error, you can submit this for potential extra credit. Email the instructor with the link to or screenshot of the conversation and an explanation of what was incorrect and how to correct it.

For some tips on safe usage of ChatGPT as a student, see [CS 625 Student Use of ChatGPT and Other Generative AI Tools](chat-gpt.md).

*Note that this does not mean that ChatGPT is acceptable for use in other courses. This policy applies only for this course.*

### Make-up Work

Make-ups for graded activities are possible only with a valid written medical or university excuse. It is the student's responsibility to give the instructor the written excuse and to arrange for any makeup work to be done.  A makeup exam may be different (and possibly more difficult) than the regularly scheduled exam.

### Disability Services

In compliance with PL94-142 and more recent federal legislation affirming the rights of disabled individuals, provisions will be made for students with special needs on an individual basis. The student must have been identified as special needs by the university and an appropriate letter must be provided to the course instructor. Provision will be made based upon written guidelines from the University's [Office of Educational Accessibility](https://www.odu.edu/accessibility). All students are expected to fulfill all course requirements.

Students are encouraged to self-disclose disabilities that have been verified by the Office of Educational Accessibility by providing Accommodation Letters to their instructors early in the semester in order to start receiving accommodations. Accommodations will not be made until the Accommodation Letters are provided to instructors each semester.

## Academic Integrity

Old Dominion University is committed to students' personal and academic success. In order to achieve this vision, students, faculty, and staff work together to create an environment that provides the best opportunity for academic inquiry and learning. All students must be honest and forthright in their academic studies. Your work in this course and classroom behavior must align with the expectations outlined in the "Code of Student Conduct", found at the [Office of Student Accountability & Academic Integrity (OSAAI)](https://www.odu.edu/student-conduct-academic-integrity).

The following behaviors along with classroom disruptions violate this policy, corrupt the educational process, and will not be tolerated.

* Cheating: Using unauthorized assistance, materials, study aids, or other information in any academic exercise.
* Plagiarism: Using someone else's language, ideas, or other original material without acknowledging its source in any academic exercise.
* Fabrication: Inventing, altering or falsifying any data, citation or information in any academic exercise.
* Facilitation: Helping another student commit, or attempt to commit, any Academic Integrity violation, or failure to report suspected Academic Integrity violations to a faculty member.

*In particular, submitting anything that is not your own work without proper attribution (giving credit to the original author) is plagiarism and is considered to be an academic integrity violation. It is not acceptable to copy source code or written work from any other source (including other students, online resources, **ChatGPT**), unless explicitly allowed in the assignment statement. In cases where using resources such as the Internet is allowed, proper attribution must be given.*

Any evidence of an academic integrity violation (cheating) will result in a 0 grade for the assignment/exam, and the incident will be submitted to the Department of Computer Science for further review. Note that academic integrity violations can result in a permanent notation being placed on the student's transcript or even expulsion from the University. Evidence of cheating may include a student being unable to satisfactorily answer questions asked by the instructor about a submitted solution. Cheating includes not only receiving unauthorized assistance, but also giving unauthorized assistance. For class files kept in Unix space, students are expected to use Unix file permission protections (chmod) to keep other students from accessing the files. Failure to adequately protect files may result in a student being held responsible for giving unauthorized assistance, even if not directly aware of it.

Students may still provide legitimate assistance to one another. You are encouraged to form study groups to discuss course topics. Students should avoid discussions of solutions to ongoing assignments and should not, under any circumstances, show or share code solutions for an ongoing assignment.

All students are responsible for knowing the rules. If you are unclear about whether a certain activity is allowed or not, please contact the instructor.

## ODU Counseling Services and Student Outreach & Support

ODU’s [Office of Counseling Services](https://odu.edu/counselingservices) (located upstairs in the Student Recreation and Well-being Center) is a university agency with competent, diverse, and multidisciplinary professional staff. They are committed to supporting the emotional well-being, social development, and academic progress of all students at Old Dominion University. College life can be a wonderful time of self-discovery, but for many, it is also a time when the awareness of mental health conditions increases. OCS services are available to assist with addressing mental health concerns that a student may be experiencing. All services are free to ODU students.

[ODU Student Outreach & Support (SOS)](https://www.odu.edu/dean-students/student-outreach-support) is a service within the Dean of Students' office. SOS provides support to students who experience administrative, academic, or personal roadblocks. SOS works collaboratively with ODU's Care Team, and is here to help students achieve their personal and academic goals. You can contact SOS via <oducares@odu.edu>.
