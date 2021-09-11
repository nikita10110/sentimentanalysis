### sentimentanalysis
In this walk through i have performed sentiment analysis on IMDB reviews dataset using Pytorch and natuaral processing language. The dataset contains 50K movies reviews.
In the model i have used LSTM ***long Short term memory*** a modified version of RNN.

For sentiment analysis, firstly i have splitted the dataset into train and test. Further i have performed  tokenziation on the sentence, also i have removed the stopswords. Further i have
performed some analysis on the reviews. I found that there are some reviews whose length is less words. So, we perform embedding on then so that they meet the requirements. Further i convert the dataset into tensors and train the model. Model contains layers like embedding, LSTM, dropout etc. Further i have trained the model on the dataset.

After training, the model was able to give an accuracy of 85.68% on train and 86% on the validation/test data. Also i have found the inference of the model,  model is able  predict the unseen review and classify whether it was a positive or negative review.
