Welcome to the HMX Data Science & Analytics takehome exam. Please submit answers in the form of a Jupyter notebook, in any scripting language of your choice. Please email zipped files to matt_bunch@hms.harvard.edu within five days of receiving the exam.

## Scenario

Imagine our team is tasked to understand learner behavior within an online course. The broader team would like to better understand learner behavior and predictability of learner completion.

The data in `data.csv` is a sample of learner question submission. All data is tied to registered and enrolled users.

The objective is to understand learner behavior and to predict learner completion. 

**Note: Each row in `data.csv` represents a learners question submission.**

## Data

| Column Name     | Description       | Desc Cont      |
| --------------- | ----------------- | -------------- |
| course_id | the course id
| max_grade | the maximum grade the learner could earn
| created | the datetime of when the original record was created
| grade | the learners earned points
| learner_id | the learners unique identifier
| modified | the datetime in which the record was modified
| state | JSON formatted string containing:
|    - last_submission_time | of the attempts taken, the last time
|    - attempts | number of question attempts taken 
|    - score|
|        |- raw_possible | the points possible for a learner to earn
|        |- raw_earned | the points a learner earned
|   - done | Bool
|   - student_answers|
|        |- section_id | the section_id itself is in the form of a hash
|    - seed| 


## Questions

1. What percent of each question did learners attempt twice?

2. Which questions were most frequently answered incorrect?

3. Create a visualization exploring the relationship between any of the content characteristics (such as learners, attempts, time etc...). This is an open-ended task. Briefly describe the visualization and the insight.

4. Create a simple model predicting the likelihood of a learner passing the course. (A passing grade is 80% or above)

5. What additional data would you add to improve the model? (Answer in 3-5 sentences)
