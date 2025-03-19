Here’s a professional `README.md` file tailored for your GitHub repository, framing this project as a strong portfolio piece for data science and data analyst roles. It highlights your technical skills, analytical insights, and the impact of your work.

---

# Visual Analytics Investigation: Water Contamination and Wildlife Impact in Mistford

## Project Overview
This project focuses on analyzing water contamination trends in the **Boonsong Lekagul Wildlife Preserve** and their potential impact on the endangered **Rose-Crested Blue Pipit** bird species. Using the **VAST Challenge 2018 Mini Challenge 2** dataset, the project investigates water sensor readings from rivers and streams across the preserve. The analysis was conducted using **Altair** for visualizations and Python for data preprocessing and statistical analysis.

This project was completed as part of my **Data Science degree** and demonstrates my ability to:
- Clean, explore, and analyze complex environmental datasets.
- Identify data quality issues, trends, and anomalies.
- Create interactive and insightful visualizations using Altair.
- Communicate findings effectively through visualizations and reports.

---

## Dataset Details
### Dataset Source
- **VAST Challenge 2018 Mini Challenge 2**: Water sensor readings from rivers and streams in the Boonsong Lekagul Wildlife Preserve.
- **Timeframe**: Several years of data, with readings from 1998 to 2016.
- **Measurements**: Water temperature, dissolved oxygen, ammonium, nitrites, nitrates, total phosphorus, sodium, potassium, iron, manganese, total coliforms, and more.

### Key Features
- **Location**: Sensor readings from multiple locations across the preserve.
- **Time Series Data**: Measurements taken at different dates over the years.
- **Chemical Measurements**: Quantitative data on various chemicals of interest.

---

## Analysis Goals
The project was divided into two main tasks:
1. **Data Quality and Uncertain Issues**:
   - Identify missing data, changes in collection frequency, and unrealistic values.
   - Visualize and analyze data quality issues to ensure reliable insights.

2. **Trends and Anomalies in Chemical Contamination**:
   - Analyze trends in chemical measurements over time and across sensor sites.
   - Identify anomalies such as sudden spikes or significant differences between sites.

---

## Key Findings
### Task 1: Data Quality and Uncertain Issues
1. **Missing Data**:
   - No null values were found in the dataset.
   - Zero values accounted for **7.09%** of the dataset. These were retained as they represent valid low readings.
   - Three locations (Achara, Decha, Tansanee) had data only from **2009 to 2016**, while others had data from **1998 to 2016**.

2. **Unrealistic Values**:
   - **Iron**: Recorded values as high as **37,959.28** (e.g., Kohsoom, August 2003), significantly higher than the average of **81.34**.
   - **Total Coliforms**: Unusually high readings, such as **16,090** in Achara (January 15, 2009) and **13,000** in Kohsoom (October 20, 2010).
   - **Manganese**: Spikes observed in Chai and other locations, with values exceeding the average of **5.53**.

3. **Visualizations**:
   - **Bar Chart**: Showed average values of chemical measurements, highlighting outliers.
   - **Scatter Plot**: Identified unrealistic values for iron, total coliforms, and manganese.
   - **Box Plot**: Visualized the distribution of unrealistic values for key chemicals.

### Task 2: Trends and Anomalies in Chemical Contamination
1. **Trends Over Time**:
   - **1998–2002**: Most chemicals showed similar fluctuating patterns, with spikes in manganese, zinc, and total coliforms.
   - **2004–2008**: Higher overall readings, with a significant spike in total dissolved salts (value = **2,330**).
   - **2011–2016**: Increased frequency of spikes, particularly in total coliforms and dissolved salts.

2. **Anomalies**:
   - **Total Coliforms**: Consistently high values until 2013, followed by irregular spikes.
   - **Dissolved Salts**: A sudden spike to **1,300** in 2016, deviating from the usual fluctuations.

3. **Visualizations**:
   - **Line Charts**: Tracked trends in chemical measurements over three time periods (1998–2002, 2004–2008, 2011–2016).
   - **Interactive Features**: Enabled tooltips to display exact values and dates for anomalies.

---

## Tools and Techniques
- **Altair**: Used for creating interactive visualizations, including bar charts, scatter plots, box plots, and line charts.
- **Python**: Used for data preprocessing, statistical analysis, and generating visualizations.
- **Excel**: Assisted in filtering and validating data quality issues.
- **Advanced Altair Features**:
  - **Tooltips**: Enabled interactive exploration of data points.
  - **Multi-Layer Visualizations**: Combined multiple charts for comprehensive analysis.
  - **Dashboard**: Integrated visualizations for a holistic view of trends and anomalies.

---

## Why This Project Matters
This project demonstrates my ability to:
- **Handle Real-World Data**: Address data quality issues and ensure reliable analysis.
- **Identify Trends and Anomalies**: Use visual analytics to uncover patterns and outliers in environmental data.
- **Communicate Insights**: Present findings through clear and interactive visualizations.
- **Apply Domain Knowledge**: Link chemical contamination trends to potential environmental impacts.

---

## How to Use This Repository
1. **Jupyter Notebook**: The main notebook (`Main_working_file.ipynb`) contains the code for data preprocessing, analysis, and visualizations.
2. **Report**: The detailed report (`Project_Report.pdf`) provides a comprehensive explanation of the analysis, findings, and visualizations.
3. **Dataset**: The original and preprocessed datasets are included for reference.

---

## Skills Demonstrated
- **Data Cleaning and Preprocessing**: Handling missing data, unrealistic values, and inconsistencies.
- **Data Visualization**: Creating interactive and insightful visualizations using Altair.
- **Statistical Analysis**: Identifying trends, anomalies, and correlations in time-series data.
- **Problem-Solving**: Addressing complex environmental questions with data-driven insights.

---

## Relevance to Data Science and Data Analyst Roles
This project aligns with the core responsibilities of **Data Scientists** and **Data Analysts**:
- **Data Exploration and Cleaning**: Handling real-world datasets with missing or inconsistent data.
- **Pattern Recognition**: Identifying trends and anomalies in large datasets.
- **Visualization**: Creating dashboards and reports to communicate insights.
- **Domain-Specific Analysis**: Applying analytical skills to environmental and ecological datasets.

---

## Contributors
- **Gil Johan Chingkiat** (M00655353)
- **Usama Imtiaz** (M00982414)
- **Thanura Rashmika** (M00971236)
- **Chinanza Kosisochukwu Ugwu** (M00965050)
- **Harry**
  
