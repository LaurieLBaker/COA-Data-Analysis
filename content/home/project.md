+++
# Homepage
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 70  # Order that this section will appear in.

title = "Project"
subtitle = "Showcase your inner data scientist"
+++

## TL;DR

Pick a dataset, any dataset...

...and do something with it. That is your final project in a nutshell. More details below.

The final project for this class will consist of a visualization of a dataset of your own choosing. The dataset may already exist, or you may collect your own data using a survey or by conducting an experiment. You can choose the data based on your interests or based on work in other courses or research projects. The goal of this project is for you to demonstrate proficiency in the techniques we have covered in this class (and beyond, if you like) and apply them to a novel dataset in a meaningful way.

The goal is not to do an exhaustive data analysis i.e., do not create every visualization you have learned for every variable, but rather let me know that you are proficient at asking meaningful questions and exploring them with data visualizations, that you are proficient in using R, and that you are proficient at interpreting and presenting the results. 

The project is very open ended. You should create some kind of compelling visualizations of this data in R. There is no limit on what tools or packages you may use, but sticking to packages we learned in class (`tidyverse`) is required. You do not need to visualize all of the data at once. A few high quality visualizations will receive a much higher grade than a large number of poor quality visualizations. At least one visualization should be made using R but you are also encouraged to create your own visualizations using other mediums/crafts if you choose. Also pay attention to your presentation. Neatness, coherency, and clarity will count. All analyses must be done in RStudio, using R.

