## EasyVisa Project

### Context

Business communities in the United States are facing high demand for human resources, but one of the constant challenges is identifying and attracting the right talent, which is perhaps the most important element in remaining competitive. Companies in the United States look for hard-working, talented, and qualified individuals both locally and abroad.

The Immigration and Nationality Act (INA) of the US permits foreign workers to come to the United States to work on either a temporary or permanent basis. The act also protects US workers against adverse impacts on their wages or working conditions by ensuring US employers' compliance with statutory requirements when they hire foreign workers to fill workforce shortages. The immigration programs are administered by the Office of Foreign Labor Certification (OFLC).

OFLC processes job certification applications for employers seeking to bring foreign workers into the United States and grants certifications in those cases where employers can demonstrate that there are not sufficient US workers available to perform the work at wages that meet or exceed the wage paid for the occupation in the area of intended employment.

### Objective

In FY 2016, the OFLC processed 775,979 employer applications for 1,699,957 positions for temporary and permanent labor certifications. This was a nine percent increase in the overall number of processed applications from the previous year. The process of reviewing every case is becoming a tedious task as the number of applicants increases each year.

The increasing number of applicants calls for a Machine Learning-based solution that can help in shortlisting candidates with a higher chance of visa approval. OFLC has hired EasyVisa for data-driven solutions. As a data scientist at EasyVisa, I analyzed the provided data and developed a classification model to:

- Facilitate the process of visa approvals.
- Recommend suitable profiles for applicants for whom the visa should be certified or denied based on the drivers that significantly influence the case status.

### Data Description

The data contains different attributes of the employee and the employer. The detailed data dictionary is given below.

| **Attribute**                  | **Description**                                                                                                                                                       |
|--------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| case_id                        | ID of each visa application                                                                                                                                         |
| continent                      | Information about the continent of the employee                                                                                                                     |
| education_of_employee          | Information about the education level of the employee                                                                                                               |
| has_job_experience             | Indicates whether the employee has any job experience (Y = Yes; N = No)                                                                                            |
| requires_job_training          | Indicates whether the employee requires any job training (Y = Yes; N = No)                                                                                         |
| no_of_employees                | Number of employees in the employer's company                                                                                                                      |
| yr_of_estab                    | Year in which the employer's company was established                                                                                                                |
| region_of_employment           | Information about the foreign worker's intended region of employment in the US                                                                                        |
| prevailing_wage                | Average wage paid to similarly employed workers in a specific occupation in the area of intended employment. This ensures that the foreign worker is not underpaid. |
| unit_of_wage                   | Unit of prevailing wage (Hourly, Weekly, Monthly, Yearly)                                                                                                           |
| full_time_position             | Indicates if the position is full-time (Y = Full-Time Position; N = Part-Time Position)                                                                              |
| case_status                    | Flag indicating whether the visa was certified or denied                                                                                                             |

### Skills Learned

During the course of this project, I developed and enhanced the following skills:

- **Exploratory Data Analysis (EDA):** 
  - Clarified project scope and objectives.
  - Conducted univariate and bivariate analysis.
  - Visualized data to identify patterns and correlations.

- **Data Preprocessing:** 
  - Handled duplicate values and missing data through appropriate imputation techniques.
  - Detected and treated outliers.
  - Engineered new features to enrich the dataset.

- **Machine Learning Model Building:**
  - Developed a classification model using Python libraries.
  - Analyzed model performance through various statistics and metrics.

- **Assumption Testing:**
  - Verified linear regression assumptions, including normality and multicollinearity.
  - Interpreted results to ensure model reliability.

- **Model Performance Evaluation:**
  - Evaluated the model using key performance metrics, including accuracy and precision.

- **Actionable Insights and Recommendations:**
  - Provided strategic insights based on the model's findings to inform decision-making.

- **Documentation and Presentation:**
  - Organized the project notebook with clear sections and logical flow.
  - Included well-commented code for ease of understanding.
  - Enhanced visual appeal with data visualizations and error handling.
