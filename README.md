# CV-recommendation
Looking from a candidate's perspective, finding a job which matches his profile as well as interest is a challenging task. Hence, built a Model using Natural Language Processing and Data Analytics which can recommend the best job profile to a candidate based on his skills, past experiences, and projects mentioned in the resume. Also suggested skills which he needs to learn that are used in a market the most for any domain.
25+ Teams participated from all over Gujarat in this 36-hour hackathon and the winning news were published in Divya Bhaskar newspaper.
Input: Candidate’s CV, Target field of the candidate. 
Output: Best sub-Job domain for the candidate, Recommendation of required skills for the target field


Tools used: Python, Rstudio

Description: First we developed a baseline model that suggest missing skills in candidate by using our ideal skill-set data. 
To recommend sub-domain, we developed a mathematical model which gives weights to skills by incorporating skill experience information. 
And give scores to a different domain. (for that candidate) We recommend highest score domain to the candidate.

Developed hybrid model, which is able to do both things. 
Also as new data of candidate comes our model automatically update its skill set to capture recent trends in each domain. 
As data increases, our recommendation becomes data-driven.

Applied Natural Language Processing to process project description written in CV. 
After applying NLP, we use statistical analysis of skills. Then we recommend job subdomain for that candidate. 
This inference is useful for skill recommendation module for other candidates.

Extension of the project: Developing candidate recommendation system for organization.
