# Driver Drowsiness Detection System

## Overview

This project aims to detect drowsiness in drivers by analyzing their eye movements and detecting yawns. The system utilizes artificial neural networks to build an effective model for drowsiness detection.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Dataset](#dataset)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

Driver drowsiness is a significant factor in road accidents. This project addresses this issue by employing artificial neural networks to analyze eye movements and detect yawns. The system is designed to provide timely alerts to drivers, enhancing road safety.

## Requirements

- Python 3.2
- TensorFlow
- OpenCV
- Dlib
- Numpy
- Matplotlib

You can install the required dependencies using the following command:

```bash
pip install -r requirements.txt
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/drowsiness-detection.git
cd drowsiness-detection
```

2. Install the dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run the drowsiness detection system using the following command:

```bash
python drowsiness_detection.py
```

The system will use the webcam to monitor the driver's eye movements and yawns in real-time.

## Model Training

To train the neural network model:

1. Prepare your dataset (see [dataset](https://www.kaggle.com/datasets/prasadvpatil/mrl-dataset) section).
2. Run the training script:

```bash
python train_model.py --dataset https://www.kaggle.com/datasets/prasadvpatil/mrl-dataset
```

Adjust the parameters as needed for your dataset and model architecture.

## Dataset

The dataset used for training should consist of labeled images representing different states of the driver (e.g., alert, drowsy, yawning). Ensure the dataset is organized appropriately before training the model.

## Results

Include any relevant results or performance metrics obtained by the model. This can help users understand the effectiveness of the drowsiness detection system.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request..

Feel free to customize this README according to your project's specifics. Good luck with your drowsiness detection system!
