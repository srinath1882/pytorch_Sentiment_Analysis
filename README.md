# pytorch_Sentiment_Analysis
Sentiment Analysis of IMDB Dataset using Pytorch

Reference [Notebook](https://github.com/bentrevett/pytorch-sentiment-analysis/blob/master/2%20-%20Upgraded%20Sentiment%20Analysis.ipynb)

Implementation changes from above Notebook

1. 3 seperate LSTM layers

2. Used a for loop to do so in the forward function

3. Trained on the text that is reversed (for example "my name is Rohan" becomes "Rohan is name my")

4. Achieves 87% or more accuracy
