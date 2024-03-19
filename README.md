# DataHouseAssessments
DataHouseAssessments

The assignment was written in Jupyter Notebook using Python language
How do I Approach the Problem

1. Defind attributes that align with the requirements of the job, team, and company culture (e.g., experience, adaptability, humility, innovation, communication, leadership, bananaLover)
2. 
3. Create a .json data set that includes arrays for 'teams' and 'applicants', with 10 data points each. Attribute scores should be randomly set in the range [0,10].
4. Weight each attribute in the range [0, 10]
5. Create compatibility_predictor function
  * Calculate the score of each team member and applicant.
  * Compatibility scores will be determined by the ratio of the change in an applicant's score to the average team score, relative to the maximum score each person can achieve.
  * Normalize the compatibility score using this formula:
(value_to_normalized - min_val_in_data) / (max_val_in_data - min_val_in_data) * (new_max - new_min) + new_min
