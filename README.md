# PyCity School Budget Analysis

# Overview:
In assuming the role of Chief Data Scientist for the city's school district, I conducted an extensive examination of district-wide standardized test results. Employing Pandas DataFrames and Jupyter Notebook, I amalgamated data from various sources to uncover trends in school performance. This endeavor served as a pivotal foundation for informing strategic decisions regarding future school budgets and priorities.

# Objective:
The primary aim was to scrutinize standardized test results across 249 mice with SCC tumors treated with diverse drug regimens, focusing particularly on Pymaceuticals’ drug, Capomulin. This comprehensive analysis was geared towards furnishing actionable insights to the school board and mayor, thereby guiding forthcoming educational strategies and investments.

# Methodology:
Data Preparation:

Merged mouse_metadata and study_results DataFrames.
Cleansed the data by eliminating duplicates.
Formulated a unified dataset for analysis.

District Summary:
Computed key metrics such as total schools, students, budget, and average scores.
Derived percentages for passing math, reading, and overall passing rates.

School Summary:
Condensed key metrics by school, encompassing type, total students, budget, and scores.
Calculated percentages for passing math, reading, and overall passing.

Performance Analysis:
Identified highest and lowest-performing schools by % overall passing.
Examined math and reading scores by grade for each school.
Evaluated school performance based on budget per student, school size, and type.

# Key Findings:
Capomulin exhibited significant efficacy compared to other drug regimens in tumor reduction.
A noteworthy correlation emerged between school budgets per student and overall passing rates, with schools with lower per-student budgets demonstrating superior performance.
Small to medium-sized schools (less than 2000 students) exhibited higher overall passing rates compared to larger schools.

# Challenges and Solutions:
The analysis necessitated intricate data manipulation tasks, including dataset merging, summary statistics computation, and school categorization based on spending, size, and type. Solutions involved leveraging advanced Pandas functionalities like .groupby(), .cut(), and conditional formatting to streamline the analysis process and generate insightful visualizations.

# Conclusion:
The PyCity Schools analysis unveiled significant insights into the effectiveness of varied educational strategies and resource allocations. Through a focus on data-driven decision-making, the school district can enhance student outcomes and optimize budgetary allocations. The revelations from this report will play a pivotal role in shaping future educational priorities and ensuring equitable access to quality education.
