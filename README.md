# Data Journal 
Goals and Expectations
My goal with this project is to be able to freely use the skills I learned from the previous Google Data Analytics courses to produce meaningful insights into certain data. I look forward to demonstrating my data cleaning, modeling, evaluation, and visualization skills. Specifically, this case study aims to understand how casual riders and annual members use Cyclistic bikes differently.

# The 'Ask' Phase of the Data Analysis Process
**Company Background:**
Cyclistic is a bike-sharing company based in Chicago, offering a fleet of bicycles for public use across the city. The company operates on a subscription-based model, providing options for both casual riders and annual members. Cyclistic is committed to promoting an inclusive and accessible mode of transportation, catering to the needs of a diverse range of users.

**Data Context:**
The dataset consists of a year’s worth of Cyclistic’s historical trip records, providing insights into the usage patterns of both casual riders and annual members. Key variables in the dataset include the start and end times of each trip, start and end station details, the type of bike used, and the rider’s status as either a casual user or an annual member.

**Problem Statement:**
The objective is to understand the differences in how casual riders and annual members use Cyclistic bikes. This understanding will help in designing a marketing strategy aimed at converting casual riders into annual members.

**Business Task:**
Analyze Cyclistic’s historical bike trip data to uncover differences in the usage patterns between casual riders and annual members. Utilize these insights to inform the development of a marketing strategy focused on converting casual riders into annual members.

**Key Stakeholders:**
*Lily Moreno:* Director of Marketing, responsible for developing campaigns and initiatives to promote the bike-sharing program.
*Cyclistic Marketing Analytics Team:* This team is responsible for gathering, analyzing, and reporting data to guide Cyclistic’s marketing strategy.
*Cyclistic Executive Team:* This team will review and decide whether to approve the recommended marketing program.

**Key Questions:**
*The analysis will aim to answer the following key questions:*
How do annual members and casual riders use Cyclistic bikes differently?
What are the patterns or behaviors unique to casual riders that could potentially be addressed by a targeted marketing campaign?
What are the trends over time for these two user groups? Are there seasonal patterns that could inform the timing of the marketing campaign?

**Assumptions:**
It is assumed that the data provided is accurate, up-to-date, and representative of the broader rider population. We also assume that rider behavior is primarily influenced by their status as either casual riders or annual members, rather than by other unrecorded factors.
Limitations: The dataset provides detailed information about ride patterns but lacks demographic data such as age, gender, or socioeconomic status. Consequently, our analysis and conclusions are based solely on ride patterns and do not account for the influence of demographic factors.


# The 'Prepare' phase of the Data Analytics Process:

**Data Location and Organization**

**Data Source:**  
The data used in this case study is provided by Motivate International Inc. and is publicly accessible for download. It represents the historical trip data for Cyclistic bikes. The data is likely organized in a structured format such as CSV or Excel, where each row corresponds to a bike trip, and the columns include features such as trip duration, start and end times, start and end station details, bike type, and user type (either casual rider or member).

**Data Credibility and Bias:**  
Since the data is provided by the company operating the bike-sharing service, it is expected to be reliable. However, potential biases may exist due to operational constraints or data collection methods. For instance, the data only includes users who opted to use Cyclistic's service, which might not represent the entire population of bike riders in Chicago.

**Licensing, Privacy, Security, and Accessibility:**  
The data is provided under a specific license that allows its use for analysis but restricts its distribution as a standalone dataset. Privacy is safeguarded as the dataset does not contain any personally identifiable information. To maintain security, the downloaded data should be stored in a secure location, potentially with encryption if necessary. Accessibility involves ensuring that the data and the resulting analysis are available to all relevant stakeholders involved in the project.

**Data Integrity:**  
To ensure the data's integrity, exploratory data analysis (EDA) will be conducted to identify any inconsistencies, missing values, outliers, or duplicate entries.

**Relevance to the Business Question:**  
The dataset contains key information on bike trips made by both casual riders and annual members, which is directly aligned with the business objective of understanding the different usage patterns of these two groups. Analyzing this data will provide insights that can inform the development of a marketing strategy aimed at converting casual riders into annual members.

**Potential Issues:**  
Potential challenges may include missing data, inaccuracies within the data, or inherent biases. The dataset might also lack certain information that could enhance the analysis, such as demographic details of the riders or specific reasons for choosing a casual ride versus a membership.

**Key Tasks:**  
1. **Download and Store the Data:** Securely download the dataset from the provided source and store it in a safe local or cloud-based environment.
2. **Understand the Data Structure:** Explore the dataset to comprehend its structure and the meaning of each column.
3. **Organize and Filter the Data:** Sort and filter the data based on variables relevant to your analysis, such as user type or trip duration, and exclude any data that is not pertinent to the business question.

# What had to be changed?
The file "C:\Users\mateu\Classes 2022\Downloads\202405-divvy-tripdata.zip" needs to be imported into Google BigQuery to be analyzed, but before, the data needs to be cleaned, I will be cleaning most of it on the excel file itself, so when I go to BigQuery I can focus on the more specific errors. The first steps I took were:


