# Least Square Adversarial Autoencoder
# Abstract
This research introduces least square adversarial autoencoder (LSAA)-an autoencoder that is able to reconstruct data and also generate data that has characteristics similar to data distribution from the prior distribution. LSAA uses least square generative adversarial network loss function on its discriminator. LSAA minimizes Pearson χ 2 divergence between the latent variable distribution and the prior distribution. In this research, a Python program is developed to model LSAA by utilizing MNIST data set and FashionMNIST data set. The program is implemented using PyTorch. All of the programming activities are carried out in the cloud environment provided by the Tokopedia-Universitas Indonesia AI Center, using DGX-1 (GPU Tesla V100) as its computing resource. The experimental results show that the mean squared error of LSAA for MNIST data set and FashionMNIST data set are 0.0080 and 0.0099, respectively. Furthermore, the Fréchet Inception Distance score of LSAA for MNIST data set and FashionMNIST data set are 11.1280 and 27.5737, respectively. These results indicate that the least square adversarial autoencoder is able to reconstruct the image properly and also able to generate images similar to the training samples.
# Link
[Link to the paper](https://www.researchgate.net/publication/344516945_Least_Square_Adversarial_Autoencoder)
# Algorithm
![alt text](https://github.com/MarshalArijona/CLUB--Generative-Network/blob/main/algorithm.PNG?raw=true)
# Result
![alt text](https://github.com/MarshalArijona/CLUB--Generative-Network/blob/main/reconstruction.PNG?raw=true)

![alt text](https://github.com/MarshalArijona/CLUB--Generative-Network/blob/main/fid.PNG?raw=true)

![alt text](https://github.com/MarshalArijona/CLUB--Generative-Network/blob/main/generated mnist.PNG?raw=true)

![alt text](https://github.com/MarshalArijona/CLUB--Generative-Network/blob/main/generated fashion.PNG?raw=true)
