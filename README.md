# YouTube-Comment-Sentiment-Analysis-Python-Bot

For the PROS Hackathon 2018, I wrote a Python Bot that utilizes YouTube's Data V3 API to parse the comments of any YouTube video given a unique video id into a CSV file. Next, I utilized the NLTK Python Library along with the Vader Lexicon to rank each comment based on sentiment. 

From the original repository, **"Our assignment was to “Develop a B2B pricing solution that can leverage competitor prices based upon pricing data repositories, screen-scraping tools, indexes, or other data sources in dynamic and sustainable manner.”** Our solution was two-pronged, consisting of a machine learning based estimator and a sentiment analyzer. Our estimator estimated the market valuation of a product based on technical features of the product. Our sentiment analyzer parsed YouTube review video comments to determine public sentiment of a brand. This assigns a measurable value to the online research process that consumers (especially millenials) carry out before making a purchase. We connected this backend to a React frontend, via a Flask REST API."

Our Hackthon team chose to analyze the camera industry. This bot was integral in analyzing our chosen industry because it provided Real Time User Sentiment and Dynamic Feedback on our product. Additionally, this bot can potentially allow a business to make dynamic pricing decisions based on competitor pricing and supplementing our price estimator. 

I have provided two products to the potential end customer. The first product is the main.py bot which allows the customer to enter a specific video id and analyze it's sentiment distribution. The second product is the loop.py bot which allows the customer to run the bot on a database of video ids in order to gain insight on a larger scope of videos. Lastly, I have provided some example data visualizations for few specific cameras that we analyzed using this bot. 

# Technologies Used
* Frontend: ReactJS
* Backend: Python, Natural Language Toolkit Library, Flask, Scikit-Learn, YouTube Data V3 API
