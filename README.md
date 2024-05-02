# Brain-Computer Interface (BCI) Research

## Overview
This repository contains the Jupyter notebooks and code for our brain-computer interface (BCI) project. Our BCI system interprets brain signals into commands for text or speech, facilitating communication for individuals with disabilities. By leveraging advanced neural network models, we aim to enhance the interaction between the human brain and digital devices, improving accessibility and quality of life.

## Project Structure

BCI-Research/
│
├── 1-Data.ipynb
│ └── Overview of the data sources used, data loading mechanisms, and initial data visualization techniques.
│
├── 2-Preprocessing.ipynb
│ └── Details on signal preprocessing steps such as filtering, normalization, and artifact removal necessary for clean signal analysis.
│
├── 3-Feature_extraction.ipynb
│ └── Techniques and methods used to extract meaningful features from the preprocessed brain signals that will be used for classification.
│
├── 4-Classification/
│ ├── 4-1-1 Temporal features.ipynb
│ │ └── Classification based on temporal features using traditional machine learning methods.
│ ├── 4-1-2 Temporal features.ipynb
│ │ └── Advanced classification techniques focusing on temporal aspects of brain signals.
│ ├── 4-2 Spatial features (CNN).ipynb
│ │ └── Utilization of Convolutional Neural Networks (CNNs) to classify brain signals based on spatial features.
│ └── 4-3 Graphical features (Graph NN).ipynb
│ └── Application of Graph Neural Networks (GNNs) for classification based on complex graphical representations of brain activity.
│
├── 4-Deep_learning_methods.ipynb
│ └── Exploration of various deep learning architectures and their application in enhancing BCI functionalities.
│
├── BCI_Demo.ipynb
│ └── A demonstration notebook showing how the BCI system works in real-time or simulated environments.
│
└── BCI_functions.ipynb
└── Contains all the utility functions used across the project for tasks such as data handling, model training, and results visualization.


## Research Goals
- **Developing Models**: Understand and predict brain activity patterns to improve the efficiency of thought-to-text translation.
- **Enhancing Accuracy and Speed**: Focus on improving the accuracy and speed of translating thoughts into text or speech.
- **Exploring Diverse Applications**: Investigate various applications ranging from control systems to communicative interfaces to broaden the impact of BCI technologies.

## Comparison with Existing Technologies
While drawing inspiration from pioneering technologies like Neuralink, our project emphasizes a broader application spectrum, detailing the transformative potential of BCI technology to enhance lives through new forms of interaction and restoring functionalities.

## How to Use This Repository
1. **Clone the Repository**: Clone this repository to your local machine.
2. **Install Dependencies**: Run `pip install -r requirements.txt` to install the required Python packages.
3. **Explore Notebooks**: Navigate through the notebooks in numerical order to understand our step-by-step process.

