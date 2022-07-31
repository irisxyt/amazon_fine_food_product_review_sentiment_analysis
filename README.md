# Amazon_fine_food_product_review_sentiment_analysis

dataset is from https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews

# text mining for customer reviews analysis by Implementing sentiment Analysis and Topic Modeling

### Sentiment Analysis: 
 - VADER Lexicon: In Sentiment Analysis, we use VANDER Lexicon because it can clearly shows the polarity and intensity (‘compound’ score), which enable us to determine the weights of positive, negative and neutral  opinions. Then we can test the accuracy with ‘score’ as actual polarity. If the accuracy is not satisfied, we can fine-tune by adjusting the threshold parameter.
 - After getting the sentiment score, we created three subset of 'pos','neu' and 'neg'. 
### Topic Modeling：
  - LDA Function: After getting three subset, we used topic Modeling with LDA function. We can find the frequently mentioned labels and the dominant topic by displaying the top N words by comparing the coherence, perplexity and log likelihood scores.
  - We can get the key features in each of three subsets and explain the difference and propose improvement suggestsions.
