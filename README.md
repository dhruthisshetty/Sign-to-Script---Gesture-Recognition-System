# Sign to Script - Gesture Recognition System

![Sign Language Recognition](https://via.placeholder.com/800x400?text=Sign+Language+Recognition)

## Overview

Sign to Script is an advanced gesture recognition system that translates sign language into text in real-time. Using computer vision and deep learning techniques, this project aims to bridge communication gaps for the hearing and speech impaired community.

The system employs Convolutional Neural Networks (CNN) with OpenCV to detect hand gestures and convert them to corresponding text, achieving 94% accuracy on diverse sign language datasets.

## Features

- **Real-time Sign Language Detection**: Translate hand gestures to text instantly
- **High Accuracy**: 94% accurate recognition using optimized CNN models
- **User-friendly Interface**: Intuitive design for improved accessibility
- **Multiple Sign Language Support**: Compatible with various sign language systems

## Research

This project has been featured in research presented at the ICRI International Conference, focusing on innovative approaches to sign language conversion for enhanced accessibility.

## Table of Contents

1. [Installation](#installation)
2. [Dataset](#dataset)
3. [Model Architecture](#model-architecture)
4. [Usage](#usage)
5. [Results](#results)
6. [Future Work](#future-work)
7. [Technologies Used](#technologies-used)

## Installation

### Prerequisites

- Python 3.7+
- TensorFlow 2.x
- OpenCV 4.x
- NLTK
- NumPy

### Setup

```bash
# Clone the repository
git clone https://github.com/dhruthisshetty/Sign-to-Script---Gesture-Recognition-System.git
cd Sign-to-Script---Gesture-Recognition-System

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Dataset

The project uses a custom dataset of sign language gestures . The dataset includes:

- Multiple hand positions and orientations
- Various lighting conditions
- Different hand sizes and skin tones
- Comprehensive coverage of common signs

## Model Architecture

Our CNN architecture consists of:

1. **Input Layer**: Captures hand gesture images (64x64x3)
2. **Convolutional Layers**: Multiple layers for feature extraction
3. **Max Pooling Layers**: For dimensionality reduction
4. **Dropout Layers**: To prevent overfitting
5. **Fully Connected Layers**: For classification
6. **Output Layer**: Predicts the corresponding text for each gesture

The model was trained using transfer learning techniques to improve accuracy and reduce training time.

## Usage

### Running the Application

```bash
python data_collection.py
```

### Basic Commands

1. Position your hand in front of the camera
2. Make sign language gestures
3. View real-time text translation on the interface



## Results

- **Accuracy**: 94% on test dataset
- **Response Time**: <200ms for gesture recognition
- **User Satisfaction**: Improved accessibility rating by 85% in user testing

## Future Work

- Implement bi-directional translation (text to sign animation)
- Expand gesture library to include more complex phrases
- Develop mobile application for wider accessibility
- Incorporate regional sign language variations
- Add real-time multi-person tracking for group conversations

## Technologies Used

- **Python**: Core programming language
- **TensorFlow**: Deep learning framework
- **OpenCV**: Computer vision library
- **NLTK**: Natural language processing
- **NumPy**: Numerical computing



## Acknowledgements

- Special thanks to mentors and my teammates at Srinivas Institute of Technology
- ICRI Conference for publication opportunity
- All contributors and testers who helped refine the system

## Contact

Dhruthi Shetty - dhruthishetty25@gmail.com

Project Link: [https://github.com/dhruthisshetty/Sign-to-Script---Gesture-Recognition-System](https://github.com/dhruthisshetty/Sign-to-Script---Gesture-Recognition-System)
