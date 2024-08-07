# CS 625 Topic Objectives

## Chapter 1 - Introduction

Summary: This module introduces data visualization and sets up the "what-why-how" framework that will be used to discuss visualization throughout the course. Several tools, including standalone applications and visualization libraries, will be introduced.

* Define visualization.
* Explain the importance of humans in the visualization process.
* Explain why human vision is particularly well-suited for information transfer.
* Give an example of a visualization idiom.
* Explain why it is best to consider multiple alternatives for vis before selecting a solution.
* Explain at a high-level the "what-why-how" framework for analyzing visualization use.
* Differentiate between Seaborn, Vega-Lite, D3, and Tableau and describe the type of tasks for which each tool might be most appropriate.

## Chapter 2 - Data

Summary: This module introduces data attribute types. Identify attribute types in a dataset will be key to designing effective visualizations. This module will also introduce data cleaning and the OpenRefine data cleaning tool, in particular.

* Distinguish among the four basic dataset types.
* Distinguish among the five core data types.
* Distinguish between categorical and ordered attributes.
* Distinguish between ordinal and quantitative attributes.
* Explain why understanding the dataset and data types and semantics matter for designing effective visualizations.
* Distinguish between scientific vis and information vis in terms of how spatial data is used.
* Explain the difference between a flat table and a multidimensional table.
* Explain some of the complexities of dealing with temporal data.
* Identify two tools for cleaning data.

## Chapter 5 - Marks and Channels

Summary: This module introduces the concepts of marks that are mapped to data items and visualization channels that are mapped to attributes. The module also introduces several principles of channel effectiveness and presents the channel effectiveness ranking that will be used throughout the course. Beginning tutorials using Seaborn and Vega-Lite will be introduced.

* Explain how marks and channels are related.
* Distinguish between the identity channel type and the magnitude channel type and indicate which channels belong to each type.
* Distinguish between the principles of expressiveness and effectiveness in visual encoding.
* List the channels for ordered attributes in order from most effective to least effective.
* List the channels for categorical attributes in order from most effective to least effective.
* Describe the effects of accuracy, discriminability, separability, popout (preattentive processing), and grouping and give one example that illustrates each.
* Explain the implication of Stevens' Law for visualizations.
* Explain the implication of Weber's Law for visualizations.

## Chapter 7 - Arrange Tables

Summary: This module highlights several basic visualization idioms, showing how they are constructed using the principles of attribute types, marks, and channels. The module will also provide examples of how to analyze a dataset and choose an appropriate visualization idiom based on the attribute types.

* Explain why the arrange design choice is the most crucial visual encoding choice.
* Explain how the concepts of express, separate, order, and align all relate to arranging tabular data.
* For each idiom example in the text (from scatterplot to normalized stacked bar chart), identify the "what: data" properties of the idiom.
* For each idiom example in the text, identify the "how: encode" properties of the idiom.
* For each idiom example in the text, identify the "why: task" properties of the idiom.
* For each idiom example in the text, identify the "scale" properties of the idiom.
* Differentiate between line charts and bar charts and explain when each is appropriate
* Explain some of the disadvantages of pie charts.
* Explain how a radial layout maps to a rectilinear layout.
* Given a particular dataset and task, suggest an idiom and explain why it might be appropriate
* Identify a visualization where an inappropriate arrange design choice was made and explain why the choice was inappropriate.

## Tour through the Visualization Zoo

Summary: This module is a continuation of the previous module and introduces more complex vis idioms. Creating various vis idioms in Seaborn and Vega-Lite will be a particular focus.

* Explain why the arrange design choice is the most crucial visual encoding choice.
* Explain how the concepts of express, separate, order, and align all relate to arranging tabular data.
* For each idiom example in the text (from scatterplot to normalized stacked bar chart), identify the "what: data" properties of the idiom.
* For each idiom example in the text, identify the "how: encode" properties of the idiom.
* For each idiom example in the text, identify the "why: task" properties of the idiom.
* For each idiom example in the text, identify the "scale" properties of the idiom.
* Differentiate between line charts and bar charts and explain when each is appropriate
* Explain some of the disadvantages of pie charts.
* Explain how a radial layout maps to a rectilinear layout.
* Given a particular dataset and task, suggest an idiom and explain why it might be appropriate
* Identify a visualization where an inappropriate arrange design choice was made and explain why the choice was inappropriate.

