# AWStest

This is a submission for the 48 Hr Hackathon Aifinity hackathon using AWS resources (Sagemaker, S3)

Due to the increasing number of emails that people receive (customer service, personal, etc), our team has came up with the solution to label emails.

This label is inspired by the Urgency Importance Matrix, to find emails which needs to be attended to and find emails which can be given automated responses (for customer service).
This will be built above the spam filter, which is a popular solution arising from text classification.

This solution is done using text classification (HuggingFace) and the pre-trained model is used on Sagemaker.

Our team attempted to use a Sentiment Analysis model, and NLTK library to preprocess the data.
