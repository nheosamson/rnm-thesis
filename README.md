REDDIT

Install all requirements from requirements.txt before proceeding to running the code.

There are two notebooks under the Reddit Directory:
1. PRAW-TESTER: Responsible for scraping data from the identified subreddit (r/Coronavirus_PH) using PRAW
2. Reddit LDA: Responsible for the data preprocessing, tokenization, cleaning, and creating LDA model with the identified terms.


Instructions
Explanation and description for each step of the code can be found in each notebook.

For PRAW-TESTER.ipynb
** Note: the raw data is already available under the file Reddit/PRAW resources/TESTER-reddit_data.csv, so proceed as follows: 

[1] To test out the scraping code, proceed with option 2.1 
[2] If you'd like to skip the scraping part, proceed with option 2.2

1. Run the PRAW-TESTER.ipynb to access the Reddit app initialization to allow for data scraping
2.1 run the data scraping part which is currently commented out
2.2 run the code block under 'RESUME'

The final output for this part should be a filtered dataframe which only includes
- data from 09-01-2021 to 05-28-2022
- not only limited to comments under posts made on this period



For Reddit LDA.ipynb
1. There are no extra configurations needed for this code.

GOOGLE TRENDS

This contains 2 notebooks

scrape-google : scraping data from the Google Trends API
rnn: Running RNN on the GT/scraped Reddit data

