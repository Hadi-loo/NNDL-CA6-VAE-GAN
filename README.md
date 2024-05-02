# NNDL CA6 - VAE & GAN

## Project Description

This project is a part of the Neural Networks and Deep Learning Course. The project is about the implementation of the Variational Autoencoder (VAE) and the Generative Adversarial Network (GAN). The project is divided into two parts.

### Control VAE

The first part is about the implementation of the Control VAE model. The Control VAE model is a variant of the Variational Autoencoder (VAE) that is used for disentangled representation learning. The model is trained to learn a good representation of the input data that is disentangled into two parts: the content part and the attribute part. The content part represents the shared information between the data samples, while the attribute part represents the specific information of each data sample. The model is trained to learn the content part in an unsupervised manner and the attribute part in a supervised manner. We are going to use the Control VAE model on dSprites dataset. The dSprites dataset contains 737,280 samples of 2D shapes. Each sample contains 6 features: shape, scale, orientation, x position, y position, and color. 

### Generative Adversarial Network (GAN)

The second part is about the implementation of the Generative Adversarial Network (GAN). The GAN model is a generative model that is used to generate new samples from a given distribution. The model consists of two parts: the generator and the discriminator. The generator is trained to generate new samples that are similar to the real samples, while the discriminator is trained to distinguish between the real samples and the generated samples. The model is trained in an adversarial manner, where the generator tries to fool the discriminator and the discriminator tries to distinguish between the real and generated samples. We are going to use the GAN model to generate new samples of hand-written digits similiar to MNISt dataset.  
We have implemented basic GAN, Wasserstein GAN (WGAN), and Self-Supervised GAN (SS-GAN) models.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
