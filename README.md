##LaTextGAN 

## Requirements
* **PyTorch r1.1.0**
* Python 3.5+
* CUDA 8.0+ (For GPU)

## File
* train_ae.py: This file trains the autoencoder.
* dataset.py: This file prepares the data. Mention the name of the input file.
* models.py: Contains all the models.
* train_gan.py: This file trains the GAN.
* test.py: This file generates synthetic data.

## Instructions to run the programs
* In dataset.py dataset file name should be mentioned
* Use the following commands: 
* python train_ae.py
* python train_gan.py
* python test.py