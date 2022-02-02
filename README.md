# Binary-and-multi-class-classification

𝗢𝘃𝗲𝗿𝘃𝗶𝗲𝘄

Web scrapping of a web page consisting of new articles snippets of various different categories was done to extract snippet, title and category. Only three categories were selected books, film and music. This data was stored in a text file and further processing was done.

𝗧𝗮𝘀𝗸 𝗰𝗼𝗺𝗽𝗹𝗲𝘁𝗲𝗱

• Text mining
Beautiful soup 4 was used to parse through all the pages of the given website and it was stored in a text file on the local system.

• Text pre-processing
Stop words such as '𝘵𝘩𝘦,𝘢𝘯, 𝘢𝘯𝘥,𝘢,𝘰𝘧,𝘧𝘰𝘳' were removed, words which had frequency of less than 5 in the corpus were removed. Along with this lemmatization was used to understand the common root words.

• Binary classification
At a time only two categories were given to a linear model. This model was trained with randomly split training data set and then tested with the test data. The check the results accuracy and confusion matrix were displayed. For SDGC classifier 90% accuracy was obtained.

• Multi-class classification
For multi-class all the three categories were given to the model and similar process as above was followed. An accuracy of 88% was obtained when SDGC classifier was used whereas logistic regression model only gave an accuracy of 86%
