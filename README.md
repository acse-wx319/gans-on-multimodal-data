# ACSE Independent Research Project

## Regression Modelling with GANs

<img width="825" alt="Screen Shot 2021-08-16 at 2 55 51 PM" src="https://user-images.githubusercontent.com/6519391/130759873-b29b48b6-86ca-4e15-b476-e0cb869e8577.png">

![real9999](https://user-images.githubusercontent.com/6519391/130760025-1a1f6bff-5498-4e0d-9ccd-793653cf1ebb.jpg)
![fake9999](https://user-images.githubusercontent.com/6519391/130760018-abdf702b-4757-4be2-a00f-359652303cb3.jpg)

![real19999](https://user-images.githubusercontent.com/6519391/130760161-25b716f6-d40c-4b07-926d-45c79c483bf1.jpg)
![fake19999](https://user-images.githubusercontent.com/6519391/130760148-00db75c5-f264-4c8d-aaeb-61502563c90f.jpg)



## Dependencies
PyTorch 1.8.1     
Scikit-learn 0.24.2      
Pandas 1.0.5      
Matplotlib 3.2.2      

## Usage
### Synthetic Data
Specify the required parameters as described below. Input data will be automatically generated.     

Parameters:
  - gp, sn: Whether to apply gradient penalty and/or spectral normalization.
  - train: Whether to train a GAN or load a pre-trained one.
  - fixed_input: Whether to produce fixed-input predictions.
  - eph: If not training, specify the epoch of model to load.
  - DATASET: Which synthetic data to use (sine, moon, 2spirals, circle, helix).
  - suffix: Output version.
  - LATENT_DIM: Input latent space dimension for generator.
  - DIM: Hidden layer dimension for generator and discriminator.
  - LAMBDA: Penalty factor for gradient penalty method.
  - DROPOUT_RATE: Dropout rate for generator.
  - lr: Learning rate for GAN.
  - CRITIC_ITERS: How many critic iterations per generator iteration
  - BATCH_SIZE: Size of mini batch.
  - ITERS: Total number of epochs.
  - log_interval: How frequent to write to log and save models 
  - use_cuda: Whether to turn on use_cuda


### Time-series Data

## License
Distributed under the MIT License. See LICENSE for more information.

## Contact
Wenjie Xu wenjie.xu20@imperial.ac.uk

