# NLP-using-python
# The main agenda of this is to classify two types of SMS i.e SPAM and HAM. Spam refers to a spam SMS and vice versa.
# Text preprocessing is done using string function. String function is used to remove strings from the text
# Tokenization is done with a custom defined function. It applies the string function, joins the charcters on wide space and removes the stop  words
# TFIDF of bag of words is created using tfidf transformer function
# Machine learning models are applied on the data after splitting
# for simplicity applied multinomial NB model
# second NLP challange is dealt with neural networks.
# The challange is to classify the ratings of the drug, high or low based on the previously genrated corpus
# Used convolutional networks
# Third challange is to classify sms into ham,spam and info.
# Third challange is dealt using Reccuring nueral netwroks
# First step is tokenixing the data using tokenizer function from keras, pad sequence function to maintain equal document length
# dummifying the labels in the target
# LSTM is applied along with an embedding layer which produces an output of equal length.
# Embedding layer helps in intializing the learned weights instead of randomly intializing the weights as in normal neural networks.
