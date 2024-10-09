# EPL_predictor
English Premier League football match predictor in Python using random forest classifier. Data was collected via webscraping from fbref.com.
Data was collected from the 2022-2023 season to the current season and the model only uses the data relevant to the EPL.
# workings.ipynb
This file contains all the workings for my project, including exploratory data analysis, feature engineering and more.
# predictor.ipynb
This file contains the final model of my project and is the file that anyone who wishes to test my model for predictions etc should use.
# scraping.ipynb
This file is the code to scrape data from the fbref.com website. Note that if using this code and changing the sleep function please be considerate to the website owner and avoid making too many requests too quickly.
# requirements.txt
Packages required to run my code.
# final_data.csv
The final dataset used to train my model.
# matches.csv
The initial dataset collected via webscraping.
# Additional
My model has a precision score of about 62.5%. This precision score is fairly low and may be improved however this could be challenging. I believe the low precision score is primarily due to
unpredictable factors inherent to football; teams often go through periods of poor/improved form, lose players and managers through transfers or injury (for players),
experience lack of funding or experience issues with the board and football (especially the EPL) is an unpredictable game. However, precision may be improved by collecting
data from more seasons to negate these issues. Other algorithms (models) could also be considered to improve accuracy. In the scraping.ipynb file, I include a sleep function to avoid being blocked by the source website for making too many requests too quickly.

