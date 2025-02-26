[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/BNrQSMzB)
# Relational Data Project: Data Storytelling with a Database

## Assignment Summary 

For this project, students will use SQLite and Python to work with a real-world dataset and tell a data-driven story based on their use of these tools. Specifically, students working in teams will begin with IMDB data in .db format and will query, analyze, and visualize data in order to make an interactive Jupyter Notebook (`.ipynb`) with a static counterpart file (`.html`). Students will be evaluated based on the quality of their technical implementations; their research and writing; and their success building on and effectively synthesizing multiple aspects of the relational data unit.

## Assignment Purpose

This assignment asks students to fulfill the following learning goals:

1. Demonstrate their understanding of relational data, including tables, columns, relationships, and querying strategies
2. Use SQLite/python effectively to facilitate data analysis
3. Synthesize various aspects of the relational data unit in service of a cohesive data story 
4. Effectively communicate what we have learned in this unit with code, visuals, and text, culiminating with a polished `.html` document
5. Use collaboration and version control to generate and document reproducible code

These learning goals are crucial to data analytics and computer science curriculum because relational data is often a core component of modeling complex relationships among data, designing and maintaining sustainable, secure, multi-user data integrations, and working at scale. In our previous unit, we learned that it is __typical in data analysis to convert__ relational data into a tabular format in order to perform common tasks like creating results pages, visualizing data, and conducting statistical analysis or machine learning. However, understanding how to make use of relational data is often core to these workflows. 

## Assignment Files

To get started on this assignment, your team will visit the Github Classroom link and follow the assignment checkout process for team-based assignments. The Github Classroom link will be shared on Canvas. The assignment files will include datasets, metadata files, and a Jupyter Notebook assignment template  (`submission.ipynb`).

__IMDB Data:__ The Internet Movie Database (IMDB) offers a Developer API for real-time access to its core data, which is available for commercial use. It also provides a collection of "Non-Commercial Datasets" that can be accessed for bulk download. These datasets are available online as flat files (.csv format) and, together, they make up the skeletal structure of a series of interconnected tables like we would expect to find in a relational database. I have create a basic version of this database for you to use. 

The IMDB dataset is quite large, which means it exceeds Github's file size limits. Collectively, there are seven data tables requiring about 6.83 GBs of hard disk space to download (Non-Commercial). `The .db files `imdb_full.db` is about 3GB. The data are available for download via a Google Drive folder link (on Canvas) and will be made available via the Ohio Supercomputer Center (OSC), which offers cloud-based resources for students (more details about OSC will be covered in class).

## Assignment Details

The core task of this assignment is to author a data-driven story that uses SQL statements to support both visualizations and descriptive analysis of the underlying data. As with the tabular data assignment, your data-driven story has a set of required technical components that can be implemented in any way that you choose. The data-driven story submission will mix Python code and markdown text to tell a compelling story focused on a topic or question. You will create your data-driven stories using Jupyter Notebook files, and you will submit your work in both `.ipynb` and `.html` formats. Submissions should adhere to the following formatting guidelines: 

| Component  | Description |
|------------|-------------|
| Title  | Brief and informative, gives some idea of your core question or topic area. |
| Introduction | Include core background information and ethical considerations relevant to initial data collection and contemporary use of the data. Articulate your core question or topic area. |
| Database Design | Discuss how the database is structured, and how you have used this information to design your querying strategy. Discuss directly how this approach relates to the topic you decided to explore. |
| Data Exploration | Use a blend of descriptive statistics and data visualizations to explore your core question or topic. Include code blocks. Discuss potential areas for deeper analysis based on the data. |
| Uses of Python - Technical Components | Fill in the submission template table with information about how you satisfied the technical requirements of the assignment. |
| Uses of Python - Reflection | Take a step back and analyze your own use of code. Provide some rationale for choices you've made. Considerations may include performance, human readability, code dependencies, and reproducibility. |
| References   | List all works cited in the data guide. Use proper APA format.  |

__Technical Components:__

Somewhere in your submission, your team is required to:

- use at least three complex SQL queries in your final notebook 
- anywhere within these three queries, use:
	- at least one table join
	- at least one GROUP BY clause
	- at least one WHERE clause
	- at least LIKE, HAVING, LIMIT, or ORDER BY clause
	- at least one SQLite function such as count, max, min, random, round, substr, group_concat, etc.
- display inline at least three data visualizations (using matplotlib, seaborn, etc.)

## Assessment Criteria 

Submissions will be evaluated on technical content; research and writing; and how well the submission comes together as a whole. The following descriptive rubric will be used when grading.

### Technical Content

- attention is paid to the complexities of the source data (missing data, coded values, sample weighting, etc.)
- relational data structures are used critically and support the data story effectively
- SQLite3 and helper functions are used properly; submission uses all required code components correctly
- data visualizations are properly coded, sufficiently polished, and used effectively in support of the data story

### Research and Writing

- sufficient attention has been paid to proofreading
- external sources are used to enhance the submission, and sources are properly cited (APA style)
- the project is well organized, flows logically, and follows the all formatting guidelines
- the submission's use of language is appropriate for a well-informed, less technical reader

### Big Picture 

- all materials are turned in on time and in the right place
- assignment directions are followed, and all required components are included in the submission
- proper documentation and version control methods are used to facilitate collaboration and reproducibility
- the submission provides sufficient details or points to supplementary materials that make the research reproducible (e.g. detailed footnotes, appendices, links to GitHub, etc.)
- submitted materials build on multiple takeaways from the relational data unit and synthesize them effectively 

## Assignment Details

__Accessing assignment files:__ via Github Classroom (linked on Canvas site) and Google Drive / OSC (for the datasets)

__Teams:__ Teams of four, chosen by students.

__Required files:__ Jupyter Notebook (`.ipynb`) data story; `.html` version (using "Download as" feature); and any imported `.py` files.

__How to turn it in__: Upload html on Canvas and push all relevant files (not `.db` or `.csv` files) on Github.
 
__Deadline:__ By the start of class on Monday, November 18, 2024.

## Examples of Data-Driven Storytelling

Data-driven stories are a relatively common genre for online magazines and newspapers but, if you haven't noticed them before, here are a few links to get you started:

- https://ncase.me/polygons/

- https://www.slate.com/blogs/browbeat/2017/08/17/identifying_an_author_s_prose_can_be_as_simple_as_counting_how_much_they.html

- https://projects.fivethirtyeight.com/redistricting-maps/ 

- https://pudding.cool/2023/10/genre/

- https://ourworldindata.org/worlds-energy-problem

Obviously, these examples are quite sophisticated and professional, but they provide a strong sense of what's possible, as well as how much room there is in the genre for experimentation. 

## References 

Non-Commercial Datasets. (Retrieved January 12, 2024). https://developer.imdb.com/non-commercial-datasets/
