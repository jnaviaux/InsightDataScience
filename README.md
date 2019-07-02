# InsightDataScience
Collected work done while Health Data Fellow at Insight Data Science

Ongo_DataEngineering_FinalAnalysis.ipynb: Jupyter Notebook that reads in various data files provided by the Ongo Science team, organizes them, extracts relevant features, and outputs a probabilistic model of user retention vs time. The notebook also fits the data to a Cox Proportional Hazard model such that the efects of individual features (such as the number of posts on the app newsfeed) can be calculated on overall retention.

GooglePlayStore_workout_trainer_review_scraper: Jupyter Notebook that demonstrates how reviews were scraped and parsed from the Google Play store. The Selenium python package was used to automatically scroll through the Google Play webpage and click the "Read More" button to load additional reviews. The HTML for the webpage was loaded into BeautifulSoup for parsing, and the review text and star ratings (1-5 stars) were saved into a dataframe.

LDA_review_analysis: Jupyter Notebook reads in negative reviews (rated 1 or 2 stars) scraped from the Google Play store and categorizes them based upon their subject using a Latent Dirichlet Allocation (LDA) model
