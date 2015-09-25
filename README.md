## DAT9 Course Repository

Course materials for [General Assembly's Data Science course](https://generalassemb.ly/education/data-science/washington-dc/) in Washington, DC (9/22/15 - 12/8/15).

**Instructor:** Vadim Bichutskiy

### [Course Project](project/README.md)

### Course Outline (tentative, subject to change)
Tuesday | Thursday 
--- | ---
9/22: Introduction to Data Science | 9/24: Command Line and Version Control
9/29: Data Reading and Cleaning | 10/1: Exploratory Data Analysis
10/6: Data Visualization | 10/8: Machine Learning
10/13: Getting Data<br>**Project Discussion Deadline** | 10/15: K-Nearest Neighbors<br>**Project Question and Dataset Due**
10/20: Basic Model Evaluation | 10/22: Linear Regression
10/27: Logistic Regression | 10/29: Advanced Model Evaluation
11/3: **First Project Presentation** | 11/5: Naive Bayes and Text Data
11/10: Natural Language Processing | 11/12: Kaggle Competition
11/17: Decision Trees<br>**Draft Paper Due** | 11/19: Ensembling
11/24: Advanced scikit-learn/Clustering<br>**Peer Review Due** | 11/26: *Happy Thanksgiving! No Class*
12/1: **Final Project Presentation** | 12/3: **Final Project Presentation**
12/8: Selected Topics, Wrap-up | 


### Python Resources
* [Codecademy's Python course](http://www.codecademy.com/en/tracks/python): Good beginner material, including tons of in-browser exercises.
* [DataQuest](https://dataquest.io/): Similar interface to Codecademy, but focused on teaching Python in the context of data science.
* [Google's Python Class](https://developers.google.com/edu/python/): Slightly more advanced, including hours of useful lecture videos and downloadable exercises (with solutions).
* [A Crash Course in Python for Scientists](http://nbviewer.ipython.org/gist/rpmuller/5920182): Read through the Overview section for a quick introduction to Python.
* [Python for Informatics](http://www.pythonlearn.com/book.php): A very beginner-oriented book, with associated [slides](https://drive.google.com/folderview?id=0B7X1ycQalUnyal9yeUx3VW81VDg&usp=sharing) and [videos](https://www.youtube.com/playlist?list=PLlRFEj9H3Oj4JXIwMwN1_ss1Tk8wZShEJ).
* [Beginner](code/00_python_beginner_workshop.py) and [intermediate](code/00_python_intermediate_workshop.py) workshop code: Useful for review and reference.
* [Python 2.7x Reference Guide](https://github.com/vybstat/python-reference/blob/master/reference.py): Beginner-oriented guide that demonstrates a ton of Python concepts through short, well-commented examples.
* [Python Tutor](http://pythontutor.com/): Allows you to visualize the execution of Python code.

### Submission Forms
* [Feedback form](http://bit.ly/1FrY6A1)
* [Homework and project submissions](http://goo.gl/forms/eqIf0lbH3n)

-----

### Class 1: Introduction to Data Science
* Welcome from General Assembly staff
* Course overview ([slides](slides/01_course_overview.pdf))
* Introduction to data science ([slides](slides/01_intro_to_data_science.pdf))
* Types of data ([slides](slides/01_types_of_data.pdf))
* Data science tools ([slides](slides/DataScienceTools.pdf))
* Wrap up: Slack tour, feedback form

**Resources:**
* For a useful look at the different types of data scientists, read [Analyzing the Analyzers](http://cdn.oreillystatic.com/oreilly/radarreport/0636920029014/Analyzing_the_Analyzers.pdf) (32 pages).
* For some thoughts on what it's like to be a data scientist, read these short posts from [Win-Vector](http://www.win-vector.com/blog/2012/09/on-being-a-data-scientist/) and [Datascope Analytics](http://datascopeanalytics.com/what-we-think/2014/07/31/six-qualities-of-a-great-data-scientist).
* Quora has a [data science topic FAQ](https://www.quora.com/Data-Science) with lots of interesting Q&A.
* Keep up with local data-related events through the Data Community DC [event calendar](http://www.datacommunitydc.org/calendar) or [weekly newsletter](http://www.datacommunitydc.org/newsletter).
* [Data Science vs Statistics](http://bit.ly/1FrZX80)
* [Doing Data Science at Twitter](http://bit.ly/1Fs08QC)
* [15 Books every Data Scientist Should Read](http://bit.ly/1Fs0bvW)
* [50+ Free Data Science Books](http://bit.ly/1Fs0kzr)
* [FREE BOOK:](http://www-bcf.usc.edu/~gareth/ISL/) Introduction to Statistical Learning
* [Building Data Science Teams](http://oreil.ly/1G1s6Oc)
* [R for Everyone:](http://amzn.to/1MHKPpR) Great reference for R
* [Doing Data Science](http://amzn.to/1MHM1Jz)
* [Python for Data Analysis](http://amzn.to/1JomygU)
* [Getting Started with Data Science](http://treycausey.com/getting_started.html)

-----

### Class 2: Command Line and Version Control
* Discuss Course Project
* Git and GitHub ([slides](slides/02_git_github.pdf))
* Command line exercise ([code](code/02_command_line.md))
* Intermediate command line
* Wrap up: Course schedule, office hours

**Homework:**

* Work through GA's friendly [command line tutorial](http://generalassembly.github.io/prework/command-line/#/) using Terminal (Linux/Mac) or Git Bash (Windows), and then browse through this [command line reference](code/02_command_line.md).
* Watch videos 1 through 8 (21 minutes) of [Introduction to Git and GitHub](https://www.youtube.com/playlist?list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD).

Create a Markdown document that includes your answers to questions 1-3 below and the code you used to arrive at those answers. Add this file to a GitHub repo that you'll use for all of your coursework, and submit a link to your repo using the homework submission form:

1. Using `chipotle.tsv` in the `data` subdirectory:
    * Look at the head and the tail, and think for a minute about how the data is structured. What do you think each column means? What do you think each row means? Tell me! (If you're unsure, look at more of the file contents.)
    * How many orders do there appear to be?
    * How many lines are in the file?
    * Which burrito is more popular, steak or chicken?
    * Do chicken burritos more often have black beans or pinto beans?
2. Count the number of occurrences of the word 'dictionary' (regardless of case) across all files in the DAT9 repo.
3. **Optional:** Use the the command line to discover something "interesting" about the Chipotle data. The [advanced commands](code/02_command_line.md#Advanced-commands) may be helpful to you!

* Install the [Anaconda distribution](http://continuum.io/downloads) of Python 2.7x.
    * If you choose not to use Anaconda, here is a list of the [Python packages](other/python_packages.md) you will need to install during the course.
* Skim through the [Python reference](http://bit.ly/1QBuv7P).

**Git and Markdown Resources:**
* [Pro Git](http://git-scm.com/book/en/v2) is an excellent book for learning Git. Read the first two chapters to gain a deeper understanding of version control and basic commands.
* If you want to practice a lot of Git (and learn many more commands), [Git Immersion](http://gitimmersion.com/) looks promising.
* If you want to understand how to contribute on GitHub, you first have to understand [forks and pull requests](http://www.dataschool.io/simple-guide-to-forks-in-github-and-git/).
* [GitRef](http://gitref.org/) is my favorite reference guide for Git commands, and [Git quick reference for beginners](http://www.dataschool.io/git-quick-reference-for-beginners/) is a shorter guide with commands grouped by workflow.
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) provides a thorough set of Markdown examples with concise explanations. GitHub's [Mastering Markdown](https://guides.github.com/features/mastering-markdown/) is a simpler and more attractive guide, but is less comprehensive.
* [Introducing GitHub](http://amzn.to/1KCjWg6) is a nice intro to GitHub that reads quickly
* [Version Control with Git](http://amzn.to/1gSkBm2)

**Command Line Resources:**
* If you want to go much deeper into the command line, [Data Science at the Command Line](http://amzn.to/1gSjcvV) is a great book. The [companion website](http://datascienceatthecommandline.com/) provides installation instructions for a "data science toolbox" (a virtual machine with many more command line tools), as well as a long reference guide to popular command line tools.

-----
