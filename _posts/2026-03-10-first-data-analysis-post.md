---
title: "Python Basics for Data Analysis: My First Notebooks"
date: 2026-03-10
categories: [data-analysis]
---

This article explores setting up a simple introductory data analysis learning environment and how to use it. 

<h2>Introduction</h2>

The field of data analysis has a wide variety of tools and learning platforms to choose from. While some of these tools have specific features in common, mant of them also have unique features or characteristics. For a learner new to data analysis, it can be overwhelming to pick a starting point and choose which tools to learn first.

The goal of this article is to share the plan I created for setting up my data analysis learning environments and becomming familiar with basic tools so that others can follow along as well. However, it is important to note that individual discretion must be applied as not all tools and/or platforms may be suitable for an individual's specific project or learning goals.

<h2>Tools Used</h2>

- [Python](https://www.python.org/downloads/)

- [Jupyter](https://jupyter.org/install)

- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

- [Power BI Desktop](https://www.microsoft.com/en-us/download/details.aspx?id=58494)

- pandas

<h2>Process</h2>

1. Install Python and Jupyter.

2. Install Git and set up [GitHub repo](https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories) for storing projects.

3. Install Power BI Desktop.

4. Test first Python script: `hello_world.py`.

    4.1. It may be useful for first-time learners to follow a [tutorial](https://www.w3schools.com/python/python_getstarted.asp) for writing and running python scripts.

5. Explore pandas basics: read CSV, head(), info()

    5.1. Create a [Jupyter notebook](https://www.dataquest.io/blog/jupyter-notebook-tutorial/) first, then use the notebook to test pandas features.

6. Load sample dataset into Power BI.

    6.1. Power BI comes with some sample datasets such as the one called `financials`, which can be loaded by following the [create a report](https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-excel-stunning-report) tutorial.

<h2>Challenges & Lessons Learned</h2>

- Run first `hello_world.py` Python script:

    - To run the script, in the terminal, type: 

        ```bash
        python3 hello_world.py
        ```

    - Note: on some systems it may be necessary to instead type: 

        ```bash
        python hello_world.py
        ```

- Run first Jupyter notebook:

    1. Start Jupyter in project folder:

        ```bash
        jupyter notebook
        ```

    2. Open notebook in browser.

    3. Run the cells sequentially to see the outputs.

- Load sample dataset into Power BI:

    1. Prepare imported data: format data types, headings, filter data, etc.

    2. Write expressions if necessary. 

    3. Enter table view mode to confirm data was imported successfully. The name of the dataset will appear in the pane on the right side of the screen.

<h2>Screenshots / Diagrams</h2>

Successfully loading the sample dataset `financials` into Power BI will look similar to the image below:

![Loaded Data](/images/data_loaded.PNG)

<h2>Next Steps</h2>

- Practice more Python basics (variables, loops, functions).

- Practice loading and cleaning datasets from Kaggle in Power BI and Jupyter notebooks.

- Learn how to handle missing values in datasets with pandas.

- Learn how to create simple visuals such as bar charts in Power BI.

- Learn how to use matplotlib and Seaborn.