# csc516-final-project

This is a repository for an experiment conducted with the CTU-13 dataset,
which uses real traffic data to record instances of normal, botnet, and background activity.

This experiment had the goal to train 3 different machine learning models to detect botnet activity in a veriety of ways.

Part 1 of this experiment can be found under project/test_models.ipynb
This part of the experiment aimed to see how well the models would perform on traditional train/test splits of the scenarios they
were trained on.

Part 2 of this experiment can be found under project/test_on_rest.ipynb
This part of the experiment aimed to see how well the models could adapt to data and scenarios they had not been trained on.
The three previously trained models were tested on the rest of the scenarios.

Part 3 of this experiment can be found under project/test_on_background.ipynb
This part aimed to determine how freshly trained models would react to background data when it had not 
preivously been exposed to it.

Each part of the experiment are captured using Jupyter Notebooks, with the results captured in metrics, plots, and graphs
using sklearn, matplotlib, and seaborn.

Credit for the dataset:
"An empirical comparison of botnet detection methods" Sebastian Garcia, Martin Grill, Jan Stiborek and Alejandro Zunino. Computers and Security Journal, Elsevier. 2014. Vol 45, pp 100-123. http://dx.doi.org/10.1016/j.cose.2014.05.011
