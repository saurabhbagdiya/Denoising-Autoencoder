# Denoising_ConvolutionAutoEncoder
Denoising Convolution AutoEncoder on mnist


## Data 
Mnist dataset from keras.datasets

## Model
- Autoencoder, a deep neural network is implemented with Keras functional API.
- Input to model is noisy image and output is the same image without noise.
- Filter size is 16 followed by 32 and latent dimesion is 16 units.
- The loss function for training is mse.

## Result
You can download the pre-trained weights from here <br />
https://drive.google.com/open?id=1KmnNJM29HADuNUIIM8MxNmDfkM9wTDgN

#### Input <br />
![](https://github.com/TanyaChutani/Denoising_ConvolutionAutoEncoder/blob/master/noisyA.png)<br />

#### Output <br />
![](https://github.com/TanyaChutani/Denoising_ConvolutionAutoEncoder/blob/master/outputA.png)<br />
