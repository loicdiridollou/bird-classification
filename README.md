# bird-classification
Building a neural network to identify birds

The idea of this project is to play with a 200-specie dataset from Kaggle to identify the specie of a bird from an unseen image.
There are two types of training in this project. The first one was to start from a blank sheet and try to train it, we are reaching a poor performance with this model. The second one was to use a pretrained model and do some transfer learning to apply the model to our dataset. We have chosen to use the ResNet18 from PyTorch to complete this task.

#### Inputs

The model takes as input an image of a bird.

#### Outputs

The model will output the guessed specie of the bird.
