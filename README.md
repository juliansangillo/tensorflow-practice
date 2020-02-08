# tensorflow-practice
Practice programs on using tensorflow

## img-practice.py - uses img datasets from keras to train a neural net to classify the images. 
When run, it will train the model, then display five different images in order and give the actual classification ond the
classification predicted by the AI.

## txt-practice.py - trains a neural net to classify movie reviews as either positive or negative.
These reviews were taken from the keras imdb dataset and used for training and testing.

## txt-practice2.py - uses the same code for training a model as txt-practice.py, except this model is now saved to memory to
prevent the training process from repeating every execution. The model is saved to txt-model.h5. After loading the saved model,
it will classify the 5 star movie review taken from imdb which is stored in txt-review.txt.

## txt-model.h5 - saved tensorflow model from txt-practice2.py.

## txt-review.txt - text file with a 5 star movie review from imdb used for testing in txt-practice2.py.