## Chapter 10 - Map Color and Other Channels

Summary: This module emphasizes the importance of color in visualizations and introduces a few additional channels. 

* Describe the components of color.
* Describe the three main types of colormaps.
* Explain the importance choosing an appropriate colormap.
* Given a set of data and a task, determine an appropriate colormap.
* Identify an inappropriate use of a colormap and suggest a more appropriate one.
* Explain why rainbow colormaps should only be used with great care.
* For the visual channels other than color, identify which are magnitude and which are identity channels.

## Chapter 13 - Reduce Items and Attributes

Summary: This module introduces techniques for reducing data items and attributes, through filtering and aggregation. Idioms showing data item aggregations such as histograms and boxplots will be introduced and examples of their use in Seaborn and Vega-Lite will be provided.

* Explain the need to reduce data, both in terms of number of items and number of attributes.
* Explain the difference between filtering and aggregation and the purposes of each.
* Identify instances of scented widgets, as opposed to standard filtering widgets.
* Contrast histograms with bar charts.
* Explain the importance of binwidth in a histogram.
* Describe the components of a boxplot.

## Exploratory Data Analysis (EDA)

Summary: This module introduces the process of exploratory data analysis.

* List the three steps in the iterative cycle of EDA.
* Explain the concept of covariation.
* Name some questions to ask about patterns found in data.
* Given a dataset, generate questions aimed at examining correlation and understanding underlying patterns in the data.

## Chapter 12 - Multiple Views

Summary: This module introduces the concept of using multiple views of the same dataset to gain insight into the data. Examples on how to create faceted visualizations in Vega-Lite will be presented.

* Explain the importance and usefulness of faceting data across multiple views.
* Contrast the two major approaches to faceting information.
* Describe the four major design choices for juxtaposed views.
* Explain the concept of linked highlighting.
* Describe the three alternatives for sharing data between two juxtaposed views.
* Contrast the use of small multiples with a grouped bar chart.
* Given a multiform visualization, identify the ways in which the data was split into multiple views and the design choices that were made.


## Chapter 8 - Maps (8.1-8.3), Chapter 6 - Rules of Thumb, and Chart Design

Summary: This module introduces the use of geographical data in visualizations, focusing on choropleth maps. The module also covers several rules of thumb to keep in mind when designing visualizations. Guidelines and recommendations for effective chart design will be discussed.

* Describe how the arrange design choice is different with spatial data as opposed to tabular data.
* Describe a choropleth map.
* Explain potential difficulties with the use of 3D visualization.
* Identify situations in which the use of 3D visualization would be appropriate.
* Explain why "eyes beat memory".
* Explain what happens when people experience cognitive load.
* Define change blindness.
* Explain the tradeoff between resolution and immersion.
* Explain the Shneiderman mantra "overview first, zoom and filter, details on demand".
* Explain the alternate concept of "search, show context, expand on demand" and identify in what situations it may be more appropriate than the Shneiderman mantra.
* Explain the importance of the design slogan "get it right in black and white".

## Storytelling Vis

Summary: This module introduces the concept of using visualization for storytelling, especially in the context of dadta journalism. Methods for adding explanatory annotations to charts in Seaborn and Vega-Lite will be discussed.

* List the seven genres of narrative visualization.
* Describe the Martini glass structure of narrative visualization.
* Describe a stepper in an interactive visualization.
* Describe how narrative visualization and presentation visualization differ from exploratory/analysis visualization, especially in terms of tools and approaches.

## Visualization Literacy

Summary: This module introduces misleading visualizations and provides techniques for how to spot such misinformation.

* Explain the concept of visual literacy.
* List 6 tips for spotting misinformation.
* Demonstrate the use of Fermi estimation.
* Explain confirmation bias.
* List 10 suggestions for spotting misinformation online.
* Given a misleading visualization, identify the misleading elements and suggest how the visualization could be improved.
