# Airbnb Australian Market Analysis

## Justification/Background 

Vacation rentals, also called short-stay rentals, are booming in Australia. Lots of us have used or at least know someone has used vacation rental apps like Airbnb, HomeAway, etc. Melbourne was announced as [6th](https://www.businessinsider.com.au/heres-how-big-airbnb-is-in-sydney-and-how-it-compares-to-the-rest-of-the-world-2016-5) on the list of top ten cities for users globally in 2016 and has been one of the top cities for listings globally since then. 

As a data analyst who also travells and hosts on Airbnb, I wanted to know what the market looks like in Melbourne and Australia, how other hosts are doing, the most popular locations, amentities and so on.

## Melbourne Market Analysis

I started with analyzing the data of listings in Melbourne. From Aug 2018 to Jul 2019, I found that:

- Steady supply: every month there were around 20K+ listings hosted by 14k+ hosts with an average price A$150 across 250+ suburbs in Melbourne.
- 90% of the listings accommodate within 6 guests and 1 house in Melbourne can accommodate 21 guests.
- 83% hosts have only 1 listing, while professional hosts can manage more than 100 listings.
- 4% hosts are international and hosting from outside Australia.
- If we put the hosts into *year groups* based on since which year they had started hosting, the average review scores of all hosts in the year groups decreased by 0.05/5.00 each year.
- More interesting findings..

## Discover Sentiment in Airbnb Reviews

Analyzed sentiment in reviews using tf-idf (term frequency–inverse document frequency) matrix and NMF (non-negative matrix factorization) analysis.

Found that:
- Most of the reviews have a positive sentiment.
- Most complaints are about cancellation.

## Links to Notebooks and Visualizations

[Analysis Notebook on Kaggle](https://www.kaggle.com/tylerx/melbourne-vacation-rental-market-analysis)

[Discover Sentiment in Airbnb Reviews](https://www.kaggle.com/tylerx/discover-sentiment-in-airbnb-reviews)

[Interactive Power BI Visualization](https://app.powerbi.com/view?r=eyJrIjoiYjZjNmZiMzAtYzQ4OC00ODNjLThiMzctODI1NGRhODFmZDgyIiwidCI6Ijc4ZWRhMzM0LWU5MTctNDQzNS1iMjM1LTg1OGI3MjFlY2ZmMSJ9&pageName=ReportSection3655a29acb3c0494a39e)
<iframe width="800" height="600" src="https://app.powerbi.com/view?r=eyJrIjoiYjZjNmZiMzAtYzQ4OC00ODNjLThiMzctODI1NGRhODFmZDgyIiwidCI6Ijc4ZWRhMzM0LWU5MTctNDQzNS1iMjM1LTg1OGI3MjFlY2ZmMSJ9" frameborder="0" allowFullScreen="true"></iframe>

[Detailed description of the dataset also on Kaggle](https://www.kaggle.com/tylerx/melbourne-airbnb-open-data)

## Next 

I'll analyze other major markets in Australia including Sydney, Brisbane, etc., and then analyze the overall Australian market.
