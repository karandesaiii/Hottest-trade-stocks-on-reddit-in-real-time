# The only open-source solution that finds popular stocks on reddit in realtime

Discover stocks with popularity/momentum increase in realtime and read the best stock-specific comments.

Detects the most popular stocks (tickers) on any subreddit's discussion thread.

Similar to www.wsbdaily.com but wsbdaily.com analyzes last 24 hours, this code analyzes user-specified number of hours. (Example: last 8 hours, last 6 hours and so on). 

Any discussion thread of any subreddit can be used such as wallstreetbets daily discussions, discussions on r/stocks, r/investing etc. Just enter the URL of any relevant discussion when the notebook asks for it.

It also enables the user to view comments which talk about a particular stock sorted by the 'Best' comments first. (Reddit's BEST category evaluates comments based on upvotes, downvotes and replies - It's an overall quality score of the comment) 

# Requirements
Python 3.7+ should work ideally.

Jupyter Notebook

Reddit API credentials - Follow this blog post to get them: https://www.jcchouinard.com/get-reddit-api-credentials-with-praw/

praw 

pandas 

time

datetime

spacy
