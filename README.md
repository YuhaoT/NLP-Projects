# NLP-Projects

## [Text Classification](https://github.com/YuhaoT/NLP-Text-Classification)
Extracting headline from Wikipedia by using regex with an text-extractor provided by instructor(code for text-extractor not include), then do a frame detection on it. Naturally, frame detection can be viewed as a text classification task, where the text are the news headlines and the classes/categories are the frames. We will take this approach to try and predict the news headlines. I implement Logistic Regression and Naïve Bays for it, and also write my own code to calculate the accuracy in our_metrics.py
## [Text Similarity](https://github.com/YuhaoT/NLP-Text-Similarity)
Given a set of words, return words that are similar with them. I also implemented three type of vector embedings(term-context, term-document, and word2vedc) along with PPMI weighting(Positive Pointwise Mutual Information) and tf-idf weighting. Besides cosine similarity, I implemented jaccard similarity and dice similarty function to see, which one could return a result that is more similar with the orginal words set.
## [Recurrent Neural Network](https://github.com/YuhaoT/NLP-RNN)
I used Pytorch to build a RNN(Recurrent Neural Network) which classified 27,000 city name by 9 countries with accuracy about 48%. I also built a character-level RNN to generate sentences from Donald Trump’s speech.
## [Name Entity Recognition](https://github.com/YuhaoT/NLP-Named-Entity-Recognition)
Through exploring 17 features from words in sentences, I implemented a Name Entity Recognition System with conditional random field model to classify name entities in Spanish corpus with accuracy (F1-score) of 71.59%.
## [Emoji Prediction](https://github.com/YuhaoT/NLP-Emoji-Prediction)
By using TF-IDF vectorizer and swap the Spanish emoji index so that the same emoji have the same index for English and Spanish, I built machine learning classifiers that can predict the most possibly associated emoji in a tweet based on 90,000 English tweets and 19,000 Spanish tweets. I also tried to translate Spanish to English and combine the data to see whether the new translated data combined with the original English data as a train set to see whether increas the size of train set could increase the accuracy.
