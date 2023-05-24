# Music Style Transfer

This repository contains the code and resources for the Music Style Transfer project, which aims to apply the concept of style transfer, commonly used in image processing, to the field of music. By leveraging deep learning techniques and custom neural networks, this project enables the generation of unique music compositions by blending the style of one piece with the content of another.

<img src="https://github.com/dvolynov/Music-Style-Transfer/assets/83712099/e123c5be-88ba-4dad-a9e8-f3fa2c2a9ee0" width="500">   

## Project Description

The Music Style Transfer project explores the application of style transfer techniques to the music industry. Similar to how style transfer works for images, where the artistic style of one image is applied to another, this project aims to achieve a similar effect with music. By combining the style of one piece with the content of another, we can create novel compositions with interesting blends of different musical genres and elements.  

<img src="https://github.com/dvolynov/Music-Style-Transfer/assets/83712099/bf0a7e9d-0375-4a2f-a0a6-7db7eb8069b3" width="500">   

The main focus of this project was to develop a custom neural network architecture that can extract meaningful features from audio spectrograms, which are representations of audio frequencies over time. While image-based style transfer often relies on pre-trained models like VGG-19 for feature extraction, audio spectrograms require a specialized approach.

## Main parts:

- **Audio Processing**: Converting an audio waveform to a spectrogram image using Fourier transform and separating to magnitude and phase.

- **Custom Neural Network**: The code for the custom neural network architecture, including the single convolutional layer that extracts features from audio spectrograms.

- **Loss Functions**: Implementation of the "Get content loss" and "Get style loss" functions, which measure the differences between the network's predictions and the desired outputs.

- **Training Process**: Code and documentation demonstrating the training process, showcasing how the spectrogram evolves over time to achieve the desired style transfer.

- **Audio Reconstruction**: Implementation of the Griffin-Lim algorithm and Inverse Fourier transform for converting the transformed spectrogram back into an audio waveform.

## Authors:
<img src="https://github.com/dvolynov/Music-Style-Transfer/assets/83712099/d47c666b-1e29-416c-99cf-ad0196186367" width="20"> Dmitriy Volynov<br>
<img src="https://github.com/dvolynov/Music-Style-Transfer/assets/83712099/fecdf38e-fa56-46c1-af04-761f73a62172" width="20"> Alexandr Dyakov<br>
<img src="https://github.com/dvolynov/Music-Style-Transfer/assets/83712099/1d750242-aff3-430d-9389-cd483a80de60" width="20"> Nikita Pestretsov<br>
<img src="https://github.com/dvolynov/Music-Style-Transfer/assets/83712099/c14fe25c-cc18-41b1-b452-e349b96a79e1" width="20"> Kolonin Gleb<br>

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
