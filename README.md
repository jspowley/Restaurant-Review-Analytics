# Restaurant Review Analytics

A restuarant review analytics workflow which scrapes the data directly from the source site, prepares the review text into an ML ready format, by vectorizing it into 50 dimensions, and then uses the preprocessed information to train a classification ML model.

Applying clustering to the vectorized word model, we were also able to make a glossary of terms which was self defined by the code, in this case relating to drinks and drinking. This allowed us to prove people are talking about drinks less over the last 10 years, without having to be experts on all varieties of alcohol and beverages available. By clustering a word vector model, you can track a topic without having to manually engineer a comprehensive list of all related vocabulary, which is particularly helpful when trying to make sense of unstructured data.

This project demonstrates many of the stages in a data pipeline, from collection and preprocessing, exploratory data analysis, model fitting, and evaluation. End applications include advanced filters for managers wishing to know where their restaurants can improve, promotional offers through the restaurant review site, and identifying the market saturation for specific sub-markets.

