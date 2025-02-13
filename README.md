# Portfolio

<h1>
 Welcome!
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
</h1>

### :woman_technologist: About Me:

I'm a Data Scientist with the [U.S. Digital Corps](https://digitalcorps.gsa.gov/) with an M.S. in Data Science and Public Policy from Georgetown University. I'm also a public policy professional with experience in program management and communications with the federal government. I'm currently open to opportunities where data science and public interest intersect. See below for examples of my work!

*Jump to a section:*
- [Professional Research](#professional-research-python)
- [Academic Research](#academic-research-python-and-r)
- [Data Visualization Projects](#data-visualization-projects)
- [Class Assignments](#class-assignments-python)
- [How to Reach Me](#how-to-reach-me)

---

### Professional Research (Python)

:file_folder: **[Massive Data Institute](https://mdi.georgetown.edu/)**

*Summary:* I am working with [Dr. Rebecca Johnson](https://gufaculty360.georgetown.edu/s/contact/0031Q00002YIzT3QAL/rebecca-johnson) to develop a first-of-its-kind database of school board video transcripts for public policy analysis of education inequalities at the local level. Responsibilities included cleaning and compiling 10 years of directory and demographic data from the National Center for Education Statistics and testing regex and Large Language Model (LLM) methods to clean and extract public comments from transcripts. Also with MDI, I collaboratively developed an interactive tool in Python to automate the data collection process and replicate the the excel-based funding allocation formula for the Deparment of Health and Human Services – Low Income Home Energy Assistance Program (LIHEAP). I helped develop and refine a detailed user guide for the tool and trained HHS staff (not versed in Python) on tool usage. See the poster presentations for these projects below: 
- [DistrictView: Exploring Methods for Isolating Public Comments in School Board Meetings](https://drive.google.com/file/d/1BWgDO9QzlGxqzhVlXfyL6sRPzkmoTbKw/view?usp=sharing), Spring 2024
- [DistrictView: Building a First-of-Its-Kind Database of U.S. School Board Meeting Transcripts](https://mdi.georgetown.edu/posters/corrina-calanoc-24-and-maggie-sullivan-24-mdi-scholars-fall-2023-research-showcase-poster/), Fall 2023
- [Supporting Efficient Federal Program Operations: Automating the LIHEAP Funding Formula](https://mdi.georgetown.edu/posters/alia-abdelkader-23-caroline-adams-23-and-maggie-sullivan-24-mdi-scholars-spring-2023-research-showcase-poster/), Spring 2023

*Techniques:* Webscraping (`Selenium`), Data Wrangling, Pipeline Production, LLM Testing

:file_folder: **[Beeck Center for Social Impact + Innovation](https://beeckcenter.georgetown.edu/)** <br>

*Summary:* Each year, the “State of the State" speech is a governor’s prime opportunity to outline their top priorities to the public. To understand governor priorities in 2023, I analyzed all 50 State of the State addresses (or the equivalent annual budget address or inaugural speech) and dove deeper into governor’s priorities by analyzing a year’s worth of press releases for the 13 states that have participated in the Data Labs program with the Beeck Center. I found that governors across the country are focused most on issues related to housing and homelessness, energy policy, and taxes. See the public GitHub repository for this project [here](https://github.com/beeckcenter/state_of_the_states_2023). My blog post with accompanying infographics will be published in May on the Beeck Center website. 

*Techniques:* Webscraping (`BeautifulSoup` and `Selenium`), TF-IDF, Principal Component Analysis (PCA), Data Visualization

### Academic Research (Python and R):

📘 **Data Science III: Just Jargon or Policy Priorities? Text Analysis of Secretary of State Remarks for the Biden and Trump Administrations (Python)**

*Summary:* Public affairs materials point to both policy priorities and how we talk about those policy priorities. This is particularly relevant when comparing the priorities of presidential administrations from different political parties. I scraped 1,973 public remarks from the Office of the Secretary of State websites for the current U.S. Secretary of State Antony Blinken (Biden Administration) and his predecessor, Secretary Michael Pompeo (Trump Administration). I then conducted both exploratory and predictive analysis on these documents to understand how government public affairs materials do or do not reveal key facts about U.S. foreign policy, particularly for changes between administrations of different political parties. I found that these public remarks revealed both diplomatic "business as usual" reveal both and key policy priorities under each administration. Read the final report [here](https://github.com/Mag-Sul/Portfolio/blob/main/class_research/Just%20Jargon%20or%20Policy%20Priorities/final_paper_ds3_mes440.pdf). 

*Techniques:* Webscraping (`BeautifulSoup` and `Requests`), TF-IDF, Principal Component Analysis (PCA), Naive Bayes, K-Nearest Neighbors (KNN), Decision Trees/Random Forest

- [01_scrape_blinken.ipynb](https://github.com/Mag-Sul/Portfolio/blob/main/class_research/Just%20Jargon%20or%20Policy%20Priorities/01_scrape_blinken.ipynb)
- [02_scrape_pompeo.ipynb](https://github.com/Mag-Sul/Portfolio/blob/main/class_research/Just%20Jargon%20or%20Policy%20Priorities/02_scrape_pompeo.ipynb)
- [03_merge_datasets.ipynb](https://github.com/Mag-Sul/Portfolio/blob/main/class_research/Just%20Jargon%20or%20Policy%20Priorities/03_merge_datasets.ipynb)
- [04_text_vectorization_sos.ipynb](https://github.com/Mag-Sul/Portfolio/blob/main/class_research/Just%20Jargon%20or%20Policy%20Priorities/04_text_vectorization_sos.ipynb)
- [05_models_sos.ipynb](https://github.com/Mag-Sul/Portfolio/blob/main/class_research/Just%20Jargon%20or%20Policy%20Priorities/05_models_sos.ipynb)
  
📘 **Data Science II: Real Life Leslie Knopes: Factors Contributing to the Proportion of Women Candidates for Local Office in the United States (Python)**

*Summary:* Much data and research exists about factors influencing the number of women in national politics globally but there is little understanding of these same elements at the local level. In my project, I examine which social, economic, and political factors are most relevant to predicting higher proportions of women candidates for local office in the United States. I employ a gender guessing package on candidate-level precinct returns from the 2018 elections and combine the resulting data with county-level factors related to demography, economics, election history, and reproductive healthcare. My resulting dataset provides one of the most conclusively available datasets on women running for local office in the U.S. Read the final report [here](https://github.com/Mag-Sul/Portfolio/blob/main/class_research/Real%20Life%20Leslie%20Knopes/Real%20Life%20Leslie%20Knopes_%20Factors%20Contributing%20to%20the%20Proportion%20of%20Women%20Candidates%20for%20Local%20Office%20in%20the%20United%20States%20-%20Sullivan.pdf). 

*Techniques:* Least Absolute Shrinkage and Selection Operator (LASSO) regression, random forests, handling unbalanced datasets

- [01_data_cleaning_local_data.ipynb](https://github.com/Mag-Sul/Portfolio/blob/main/class_research/Real%20Life%20Leslie%20Knopes/01_data_cleaning_local_data.ipynb)
- [02_data_cleaning_demographic.ipynb](https://github.com/Mag-Sul/Portfolio/blob/main/class_research/Real%20Life%20Leslie%20Knopes/02_data_cleaning_demographic.ipynb)
- [03_data_cleaning_repro.ipynb](https://github.com/Mag-Sul/Portfolio/blob/main/class_research/Real%20Life%20Leslie%20Knopes/03_data_cleaning_repro.ipynb)
- [04_merging.ipynb](https://github.com/Mag-Sul/Portfolio/blob/main/class_research/Real%20Life%20Leslie%20Knopes/04_merging.ipynb)
- [05_analysis.ipynb](https://github.com/Mag-Sul/Portfolio/blob/main/class_research/Real%20Life%20Leslie%20Knopes/05_analysis.ipynb)

📘 **Stats I: School-Aged Violence and Potential Impact on Proportion of Women in Public Office (R)**

*Summary:* Initially we planned to examine the relationship between online violence against women and women's political participation. However, this is an emerging data area and many data gaps remain. Instead, we pivoted to examine violence in relation to another proposed element contributing to the low numbers of women in elected office: the influence of childhood experiences. For example, based on survey data from 1,600 children ages 6 to 12, researchers Bos, et al concluded that girls report less interest in running for political office than their boy peers (Bos, Angela L., et al). Another study by Fox and Lawless found that even factors such as participation in school sports influences whether or not a girl says they want to run for office someday (Fox and Lawless, "Girls Just Wanna Not Run"). Our hypothesis is that the levels of violence against girls in high school will have a negative correlation on the levels of women in politics at both the state and federal level. In our study, we analyzed 2015 state-level data on the percent of high school students experiencing harassment or bullying and dating violence, and state statutes on violence and employment, domestic violence, sexual violence, stalking, and gun ownership as well as 2015 data on women in congress and state legislatures. See the full presentation of results [here](https://github.com/Mag-Sul/Portfolio/blob/main/class_research/Violence%20and%20Women%20in%20Office/final_presentation.pptx).

*Techniques:* Linear Regression

- [01_analysis.Rmd](https://github.com/Mag-Sul/Portfolio/blob/main/class_research/Violence%20and%20Women%20in%20Office/01_analysis.Rmd)

📘 **Data Science I: The Air We Breathe: Air Quality and Health Outcomes in Kentucky (Python)**

*Summary*: Much research has been conducted on the relationship between air pollution and health outcomes. For our final project, we dived deeper into this relationship in a single state in the United States: Kentucky. With 2019 data from the U.S. Centers for Disease Control and Prevention (CDC) and the U.S. Environmental Protection Agency (EPA) , we conducted an exploratory analysis with data visualization and linear regression on overall, respiratory, and mental health outcomes. Due to a very limited sample size (potential political reasons discussed), our results did not show a statistically significant relationship, but we provided recommendations for further research. Read the full report (co-authored with three of my classmates) [here](https://github.com/Mag-Sul/Portfolio/blob/main/class_research/The%20Air%20We%20Breathe/The%20Air%20We%20Breathe%20-%20Air%20Quality%20and%20Health%20Outcomes%20in%20KY.pdf).

*Techniques*: Linear Regression; Overleaf (LaTeX)

- [01_final_data_cleaning.ipynb](https://github.com/Mag-Sul/Portfolio/blob/main/class_research/The%20Air%20We%20Breathe/01_final_data_cleaning.ipynb)
- [02_final_data_merging.ipynb](https://github.com/Mag-Sul/Portfolio/blob/main/class_research/The%20Air%20We%20Breathe/02_final_data_merging.ipynb)
- [03_final_data_visualization.ipynb](https://github.com/Mag-Sul/Portfolio/blob/main/class_research/The%20Air%20We%20Breathe/03_final_data_visualization.ipynb)
- [04_regression.ipynb](https://github.com/Mag-Sul/Portfolio/blob/main/class_research/The%20Air%20We%20Breathe/04_regression.ipynb)

---

### Data Visualization Projects: 

📊 **Parking in DC: A Story of Millions of Red Tickets and Revenue with Unequal Enforcement on Communities of Color (Tableau and R)**

*Summary*: Every driver dreads receiving a parking ticket on their dashboard. However, for those with ample income, this ticket is a minor inconvenience that can easily be settled. In contrast, a ticket of any amount for an individual with low-income is burdensome at minimum and may mean the choice between groceries or paying the fine. In DC, a city known for its history and present as a predominantly Black city, parking tickets are plentiful. My dashboard ([accessible here at Tablueau Public](https://public.tableau.com/views/parking_dc/Story1)) can be used to explore how the enforcement of parking tickets intersects with issues of race and income in DC in 2019, resulting in a disproportionate burden on low-income communities of color. Read the full report [here](https://github.com/Mag-Sul/Portfolio/blob/main/data_visualizations/Parking%20in%20DC/Parking%20in%20DC%20-%20Sullivan.pdf).

*Techniques*: Mapping, exploratory data visualization using Tableau

- [parking_exploration.qmd](https://github.com/Mag-Sul/Portfolio/blob/main/data_visualizations/Parking%20in%20DC/parking_exploration.qmd)

📊 **How to Stop Recreating the Wheel: Creating and saving custom ggplot themes for your organization’s brand (R)**

*Summary* In this blog tutorial, I show how with `ggplot` in R, you can create a new, custom theme that integrates your organization’s brand, including color and font. You can also add your organizational logo to a plot using the packages `cowplot` and `magick`. By placing this code in a `utils.R` document in your project folder, you can easily load these custom visualization settings into new scripts. Read the blog post [here](https://medium.com/@mes440/how-to-stop-recreating-the-wheel-7246bb4d9702).

*Techniques*: custom visualization themes using `ggplot`

- [tutorial.qmd](https://github.com/Mag-Sul/Portfolio/blob/main/data_visualizations/How%20to%20Stop%20Recreating%20the%20Wheel/tutorial.qmd)

---

### Class Assignments (Python): 

*(posted with permission from my Data Science professor)*

:green_book: [00_python_basics.ipynb](https://github.com/Mag-Sul/Portfolio/blob/main/code/00_python_basics.ipynb)
- python lists
- numpy arrays
- basic list comprehension

:green_book: [01_criminal_justice_data.ipynb](https://github.com/Mag-Sul/Portfolio/blob/main/code/01_criminal_justice_data.ipynb)
- recoding variables using np.select and np.where
- aggregation using groupby and agg
- user-defined function to find matches within a broader pool of data
- using list comprehension to apply a function iteratively over list elements

:green_book: [02_guestworker_violations.ipynb](https://github.com/Mag-Sul/Portfolio/blob/main/code/02_guestworker_violations.ipynb)
- pivot from long to wide
- filter out duplicate data 
- merging 
- targeted regex

:green_book: [03_doj_press_releases.ipynb](https://github.com/Mag-Sul/Portfolio/blob/main/code/03_doj_press_releases.ipynb)
- tagging and sentiment scoring
- part of speech tagging
- named entity recognition
- sentiment analysis
- topic modeling
- estimate a topic model using preprocessed words
- extend the analysis from unigrams to bigrams

---
### How to reach me:

:mailbox_with_mail: [maggie.sullivan.111@gmail.com](mailto:maggie.sullivan.111@gmail.comu?subject=[GitHub]%20Source%20Han%20Sans)

[![Linkedin Badge](https://img.shields.io/badge/-Maggie-blue?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/mes440/)