Here is an example of a past [project write up](https://dcs-210.github.io/project-lizakemuntopatrick/) and [presentation](https://dcs-210.github.io/project-lizakemuntopatrick/presentation/presentation.html#1) on **Lessons to be Learned from Super Bowl Advertisements**. 

### Data

In order for you to have the greatest chance of success with this project it is important that you choose a manageable dataset. This means that the data should be readily accessible and large enough that multiple relationships can be explored. As such, your dataset must have at least 50 observations and between 10 to 20 variables (exceptions can be made but you must speak with me first). The variables in the data should include categorical variables, discrete numerical variables, and continuous numerical variables.

If you are using a dataset that comes in a format that we haven't encountered in class, make sure that you are able to load it into R as this can be tricky depending on the source. If you are having trouble ask for help before it is too late.

**Note on reusing datasets from class:** Do not reuse datasets used in examples, homework assignments, or labs in the class.

Below are a list of data repositories that might be of interest to browse. You're not limited to these resources, and in fact you're encouraged to venture beyond them. But you might find something interesting there:

- [TidyTuesday](https://github.com/rfordatascience/tidytuesday)
- [NHS Scotland Open Data](https://www.opendata.nhs.scot/)
- [Edinburgh Open Data](https://edinburghopendata.info/)
- [Open access to Scotland's official statistics](https://statistics.gov.scot/home)
- [Bikeshare data portal](https://www.bikeshare.com/data/)
- [UK Gov Data](https://data.gov.uk/)
- [Kaggle datasets](https://www.kaggle.com/datasets)
- [OpenIntro datasets](http://openintrostat.github.io/openintro/)
- [Awesome public datasets](https://github.com/awesomedata/awesome-public-datasets)
- [Youth Risk Behavior Surveillance System (YRBSS)](https://chronicdata.cdc.gov/Youth-Risk-Behaviors/DASH-Youth-Risk-Behavior-Surveillance-System-YRBSS/q6p7-56au)
- [PRISM Data Archive Project](https://www.icpsr.umich.edu/icpsrweb/content/ICPSR/fenway.html)
- [Harvard Dataverse](https://dataverse.harvard.edu/)
- [National Archive of Criminal Justice Data](https://www.icpsr.umich.edu/web/pages/NACJD/index.html)
- [TransPop](https://www.icpsr.umich.edu/web/ICPSR/studies/37938) first national probability sample of transgender individuals in the United States.
- [Data is Plural](https://www.data-is-plural.com/archive/)
- [American Community Survey](https://data.census.gov/cedsci/) some Maine data here.
- [IPUMS USA](https://usa.ipums.org/usa/) census microdata
- [The Lawrence Papers](https://scarab.bates.edu/lawrance/) from Bates and [metadata](https://bates-archives.libraryhost.com/repositories/2/resources/185)
- [Health-related datasets](https://libguides.bates.edu/health-economics/resources) compiled by Bates library
- If you know of others, let me know, and we'll add here...

### Deliverables

1. Team contract - due Saturday, October 15, 23:59 EST
1. Proposal     - due Saturday, October 22, 23:59 EST
1. Presentation outline (Optional) - due Saturday, October 29, 23:59 EST
1. Write-up     - due Friday, November 11, 23:59 EST
1. Presentation - due Tuesday or Wednesday, November 15 or 16 (In class)

#### Team Contract

One of the main goals of this course is that you build and develop community leadership skills as a collaborator that shares strengths, builds weaknesses, and contributes to a broader shared understanding. These skills will serve you in this course and beyond in your careers. A crucial part of building strong collaborations is good communication.

Each team will draft a group contract. A group contract is a document to help you formalize the expectations you have for your group members and what they can expect of you. It will help you think about what you need from each other to work effectively as a team! You will create and agree on this contract as a team and refer to it during the project.

At a minimum, your group contract must address these questions:

##### Goals:

- What are our team goals for this project?
- What do we want to accomplish?
- What skills do we want to develop or refine?

##### Expectations:

- What do we expect of one another regarding attendance at meetings, participation, frequency of communication, quality of work, etc.?

##### Policies & Procedures:

- What rules can we agree on to help us meet our goals and expectations?

##### Consequences:

- How will we address non-performance regarding these goals, expectations, policies and procedures?

Each member should "sign" (you can just type out your name) at the bottom of the submission.

Credit for Group Contract: Tiffany Timbers, University of British Columbia

#### Proposal

You will write your proposal in the proposal.Rmd file in your Github project.

- Section 1 - Introduction: The introduction should introduce your general 
research question and your data (where it came from, how it was collected, 
what are the cases, what are the variables, etc.).

- Section 2 - Data: Place your data in the `/data` folder, and add dimensions 
and codebook to the README in that folder. Then print out the output of 
`glimpse()` or `skim()` of your data frame.

- Section 3 - Data analysis plan:
  - The outcome (response, Y) and predictor (explanatory, X) variables you will use to explore your question.
  - The comparison groups you will use, if applicable.
  - Very preliminary exploratory data analysis, including some summary statistics 
and visualizations, along with some explanation on how they help you learn more 
about your data. (You can add to these later as you work on your project.)
  - The data visualization(s) that you believe will be useful in exploring your 
question(s). (You can update these later as you work on your project.)


Each section should be no more than 1 page (excluding figures). You can check a 
print preview to confirm length. 

#### Presentation

10 minutes maximum, and each team member should say something substantial.

Prepare a slide deck using either Google Slides or the template in your repo. This template uses a package called `xaringan`, and allows you to make presentation slides using R Markdown syntax. There isn't a limit to how many slides you can use, just a time limit (10 minutes total). A rough guide to follow is one slide is equal to one minute. Each team member should get a chance to speak during the presentation. Your presentation should not just be an account of everything you tried ("then we did this, then we did this, etc."), instead it should convey what choices you made, and why, and what you found.

Before you finalize your presentation, make sure your chunks are turned off with `echo = FALSE`. 

Presentation schedule: Presentations will take place during the Tuesday and Wednesday of the last week of the course. During the class you will watch presentations from the other teams and provide feedback in the form of peer evaluations. The presentation line-up will be generated randomly.

#### Write-up

Along with your presentation slides, we want you to provide a brief summary of your project in the README of your repository.

This write-up, which you can also think of as an summary of your project, should provide information on the dataset you're using, your research question(s), your approach (how you decided to visualize the data), and your findings. 

#### Repo organization

The following folders and files in your project repository:

* `presentation.Rmd` + `presentation.html`: Your presentation slides
* `README.md`: Your write-up
* `/data/*`: Your dataset in csv or RDS format, in the `/data` folder.
* `/proposal`: Your proposal from earlier in the semester
* `/contract`: Your group contract from earlier in the semester

Style and format does count for this assignment, so please take the time to make sure everything looks good and your data and code are properly formatted including labelling code chunks. Pay attention to images and plots included in the presentation and make sure to include appropriate alternative text.

## Tips

- You're working in the same repo as your teammates now, so merge conflicts will happen, issues will arise, and that's fine! Pull, commit and push often, and ask questions when stuck.
- Review the marking guidelines below and ask questions if any of the expectations are unclear.
- Make sure each team member is contributing, both in terms of quality and quantity of contribution (we will be reviewing commits from different team members).
- Set aside time to work together and apart (physically).
- When you're done, review the documents on GitHub to make sure you're happy with the final state of your work. Then go get some rest!
- Code: In your presentation your code should be hidden (`echo = FALSE`) so that your document is neat and easy to read. However your document should include all your code such that if I re-knit your R Markdown file I should be able to obtain the results you presented. **Exception:** If you want to highlight something specific about a piece of code, you're welcomed to show that portion. 
- Teamwork: You are to complete the assignment as a team. All team members are expected to contribute equally to the completion of this assignment and team evaluations will be given at its completion - anyone judged to not have sufficient contributed to the final product will have their grade penalized. While different teams members may have different backgrounds and abilities, it is the responsibility of every team member to understand how and why all code and approaches in the assignment works.

## Marking

Total                          | 100 pts
-------------------------------|--------
Proposal                       | 10 pts
Presentation                   | 50 pts
Write-up                       | 15 pts
Reproducibility and organization | 10 pts
Team peer evaluation           | 10 pts
Classmates' evaluation         | 5 pts

### Criteria

- **Content** - What is the quality of research and/or policy question and relevancy of data to those questions?
- **Correctness** - Are the data visualizations chosen an effective means of exploring the questions?
- **Writing and Presentation** - What is the quality of the statistical presentation, writing, and explanations?
- **Creativity and Critical Thought** - Is the project carefully thought out? Are the limitations carefully considered? Does it appear that time and effort went into the planning and implementation of the project?

### Team peer evaluation

You will be asked to fill out a survey where you rate the contribution and teamwork of each team member out of 10 points. You will additionally report a contribution percentage for each team member. Filling out the survey is a prerequisite for getting credit on the team member evaluation. If you are suggesting that an individual did less than 20% of the work, please provide some explanation. If any individual gets an average peer score indicating that they did less than 10% of the work, this person will receive half the grade of the rest of the group. The contribution and teamwork scores for each team member will be averaged across the team to give the peer evaluation score.