## Project proposal

New York City department of transportation proposed to add several new subway stations as needed. NY DOT requested a survey plan to determine when and where to take survey at each subway station. This analysis will provide the morning and afternoon traffic for each station on both weekends and weekdays to help determine the survey plan. 

#### Question/need:

* Question: What is the survey plan (where and when?) if we want to determine where to add a new MTA station?

* Need: The NYC underground transportation planning department would benifit from exploring this question for the purpose of planning a new MTA station at a busy area.

#### Data Description:

* Dataset(s) plan to use: MTA turnstile data http://web.mta.info/developers/turnstile.html
                          
* Individual sample/unit, characteristics/features: A year of MTA data; Average daily morning and afternoon busy hour traffic (entries/exists) at each station

* What to predict as a target: Top 10 stations with high average daily morning busy traffic and top 10 stations with high average daily afternoon busy traffic on both weekends and weekdays.


#### Tools:

* SQL, python, pandas, matplotlib, seaborn

#### MVP Goal:

* Clarify the project question and goal.
* Describe the model/algorithm to use.
* Show one plot and a short conclusion
