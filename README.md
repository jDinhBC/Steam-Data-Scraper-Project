# Steam-Data-Scraper-Project
Scrapes data off Steam's hardware survey website

A write-up to briefly describe
how the data is collected (10 pts),
what is the data and what information of EACH column represent (10 pts), and 
a list of questions you plan to answer with this dataset (10 pts)

Source code for option 1 or 2. You may include a Jupyter Notebook or your Python source code (40 pts) 
The dataset file in CSV format with proper index and header. (10 pts)

Data is scraped off steams gpu hardware survey website : https://store.steampowered.com/hwsurvey/videocard/

Data is Percentage of Users who use certain GPUs.

EXAMPLE:
Columns : GPU, most recent 5 months
Row : NVIDIA RTX GeForce 3070, 3.01, 6.5, 2.0, 0.51, 1.46
numbers = percentage of users with that gpu.

Questions:

What are the top 5 gpus?, the least 5? the average 5?

What gpu is gaining increasing attraction for usage?

Over the course of the 5 months what was the average delta change? 

What gpu is gaining the most increasing attraction for usage?

What gpu is losing the most attraction for usage?