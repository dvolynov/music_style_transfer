# Music Style Transfer

This repository contains the code and resources for the Music Style Transfer project, which aims to apply the concept of style transfer, commonly used in image processing, to the field of music. By leveraging deep learning techniques and custom neural networks, this project enables the generation of unique music compositions by blending the style of one piece with the content of another.

## Project Description

The Music Style Transfer project explores the application of style transfer techniques to the music industry. Similar to how style transfer works for images, where the artistic style of one image is applied to another, this project aims to achieve a similar effect with music. By combining the style of one piece with the content of another, we can create novel compositions with interesting blends of different musical genres and elements.  

<img src="https://github.com/dvolynov/Music-Style-Transfer/assets/83712099/bf0a7e9d-0375-4a2f-a0a6-7db7eb8069b3" width="500">   

The main focus of this project was to develop a custom neural network architecture that can extract meaningful features from audio spectrograms, which are representations of audio frequencies over time. While image-based style transfer often relies on pre-trained models like VGG-19 for feature extraction, audio spectrograms require a specialized approach.

## How it Works

The core components of the Music Style Transfer project are as follows:

1. **Audio Spectrograms**: Instead of working with raw audio data, we convert audio waveforms into spectrograms, which provide a visual representation of the frequency content over time. Spectrograms are widely used in audio processing and are suitable for input to neural networks.

2. **Custom Neural Network**: We developed a custom neural network architecture specifically designed to extract features from audio spectrograms. This network comprises a single convolutional layer capable of extracting 4,000 features from the input spectrogram.

![image](https://github.com/dvolynov/Music-Style-Transfer/assets/83712099/d811aee2-b2a6-44f1-ae3d-a2d4d75e69a9)

3. **Loss Functions**: To guide the network's training process, we implemented two custom loss functions: "Get content loss" and "Get style loss." These functions measure the disparity between the network's predictions and the desired outputs, ensuring that the generated compositions retain the content of the original piece while incorporating the style of another.

4. **Training Process**: During the training phase, the network learns to optimize the spectrogram to resemble the desired style while preserving the content. The spectrogram progressively transforms from a noisy representation to a refined one that exhibits the desired style characteristics.

![image](https://github.com/dvolynov/Music-Style-Transfer/assets/83712099/b5fd2c78-4466-4806-992b-bffd9e67966b)

5. **Audio Reconstruction**: To convert the transformed spectrogram back into an audio waveform, we employ the Griffin-Lim algorithm and Inverse Fourier transform. This reconstruction process allows us to generate an audio output that reflects the desired style transfer.

## Repository Contents

This repository contains the following resources:

- **Custom Neural Network**: The code for the custom neural network architecture, including the single convolutional layer that extracts features from audio spectrograms.

- **Loss Functions**: Implementation of the "Get content loss" and "Get style loss" functions, which measure the differences between the network's predictions and the desired outputs.

- **Training Process**: Code and documentation demonstrating the training process, showcasing how the spectrogram evolves over time to achieve the desired style transfer.

- **Audio Reconstruction**: Implementation of the Griffin-Lim algorithm and Inverse Fourier transform for converting the transformed spectrogram back into an audio waveform.

- **Articles**: A collection of relevant articles and resources that aided in the development and understanding of the Music Style Transfer project.

## Usage

To explore the Music Style Transfer project and create your own unique compositions, follow these steps:

1. Clone the repository to your local machine using the following command:




<img src="https://github.com/dvolynov/Music-Style-Transfer/assets/83712099/e123c5be-88ba-4dad-a9e8-f3fa2c2a9ee0" width="500">   
 


<h2>Authors:</h2>
<img src="https://github.com/dvolynov/Music-Style-Transfer/assets/83712099/d47c666b-1e29-416c-99cf-ad0196186367" width="20"> Dmitriy Volynov<br>
<img src="https://github.com/dvolynov/Music-Style-Transfer/assets/83712099/fecdf38e-fa56-46c1-af04-761f73a62172" width="20"> Alexandr Dyakov<br>
<img src="https://github.com/dvolynov/Music-Style-Transfer/assets/83712099/1d750242-aff3-430d-9389-cd483a80de60" width="20"> Nikita Pestretsov<br>
<img src="https://github.com/dvolynov/Music-Style-Transfer/assets/83712099/c14fe25c-cc18-41b1-b452-e349b96a79e1" width="20"> Kolonin Gleb<br>
