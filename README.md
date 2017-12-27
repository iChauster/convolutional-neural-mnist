# convolutional-neural-mnist
## tensorflow x python3 x cnn

Used Tensorflow with guidance to create an mnist model off a number data set (https://pjreddie.com/media/files/mnist_train.csv ).

The model created after 30 minutes of iteration (around 8000 iterations) is 97.35% accurate in classifying numbers.

This series on the basics of Neural Networking also helped me a lot : https://youtu.be/aircAruvnKk

## use

download datasets from the link, make sure you `pip install tensorflow`

use `python3 train.py` to train - it will finish after 10k iterations

you can also visualize the training process on localhost
`tensorboard --logdir=graphs/ --port=6006` (it will appear in localhost on your browser)



