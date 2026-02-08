Image Caption Generation using CNN–LSTM

This project implements an end-to-end deep learning model for automatic image caption generation, combining computer vision and natural language processing techniques.
<img width="2752" height="1316" alt="ImageCaptionGenerator" src="https://github.com/user-attachments/assets/0b5230c6-88a9-4408-ab95-60bd750f6d12" />


Overview

The system extracts visual features from images using a CNN-based encoder and generates descriptive natural language captions using an LSTM-based decoder. The model is trained on the Flickr8k dataset and learns to map visual representations to coherent textual descriptions.

Dataset

- Flickr8k Dataset

- ~8,000 images with multiple human-annotated captions

- Vocabulary size: ~7,500 words

- (Dataset not included in this repository)

Model Architecture
<img width="2752" height="1477" alt="Model" src="https://github.com/user-attachments/assets/467a59e7-a81f-488b-82ab-02c85d0790ef" />

- CNN Encoder: Xception (pretrained, used as feature extractor)

- Feature vector size: 2048

- Text embedding + LSTM-based sequence decoder

- Multimodal fusion of visual and textual features

- Softmax output layer for word prediction

Sample Output
<img width="2752" height="1561" alt="output" src="https://github.com/user-attachments/assets/891459ca-953b-4abb-ba87-ccdf5fb50973" />
- 

Technologies Used

- Python

- TensorFlow / Keras

- Convolutional Neural Networks (CNN)

- LSTM (RNN)

- Computer Vision & NLP

Notes

- The project focuses on understanding and implementing multimodal deep learning pipelines.

- Pretrained CNN weights are used for feature extraction.

- Training was performed on a subset of the dataset due to resource constraints.
