# pandas-challenge
# Background
You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

# District Summary
Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.

Include the following:

Total number of unique schools

Total students

Total budget

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)

# School Summary
Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.

Include the following:

School name

School type

Total students

Total school budget

Per student budget

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)

# Highest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in descending order and display the top 5 rows.

Save the results in a DataFrame called "top_schools".

# Lowest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.

Save the results in a DataFrame called "bottom_schools".

# Math Scores by Grade
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

# Reading Scores by Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

# Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student).

Include the following metrics in the table:

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)

# Scores by School Size
Use the following code to bin the per_school_summary.

size_bins = [0, 1000, 2000, 5000]
labels = ["Small (<1000)", "Medium (1000-2000)", "Large (2000-5000)"]
Use pd.cut on the "Total Students" column of the per_school_summary DataFrame.

Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

# Scores by School Type
Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.

This new DataFrame should show school performance based on the "School Type".


# Analysis
The purpose of this analysis is to help educators, administrators, and local governments/policy makers make informed and accurate decisions in order to improve the educational achievements of the students in their district. The data was analyzed based on student grades (math, reading, or both combined), individual schools, whether the school was a charter or district school, as well as funding and school size. Overall, students in charter schools have higher average scores and passing rates in both math and reading when compared to district schools. Based on the data it is evident that charter schools tend to allocate more funding per student whereas, district schools have an overall higher budget due to higher student populations. This may contribute to the reason charter schools tend to perform better in terms of higher average grades and passing rates due to more funding allocated per student thus, more resources per student. So, while district schools have a larger budget, this isn’t necessarily being allocated solely towards student success resources. Furthermore, students tended to do better in reading than math, with the average reading score being 82.41 while the average math score was 79.94. Also, the reading scores had a more even distribution with the scores being in the range of 76-89. In summary, it seems that there are other factors that impact the student’s performances such as quality of the curriculum, the ratio of teacher to student, and demographics. However, while the funding is lower for charter schools, their performance is higher indicating quality over quantity in this dataset.
# Resources
I used StackOverflow, my group, AskBCS, and the internet for assistance with writing the code as well as with the errors I encountered
