# MSDS6306 CaseStudy2 Codebook

## MinorLeague Group Members
- Brandon Croom, Sandesh Ojha, Sangrae Cho

### Study Overview
This study contains an exploratatory data analysis of a single data set `CaseStudy2-data`. The team has been asked to evaluate the data set and attempt to determine which if any of the features could be contributing factors for employee attrition. The team has also been asked to provide any other insights that the data may expose as part of their analysis

### The Data

`data/CaseStudy2-data.csv`

| FEATURE                 | DESCRIPTION            |
|:-----------------------:|:---------------------:|
|Age                      | The age of the employee |
|Attrition                | Denotes whether attrition has occurred in role |
|BusinessTravel           | Denotes how much business travel is required   |
|DailyRate                | Denotes the daily rate of the employee |
|Department               | Denotes the department of the employee |
|DistanceFromHome         | Denotes the distance an employees role is from home |
|Education                | Denotes the type of degree an employee has obtained |
|EducationField           | Denotes the field an employees degree is in         |
|EmployeeCount            | Constant value in this version of the data set |
|EmployeeNumber           | Number assigned to the employee |
|EnvironmentSatisfaction  | Employee's rating of job environment |
|Gender                   | Denotes the employee's gender |
|HourlyRate               | Denotes the hourly rate of the employee |
|JobInvolvement           | Employee's rating of job involvement |
|JobLevel                 | Denotes the employee's job level |
|JobRole                  | Denotes the employee's job role |
|JobSatifaction           | Employee's rating of job satisfaction |
|MaritalStatus            | Employee's marital status |
|MonthlyIncome            | Denotes employee's monthly income |
|MonthlyRate              | Denotes employee's monthly rate |
|NumCompaniesWorked       | Number of companies the employee has worked for |
|Over18                   | Denotes whether the employee is over 18 years of age |
|OverTime                 | Indicates whether the employee gets over time | 
|PercentSalaryHike        | Indicates the percentage of the employee's last salary hike |
|PerformanceRating        | Rating employee received at last performance rating |
|RelationshipSatisfaction | Employee's rating of relationship satisfaction |
|StandardHours            | Standard number of hours the employee works |
|StockOptionLevel         | Indicator of the stock option level of the employee |
|TotalWorkingHours        | Total working hours of the employee |
|TrainingTimesLastYear    | Indicates the total number of trainings in a year |
|WorkLifeBalance          | Employee's rating of work life balance |
|YearsAtCompany           | Number of years the employee has been at the company |
|YearsInCurrentRole       | Number of years the employee has been in their current role |
|YearsSinceLastPromotion  | Number of years since employee was last promoted |
|YearsWithCurrManager     | Number of years the employee has been with their current manager |

**Data Definitions for Specific Features:**

Feature: Education

| VALUE       | DESCRIPTION           |
|:-----------:|:---------------------:|
| 1           | Below College         |
| 2           | Bachelor              |
| 3           | Master                |
| 4           | Doctor                |

Feature: EnvironmentSatisfaction

| VALUE       | DESCRIPTION           |
|:-----------:|:---------------------:|
| 1           | Low                   |
| 2           | Medium                |
| 3           | High                  |
| 4           | Very High             |

Feature: JobInvolvement

| VALUE       | DESCRIPTION           |
|:-----------:|:---------------------:|
| 1           | Low                   |
| 2           | Medium                |
| 3           | High                  |
| 4           | Very High             |

Feature: PerformanceRating

| VALUE       | DESCRIPTION           |
|:-----------:|:---------------------:|
| 1           | Low                   |
| 2           | Good                  |
| 3           | Excellent             |
| 4           | Outstanding           |

Feature: RelationshipSatisfaction

| VALUE       | DESCRIPTION           |
|:-----------:|:---------------------:|
| 1           | Low                   |
| 2           | Medium                |
| 3           | High                  |
| 4           | Very High             |

Feature: WorkLifeBalance

| VALUE       | DESCRIPTION           |
|:-----------:|:---------------------:|
| 1           | Bad                   |
| 2           | Good                  |
| 3           | Better                |
| 4           | Best                  |

### Folder & File Information

- `CaseStudyInfo/` Contains all the background information important for understanding
the purpose of the study. This folder contains files.

  + `Case Study 02.pdf` The entire case study file that outlines the objectives of the study.
  
- `Data/` This folder contains all the data files that is used in the study.

  + `CaseStudy2-data.csv` contains list of 1,470 employee records and 35 individual features
  + `CaseStudy2-data` contains an Excel version of the same data, which includes data definitions for some fields
  
 - `DDSAnalytics_Case_Study.Rmd` contains the analysis of the data files, exploratory data analysis and conclusions about the data
 
 - `DDSAnalytics_Case_Study.html` contains the HTML output of the RMarkdown file.
 
 - `MinerLeague Presentation Case Study 2.pptx` contains a PowerPoint presentation developed off of the analysis performed in `DDSAnalytics_Case_Study.Rmd`to allow for easily reporting on analysis.


### Researcher Information & Responsibilities

| Researcher | Questions of Interest |
|:-----------:|:---------------------:|
|Brandon Croom|Data cleaning, initial coding   |
|Sandesh Ojha|Presentation prep, editing code |
|Sangrae Cho|Readme, editing code|
