# Arcana-Analytics Hackathon
Public Sentiment Prediction(StockTwits tweets) and Co-occurrence of stocks in tweets


### Installation 
Use the following command to clone the repository
```
git clone https://github.com/McMafia/Arcana-Analytics.git
```

### Downloading the correct package versions
Use the following command to install the correct package versions after creating a virtual environment
```
pip install -r requirements.txt
```

## Usage
The program is easily executed by running the main.py file from the repository. This file when successfully executed, opens a streamlit webapp. We have used the latest posts available on the website stocktwits.com to predict general sentiment about the stock, and compare it with the actual sentiment we calculated using the tags on each of the available post. The app also provides the user with the information about the co-occurence of a particular chosen stock, with the other stocks present in the dataset which will help the user to be alert about the other market factors that might affect the performance of their chosen stock.

### Running the program
To run the program, enter the directory where the repository has been cloned and run the following command.
```
streamlit run main.py
```
## Interpreting the results

The co occurence graph shows the number of posts in which the selected stock and another stock have been mentioned.
The sentiment analysis graph provides the overall sentiment of the general public on the selected stock through time. The score of 1 being a completely 'bullish' sentiment and the score of 0 being completely 'bearish' sentiment.
Please see the Presentation ppt for more details
