# British_Airways_Forage
Virtual Internship from the theforage.com

1. Task - 1 : Data Acquisition and Finding 
    1. Web Scraping from skytrax
       * Data collection from a third-party website https://www.airlinequality.com/airline-reviews/british-airways
           * Used requests library to acquire the data in HTML foramt
       * Parsed the HTML content
           * Parsing refers to the process of analyzing the structure and content of the HTML document, parser identifies various elements such as tags, attributes, text content,
           * Parsing done using beautifulsoup library
             
       * Saved the relevant info in a csv file format
       * The obtained dataset is as below
         ![image](https://github.com/Cokaine2912/British_Airways/assets/97113663/8858069d-8998-410e-b07a-d9a4478a7d82)


    2. Data Cleaning 
       * Not much of cleaning needed as there were no missing values and features were not as such that would bring in outliers
      
    3. Initial Analysis / a glance onto the reviews 
       * Employed a Word-Cloud using the wordcloud library to get and idea an idea of what all things are passengers talking about. 
       * Added stopwords which will restrict the common inconclusive words and also also added a few manually by performing few iterations of word cloud.
       * By looking the wordcloud, depending on the word size we can infer what all words and how frequently are they mentioned by the passengers. 
    4. Distribution of Rating and Sentiments
       * Plotted a histogram showing distribution of ratings from 1 to 10 to get an idea of the ratings 
       * Divided the ratings in positive, neutral and negative.
    5. Sentiment analysis from reviews text
       * I did this basically to see whether the sentiments coming from the ratings go hand in had with the sentiments inferred from the text that they have written
       * Used Python's Textblob library to study sentiments from text
    6. Word frequency with N_gram
       * This shows how frequenlty certain words have occured together and plotting N_grams for different sentiments I can understood that what the people are complaining about similarly what are they loving.
      
    7. Topic Modelling
       * Lastly I performed topic modelling with LDA which gives an idea about the theme of the text corpus
       * while word frequency with N-grams focuses on the occurrence and frequency of specific words or phrases, topic modeling delves into the underlying themes or topics within a text corpus. Word frequency provides a quantitative perspective, whereas topic modeling provides a qualitative and thematic perspective.
  

