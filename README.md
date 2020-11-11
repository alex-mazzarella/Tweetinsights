# Tweetinsights
My first Data Science project. Created as the capstone project while at the BrainStation Data Science bootcamp.

Please take the time to read this ReadMe description, it will help you understand the structure of the repository.

---
## DATA

Before reviewing any notebook, please download the 2 data folders named 
- "master_tweets"
- "net_tweets_pulled"

from this link
https://drive.google.com/drive/u/0/folders/1QXzj1p9TrpT7Tna1W6BWD81TJstpULrR

and save them (unzipped) inside "final-Twitter API".

NOTE: the folder 
- "xbox_tweets_pulled"
can also be downloaded from the link above, however it is not used in this
analysis.

---

---

Here you can find the basic information about the files 
included in the folder "final-Twitter API".

For this project, I have used the following:
* Jupyter Notebook (5+1)
* Tableau (1 file)

I have also included a text document with the environment variables.
For a more detailed description, see below.

---

Please follow this order when reading the notebooks:

- 01_A_ScrapingTweets(xbox_netflix)
tweets collection from Twitter API. As the initial plan was to compare
two brands, I collected tweets for Netflix and Xbox. I have then changed
the scope of the analysis, therefore the in following notebooks I am not
using the Xbox tweets.

- 02_EDA_Netflix
data cleaning and exploration steps.

- 03_Text_preprocessing-LABELLING-Netflix
sentiment analysis

- 04_Text_preprocessing-TOPICS_LDA_SKLEARN-Netflix
topic extraction using LDA from scikit-learn

- 05_Text_preprocessing-TOPICS_LDA_GENSIM-Netflix
topic extraction using LDA Multicore from Gensim

ADDITIONAL NOTEBOOK:

- 01_B_ScrapingTweets(only-one-brand)
since as anticipated I performed the analysis with only one brand, 
I have also created a version of the scraping tweets code 
for one brand only. Although this is not used in the analysis, I thought
it might be useful for future explorations

DASHBOARD:
-"Tweetinsights_final.twb" inside the "tableau_visualizations" folder


ENVIRONMENT:

- alex_m_capstone_env.txt
text file including the details of the environment used for this project


FOLDERS:

- brand-name_tweets_pulled
not used for the project. created only to test that 
01_B_Alex_Mazzarella_ScrapingTweets(only-one-brand)
would correctly collect and save the tweets in a csv

-data
containing dictionaries and files used for the tokenizer function

- lda_vis
LDA visualizations saved in html format

-master_tweets
since during the data collection multiple csv were generated,
this folder contains the concatenated tables, before (raw) and 
after (clean) cleaning

- net_topics
saved results of hyperparameters optimization
(only used for data backup, not utilized
for the scope of the analysis)

- net_tweets_pulled
CSVs with data collected from Twitter API

- tableau_visualizations
tableau file "Tweetinsights_published.twb" and data used for the dashboard

- vader_lexicon
coprora-wordnet files

- xbox_tweets_pulled
the tweets collected for Xbox (not used in the analysis)



Please reach out to me via slack or linkedin
( https://www.linkedin.com/in/alex-mazzarella-yvr/ )
if you have any questions.


Thank you,
Alex
