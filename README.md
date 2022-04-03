# Human-Capital-Analytics-Consulting-Project---Predictive-Modelling-to-assess-Leadership-Effectiveness
# Objective
Built a statistical model (random forest classifier) with 97% accuracy to predict leadership effectiveness, identified opportunities to improve managerial capabilities aiding in leadership strategy development.

# Outcome:
Built a statistical model (random forest classifier) with 96% accuracy to predict leadership effectiveness, identified opportunities to improve managerial capabilities aiding in leadership strategy development

# Predictor Variables:
Average(Act with Humility) – Self Assessed: Average of 8 questions in the leadership assessment,
Average(Lead with transparency) - Self Assessed: Average of 7 questions in the leadership assessment,
Average(Deliver with Focus) - Self Assessed : Average of 9 questions in the leadership assessment,
Average Glint Leadership review – Team members assessed the People Leader: Average of  11 questions from glint survey categorized under Leadership,
Average Innovation – Self Assessed – Average of 5 questions in the leadership assessment, 
Attrition – Average of actual turnover under a specific manager in past 2 years,
Promotions – Average of actual promotions under a specific manager in past 2 years,
Average Checkpoints - Average of actual checkpoints under a specific manager in past 2 years.

# Response Variable:
Effective Leadership(Yes/No)

# Defining Metrics and Data Preparation:
Average(Act with Humility) Score – 0 for Managers with Average < 3.85, 1 for Managers with Average > 3.85,
Average(Lead with transparency) Score – 0 for Managers with Average < 3.77, 1 for Managers with Average > 3.77,
Average(Deliver with Focus) Score - 0 for Managers with Average < 3.76, 1 for Managers with Average > 3.76,
Average Glint Leadership review Score – 0 for Managers with Average < 4.16, 1 for Managers with Average > 4.16,
Average Innovation Score – 0 for Managers with Average < 3.73, 1 for Managers with Average > 3.73,
Attrition Score – 1 if attrition under a Manager < 9.82%(Energy industry’s attrition %-2021) of the total number of reporting members, 0 if attrition under a Manager > 9.82%(Energy industry’s attrition %-2021) of the total number of reporting members(Only Voluntary considered),
Promotions Score – 0 if promotion under a Manager < 10.3%(Manufacturing industry’s promotion%-2021) of the total number of reporting members, 1 if promotions under a Manager > 10.3%(Energy industry’s attrition %-2021) of the total number of reporting members,
Average Checkpoints Score- 0 for Managers with Average < 2, 1 for Managers with Average > 2,
Overall Leadership Effectiveness Score  – 0(Not effective) if humility is 0 and more than 3 of the other metrics considered are 0 and 1 if humility is 1 and more than 3 metrics considered are 1(Effective). 



