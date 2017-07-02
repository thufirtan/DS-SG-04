# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Final Project, Part 2: Project Design Writeup and Exploratory Data Analysis

### PROMPT

Project outlines are a valuable resource when working with data projects, as they help keep your project organized.  A well constructed outline can clarify your goals and serve as a checklist when conducting research and analysis.

Complete a problem statement and research design outline for one of the three lightning talks you designed during pt. 1. This will serve as the starting point for your analysis. Make sure to include a specific aim and hypthesis, well-defined risks and assumptions, and clearly articulated goals and success metrics.

Exploratory data analysis is a crucial and informative step in the data process. It helps confirm or deny your initial hypotheses and helps visualize the relationships among your data. Your exploratory analysis also informs the kinds of data transformations that you'll need to optimize for machine learning models.

Explore and visualize your initial analysis in order to effectively tell your data's story. Create an iPython notebook that explores your data mathematically, using a python visualization package.

**Goal:** Create an outline of your research design approach, including hypothesis, assumptions, goals, and success metrics. Create an exploratory analysis notebook with stat analysis and visualization.
---

### DELIVERABLES

- **Requirements:**
  - Well-articulated problem statement with "specific aim" and hypothesis, based on your lightning talk
  - An outline of any potential methods and models
  - Detailed explanation of data available
  - Describe any outstanding questions, assumptions, risks, caveats
  - Define your goals and criteria, explain what success looks like
  - Demonstrate domain knowledge, including features or benchmarks from similar projects
  - A well organized iPython notebook with code and output
  - At least one visual for each independent variable (and any relationships) using a python visualization tool
  - Provide insight about data set and its impact on your hypothesis

- **Bonus:**
    - Consider alternative hypotheses: if your project is a regression problem, is it possible to rewrite it as a classification problem?
    - "Convert" your goal metric from a statistical one (like Mean Squared Error) and tie it to something non-data people can understand, like a cost/benefit analysis, etc.
    - Surface and share your analysis online. Jupyter makes this very simple and the setup should not take long.
    - Try experimenting with other visualization languages; python/pandas-highcharts, shiny/r, or for a real challenge, d3 on its own. Interactive data analysis opens the doors for others to easily interpret your work and explore the data themselves!

---

### TIMELINE

| Deadline | Deliverable| Description |
|:-:|---|---|
| 22 July 2017 | Part 2 - Experiment Writeup and EDA  |  Research Design Problem Statement & Outline, Exploratory Analysis   |
| 29 July 2017 | Part 3 - Notebook Draft  |  iPython Notebook & Model Draft  |
| 5 August 2017 | Part 4 - Presentation  | Present Your Final Report   |

---

### EVALUATION

Your project will be assessed using the following standards:

#### Rubric: [Click here for the complete rubric](./final-project-2-rubric.md).

Requirements for these standards will be assessed using the scale below:

    Score | Expectations
    ----- | ------------
    **0** | _Incomplete._
    **1** | _Does not meet expectations._
    **2** | _Meets expectations, good job!_
    **3** | _Exceeds expectations, you wonderful creature, you!_

While your total score is a helpful gauge of whether you've met overall project goals, __specific scores are more important__ since they'll show you where to focus your efforts in the future!

---

### RESOURCES

#### Suggestions for Getting Started

- Refer to this [template](./project-design-template.md) for a rough guide on the structure of the first portion (i.e. before EDA).
- The more time you spend researching, the less time you'll likely spend writing; this is a positive sign!
- While researching, keep track of all of your resources. Make sure they're trustworthy.
- If you've seen similar work online, see if you can find the code that implemented the data munging. It might come in handy!
- If your project requires using an API, make sure you can get access to it. Not everyone gives away API keys immediately, and you don't want to be caught with no data with one week left to work!
- Keep the project simple! The "cool" part of the analysis will come; just looking at simple relationships between variables can be incredibly insightful.
- Consider building some helper functions that help you quickly visualize and interpret data.
   - Exploratory data analysis should be formulaic; the code should not be holding you back. There are plenty of "starter code" examples from class materials.
- **DRY:** Don't Repeat Yourself! If you see yourself copy and pasting code a lot, turn it into a function, and use the function instead!

#### Specific Tips

- Provide a sense of depth and scale to the project, which can be used to guide where the majority of your time should be spent working on the project.
- Show a clear connection between the datasets and the problem presented. The project should avoid working with independent variables (or features) that would not ordinarily be available in order to predict your target.
