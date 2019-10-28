# vikingsPredictions

### Introdution
Well, as a Vikings fan I was curious as to why the 2018 season did not end as many predictied or wanted it to.  The team did not make the playoffs and ended with a record that was pretty dissapointing.  In this project, I wanted to use Machine Learning and classification methods to look at the offense and see how predictable John DeFilippo (the offensive coordinator) was when calling plays.  *These stats reflect the OC's preditability, not the team in general.* 

### Quick Look
The Vikings threw the ball almost 2/3 of the time and were more predictable with features such as shotgun formation, down and distance, winning percentage and time outs remaining. 

### Data
All of the data is from https://github.com/ryurko/nflscrapR-data where I only used the plays from 2018 where the Vikings were on offense. (I tookout kickoffs, field goals..etc).  I cleaned and saved the data into a new df, the imported that on my notebooks, if you are interested in that process let me know and I can further explain. 

### Code
I have uploaded my notebooks that I used to create my predictions and findings.  I have also summarized it all in the slide deck.  Time was being crunched at the end, so some things may be out of order.  

### Findings
Random Forest resulted in the highest accuracy and using GridSearchCV is how the best hyperparameteres were found.  Being in shotgun was the most important feature for predicting whether the play was a run or pass - passing the ball over 80% of the time in shotgun.  

### Recommendations
In hindsight, the Vikings should have ran the ball a lot more in 2018, given personnell and being less predicatable.  They passed the ball when they had to, not when they wanted to and this resulted in a preditable offense that was not tough to defend - even with playmakers on that side of the ball.

