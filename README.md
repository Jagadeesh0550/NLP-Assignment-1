# NLP-Assignment-1
NLP Assignment-1
This assignment is part of a nlp course at SVES. We build an n-gram model and we find the perpelxity of diffrent n-gram models.
Steps involved in building the model:
Step1: Getting the Data: By using teitter api and user_timeline() methods 50000 tweets were accessed.
Step2: Pre-processing of Data: Data has pre-processed by removing links, whitespaces, Hashtags, RTTags, @ Mentionings, additional new line characters and emojis.
Step3: Train-Test Split: After Pre-processing perform the train_test split as 90 10
Step4: Tokenization: After splitting data tokenize the train data by removing spaces and newline characters at word as well as sentence level.
Step5: Create Vocabulary: Create vocabulary by getting the word counts of each word in train data
Step6: Create n-gram model: create n-gram model for every word in train_data by adding the "<s> and "<e>" delimiters.
Step7: Calculate the probability of occurance of each word at the sentene level for different sentences.
Step8: Evaluate by perplexity: Evaluate the model by calcualting the perplexity of the model developed.
Step9: Calcualte probabilities: Calcualte the probabilities for different n-grams
Step10: Get suggestions: Given a word or a set of words get the suggestions of the words that can occur next with the repective probability.
Step11: Test the data: Apply n-gram model and calculate the probabilties and perplexties on test data
