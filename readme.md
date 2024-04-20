# <h1 align="center">**DCGAN**</h1>

<p align="center">
<img src="images/image_readme.png"> 
</p>

This repository is dedicated to the implementation of [Deep Convolutional Generative Adversarial Networks (DCGAN)](https://arxiv.org/pdf/1511.06434.pdf), a specialized variant of GANs that replaces dense layers with convolutional and transposed layers. By employing convolutional layers in both the discriminator and the generator, DCGANs can effectively capture the spatial features inherent in images, leading to the generation of higher quality images. Furthermore, the use of convolutional layers allows DCGANs to handle high-resolution images more efficiently. Compared to standard GANs, DCGANs tend to be more stable during training, thereby facilitating model convergence.

## **Components of a GAN**

- **Generator:** Its role is to create "fake" images that resemble real images used in training. During the training process, the generator continually strives to deceive the discriminator, consistently improving the quality of the forgeries it produces. Balance is achieved when the generator is able to generate perfect forgeries that are indistinguishable from the real images used in the training dataset.

- **Discriminator:** Its task is to determine whether a given image is real or a forgery generated by the generator. During training, the discriminator is trained to be a more effective "detective," learning to properly classify images as real or fake. Balance is achieved when the discriminator cannot distinguish between real images and those generated by the generator, and therefore, always has a 50% probability of determining whether a given image is real or fake.

## **Used Datasets**

- **Anime Faces**: Dataset containing 63,565 color images of [anime faces by MckInsey666](https://github.com/bchao1/Anime-Face-Dataset).

- **Fashion-MNIST**: This dataset consists of 70,000 grayscale images representing clothing items, distributed across 10 different categories.

- **MNIST**: This dataset consists of 70,000 grayscale images of handwritten digits ranging from 0 to 9.

- **Sign language**: This dataset includes 27,455 grayscale images representing human hands making gestures of sign language.

## **Implementations in TensorFlow and PyTorch**
Implementations have been done in both TensorFlow and PyTorch, the two most widely used frameworks in Deep Learning, to explore the capabilities of DCGANs. Each implementation provides insights into the differences and similarities between these frameworks, offering practical perspectives for professionals in the field.

## **Generated Examples**

<div style="display: flex; justify-content: center;">
    <div style="display: flex; justify-content: center; max-width: 800px;">
        <img src="images/anime_faces_dcgan/anime_faces_dcgan.gif" style="width: 400px; margin-left: -100px;">
        <img src="images/fashion_mnist_dcgan/fashion_mnist_dcgan.gif" style="width: 400px; margin-left: -100px;">
    </div>
</div>

<div style="display: flex; justify-content: center;">
    <div style="display: flex; justify-content: center; max-width: 800px;">
        <img src="images/mnist_dcgan/mnist_dcgan.gif" style="width: 400px; margin-left: -100px;">
        <img src="images/sign_language_dcgan/sign_language_dcgan.gif" style="width: 400px; margin-left: -100px;">
    </div>
</div>

*You can observe how generation improves as epochs progress.*

## **Technological Stack**
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=101010)](https://docs.python.org/3/) 
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white&labelColor=101010)](https://www.tensorflow.org/api_docs)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white&labelColor=101010)](https://pytorch.org/docs/stable/index.html)
[![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white&labelColor=101010)](https://plotly.com/)

## **Contact**
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=101010)](mailto:jerson.gimenesbeltran@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=101010)](https://www.linkedin.com/in/jerson-gimenes-beltran/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=101010)](https://github.com/JersonGB22/)
