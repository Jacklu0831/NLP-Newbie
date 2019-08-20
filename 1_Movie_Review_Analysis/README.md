# Movie Review Analysis

Binary classification with LSTM in just ~30 lines with Keras (TF backend). Tackling the classic problem of sentiment analysis. It is amazing how fast the deep learning frameworks have evolved for amateurs to quickly get results and even experienced developers to break into new grounds in AI.

## Procedure

1. Get data
2. Peek at data (print out examples)
3. Pad sequences
4. Build RNN model (32 embeddings -> LSTM -> dense)
5. Training (with train-valid split)
6. Test performance

## Performance

After training 5 epochs training on 24936 samples (~40 minutes), the final accuracy is 0.87016. Of course, more data and deeper network could be used to improve the performance. However, it would be a much better usage of my time to study newer techniques like attention, transformer, or the newest pervasive attention (2D conv) to drastically improve both the performance and efficiency of my NLP models.

## Dataset

Large Movie Review Dataset (since it's "large", I did not include it in the repo), download it [here](http://ai.stanford.edu/~amaas/data/sentiment/). Or simply get the Keras built-in version [like I did](https://github.com/Jacklu0831/NLP-with-RNN/blob/master/1_Movie_Review_Analysis/rnn_sentiment_analysis.ipynb), which also avoids having to clean the data.