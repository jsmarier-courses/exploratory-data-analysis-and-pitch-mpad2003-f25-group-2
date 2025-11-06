**November 6th, 2025**<br>
**2003A Introductory Data Storytelling**<br>
**Michelle Clarke, Yi Liu, Corinna Macintyre**<br>
**Presented to Jean-Sébastien Marier**<br>

# Exploratory Data Analysis (EDA) & Pitch

Use one hashtag symbol (`#`) to create a level 1 heading like this one.

## Foreword

For this assignment, you must extract data from a dataset provided by the instructor. You must then clean and analyze the data, create exploratory charts/visualizations, and find a potential story idea. Your assignment must clearly detail your process. You are expected to write about 1500-2000 words, and to include several screen captures showing the different steps you went through. Your assignment must be written with the Markdown format and submitted on GitHub Classroom.

I have been assigning different versions of this project to my digital journalism and data storytelling students for a few years now. Its structure was inspired by the main sections/chapters of [*The Data Journalism Handbook*](https://datajournalism.com/read/handbook/one/). This version was further inspired by the [Key Capabilities in Data Science](https://extendedlearning.ubc.ca/programs/key-capabilities-data-science) program offered by the University of British Columbia (UBC).

**Here are some useful resources for this assignment:**

* [GitHub's *Basic writing and formatting syntax* page](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* [The template repository for this assignment in case you delete something by mistake](https://github.com/jsmarier/jou4100_jou4500_mpad2003_project2_template)

Did you notice how to create a hyperlink? In Markdown, we put the clickable text between square brackets and the actual URL between parentheses.

And to create an unordered list, we simply put a star (`*`) before each item.

## 1. Introduction

Insert text here.



## 2. Getting Data
To import the dataset into Google Sheets, I started by opening a new blank sheet in Google Sheets. Then I clicked on File at the top left corner, selected Import, and clicked Upload to import the dataset file from my computer. Once the file was uploaded, I selected to replace the current sheet so all the data would show up.

![](data-sheet-picture.png)<br>
*Figure 1: The "Import file" prompt on Google Sheets.*


Looking at the dataset, I noticed that it has 26 rows and 2,603 columns. In this dataset, Global Non-Response shows the percentage of people who didn’t answer the survey in each ward, so it’s a continuous variable because it can take on decimals like 1.7% or 7.6%. Total - Age groups of the population gives the total number of people in each ward, which is also a continuous variable since the numbers can vary widely from ward to ward. Looking further at household data, the column In a two-parent family gives a count of children living with both parents in each ward, which is a discrete variable because it’s whole numbers. 

The dataset has 26 rows and 2,603 columns. The data isn’t super clean. Some cells are blank, which might mean the info is missing or there just isn’t any data for that row. Also, a lot of the numbers have commas (like “26,395”), which can mess up trying to find certain data because Google Sheets treats them as text instead of actual numbers. That means you’ll have to spend more time cleaning it up before doing any calculations.

As I look at the raw data, one question that comes to mind is why some language rows have all zeros. I’m not sure if that means the data is missing or if there really aren’t any speakers of those languages in certain wards. A hypothesis I have is that wards with more people aged 65 and over probably have more people living alone, while wards with more kids (0–14 years) probably have more two-parent families.


## 3. Understanding Data



### 3.1. VIMO Analysis

Use three hashtag symbols (`###`) to create a level 3 heading like this one. Please follow this template when it comes to level 1 and level 2 headings. However, you can use level 3 headings as you see fit.

Insert text here.

Support your claims by citing relevant sources. Please follow [APA guidelines for in-text citations](https://apastyle.apa.org/style-grammar-guidelines/citations).

**For example:**

As Cairo (2016) argues, a data visualization should be truthful...

### 3.2. Cleaning Data

Insert text here.

### 3.3. Exploratory Data Analysis (EDA)

Insert text here.

**This section should include a screen capture of your pivot table, like so:**

![](pivot-table-screen-capture.png)<br>
*Figure 2: This pivot table shows...*

**This section should also include a screen capture of your exploratory chart, like so:**

![](chart-screen-capture.png)<br>
*Figure 3: This exploratory chart shows...*

## 4. Potential Story

We want to explore how different wards in Ottawa are being funded and developed, and whether some areas are getting left behind. Looking at the numbers, some wards seem to have higher incomes and more people living in houses, while others have lower incomes or more people in apartments. Are those differences reflected in how much funding or resources each ward gets? And if not, why might certain areas be overlooked?

To tell this story properly, we would need more detailed data, including ward budgets, per-person investment, and housing types by ward. It would also help to have visuals like maps we could overlay with income, population, ward type (rural, suburban, or urban), and funding levels. Seeing these patterns on a visual map would make it much easier to spot imbalances and understand how resources are distributed across the city.

The story could start with a city-wide map highlighting income differences across wards, immediately showing readers where gaps may exist. From there, it could zoom in on one or two different wards, perhaps a wealthy, well-resourced area versus a lower-income ward with fewer resources to highlight the human impact of these imbalances. Adding stories from local residents, along with visual data, could really show not just where the differences exist, but why they matter and how they affect these communities.


## 5. Conclusion

Insert text here.

## 6. References

Include a list of your references here. Please follow [APA guidelines for references](https://apastyle.apa.org/style-grammar-guidelines/references). Hanging paragraphs aren't required though.

**Here's an example:**

Bounegru, L., & Gray, J. (Eds.). (2021). *The Data Journalism Handbook 2: Towards A Critical Data Practice*. Amsterdam University Press. [https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153](https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153)
