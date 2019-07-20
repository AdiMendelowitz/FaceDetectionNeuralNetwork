# Face Classifier

##### This convolutional neural network (CNN) is constructed in VGGNet architecture.
##### The neural network classifies a png image as a valid or invalid photo of a face.
##### The VGGNet architecture was chosen for its excellent feature recognition.

## What the code does
- Imports all frameworks and datasets
- Oversamples "good" dataset and undersamples "bad" dataset to balance set sizes
- Splits data into 80% training and 20% test sets
- Trains the model
- Computes loss
- Tests model on 20 randomly selected images from entire dataset


## This repo contains the following
- Jupyter notebook
- Trained model 
- Model weights
- Dataset

## Frameworks used
 - Keras
 - TensorFlow
 - NumPy
 - scikit-learn
 - Pillow
 - glob

## Why VGGNet?
> VGGNet has the best results on VOC 2007, 2012 and Caltech 256 dataset. And it also has competitive result on Caltech 101 dataset.

For further reading see: [Review: VGGNet — 1st Runner-Up (Image Classification), Winner (Localization) in ILSVRC 2014](https://medium.com/coinmonks/paper-review-of-vggnet-1st-runner-up-of-ilsvlc-2014-image-classification-d02355543a11)

## Example images
* Images with faces:
![Good1](good1.png.png?raw=true "Good 1")
![Good2](good2.png.png?raw=true "Good 2")
* Images without faces:
![Bad1](bad1.png.png?raw=true "Bad 1")
![Bad2](bad2.png.png?raw=true "Bad 2")
 
### Todos
 - Train model on larger dataset
 - Add more layers to NN

License
----
MIT
