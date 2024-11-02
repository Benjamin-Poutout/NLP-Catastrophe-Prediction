# Catastrophe Tweets Prediction Kaggle Competition

Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

But, it’s not always clear whether a person’s words are actually announcing a disaster. Take this example:

" On the plus side LOOK AT THE SKY RIGHT NOW IT WAS ABLAZE "

The author explicitly uses the word “ABLAZE” but means it metaphorically. This is clear to a human right away, especially with the visual aid. But it’s less clear to a machine.

We are challenged to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t. You’ll have access to a dataset of 10,000 tweets that were hand classified.

To efficiently run this notebook, you can go on google colab and run the different cells. Note that to be able to fine-tune LongFormer, you'll have to set your environment to T4 GPU.

Once it is done, make your own tests if you want and improve the predictions.
