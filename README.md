# PR1_Maths

# Expectation Decider - Probability Analysis Project

## Project Overview

The Expectation Decider project aims to analyze the probability of students passing a competitive mathematics examination using historical educational data. The project applies fundamental probability concepts, probability distributions, conditional probability, Bayes Theorem, and data visualization techniques to identify factors that influence student success.

The analysis was performed using Python in Jupyter Notebook with the following libraries:

* Pandas
* NumPy
* Matplotlib

---

## Dataset Description

The dataset contains information about 200 students and includes the following attributes:

| Column Name         | Description                                 |
| ------------------- | ------------------------------------------- |
| study_hours         | Number of hours studied per week            |
| attendance          | Percentage attendance in lectures           |
| group_discussion    | Participation in group discussions (Yes/No) |
| previous_test_score | Previous internal test score out of 100     |
| final_exam_pass     | Final competitive exam result (Pass/Fail)   |

---

## Project Objectives

* Understand basic probability concepts using real-world educational data.
* Calculate empirical and theoretical probabilities.
* Analyze probability distributions using random variables.
* Visualize relationships between study habits and attendance using Venn diagrams.
* Construct contingency tables and calculate joint, marginal, and conditional probabilities.
* Determine relationships between events using probability theory.
* Apply Bayes Theorem to estimate the probability of passing based on attendance.

---

## Tasks Performed

### Task 1: Understanding the Basics

* Defined probability and key probability terminology.
* Identified probability events from the dataset.
* Calculated probabilities for:

  * Study Hours > 10
  * Attendance > 80%
  * Passing the Final Exam

### Task 2: Types of Events

* Calculated empirical probability using observed data.
* Calculated theoretical probability using mathematical assumptions.
* Compared empirical and theoretical results.

### Task 3: Random Variable & Probability Distribution

* Defined a random variable representing the number of students passing among three randomly selected students.
* Constructed a probability distribution table.
* Calculated:

  * Mean (Expected Value)
  * Variance
* Visualized the probability distribution using a bar chart.

### Task 4: Venn Diagram in Probability

* Identified students who:

  * Studied more than 10 hours/week.
  * Maintained attendance above 80%.
* Determined the overlap between both groups.
* Created a Venn diagram to represent set relationships.

### Task 5: Contingency Table & Probability Calculations

* Created a contingency table for:

  * Group Discussion Participation
  * Final Exam Result
* Calculated:

  * Joint Probability
  * Marginal Probability
  * Conditional Probability

### Task 6: Understanding Relationships

* Interpreted conditional probability results.
* Determined whether events were:

  * Independent
  * Dependent
  * Mutually Exclusive

### Task 7: Bayes Theorem Application

* Applied Bayes Theorem using attendance and exam performance data.
* Estimated the probability of passing given high attendance.

---

## Visualizations

The project includes:

* Event Probability Bar Chart
* Probability Distribution Graph
* Attendance Distribution Histogram
* Study Hours Histogram
* Pass vs Fail Analysis Chart
* Venn Diagram Visualization

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib

---

## Key Findings

* Students participating in group discussions demonstrated a higher probability of passing.
* High attendance was strongly associated with examination success.
* Students studying more than 10 hours per week and maintaining attendance above 80% formed an academically stronger group.
* Group discussion participation and exam success were found to be dependent events.
* Bayes Theorem analysis showed that students with high attendance had a significantly greater probability of passing.

---

## Conclusion

This project demonstrates how probability theory and statistical analysis can be applied to educational datasets to identify patterns influencing student performance. Through empirical probability, probability distributions, conditional probability, and Bayes Theorem, meaningful insights were derived regarding study habits, attendance, and collaborative learning behaviors.
