# Caesar Cipher

This project is not as popular as the other two (sentiment analysis, machine translation) but is the funnest in my opinion. Cipher is a jargon in crytography for an algorithm for performing encryption or decryption. The caesar cipher is one of the most famous cipher for its simplicity as it is basically shifting the alphabet by a certain number of positions. 

Instead of building a 26 case switch, I chose to preprocess the texts then train it on a network with GRU (64 units) and a time distributed dense layer. Sorry Occam.

## Procedures

1. Load data
2. Tokenize all sentences to char level
3. Post pad all sequences to maxlength
4. Build model (GRU + Dense)
5. Convert output logics back to text

## Performance

2.5 mins of training yielded 96% accuracy.

## Dataset

Dataset from Udacity, contained in the repo.