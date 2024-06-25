# Web3 Personality Analyser

Welcome to the Web3 Personality Analyser! This web app is built with an open-source philosophy, enabling anyone to customize and enhance it. Our goal is to facilitate the detection of mental health problems using advanced machine learning techniques.

## Overview

The Web3 Personality Analyser leverages Web3 technology to provide easy access to datasets and machine learning models. By simply running a Python script, users can download the dataset and build a model, thanks to the integration with 0g Labs. We employ a RandomForestClassifier for our machine learning model, which achieves an impressive accuracy rate of over 95%.

## Features

- **Open Source**: Customize and enhance the app to fit your needs.
- **Mental Health Detection**: Focuses on detecting mental health issues.
- **Web3 Integration**: Easily access datasets and build models.
- **Machine Learning**: Utilizes RandomForestClassifier with >95% accuracy.

## Getting Started

### Prerequisites

- Python 3.x
- Go

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/skwasimrazzak/Web3-Personality-Analyser.git
    cd Web3-Personality-Analyser
    ```

2. Set up the Go module and run the Go script to upload the dataset:
    ```bash
    go mod init 0g-sdk-demo
    go mod tidy
    go run main.go
    ```

### Usage

1. Run the Python script to download the dataset and build the model:
    ```bash
    python script.py
    ```

2. Start the web app (instructions depend on your web framework and setup).

### Customization

Feel free to customize and enhance the app to better suit your requirements. Contributions are welcome!

## Machine Learning Model

We use a RandomForestClassifier for our machine learning model, which provides an accuracy rate of over 95%.

## Contributing

We welcome contributions from the community. If you have suggestions for improvements, please open an issue or submit a pull request.

## Acknowledgements

- Powered by 0g Labs
- Thanks to the open-source community for their contributions
