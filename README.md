# Audio_Classification_FYP

This repository contains code and resources for an audio classification project with a backend server using Express.js. The goal of this project is to classify audio samples into different categories or labels. 

## Dataset
The dataset used for this project is UrbanSound8k dataset, which consists of . The dataset is split into training, validation, and test sets for model training, evaluation, and testing.

## Models
Several machine learning models are implemented for audio classification, including:
- Convolutional Neural Networks (CNNs)
- Recurrent Neural Networks (RNNs)
- Convolutional Recurrent Neural Networks (CRNNs)
- Support Vector Machines (SVMs)
- Random Forests
- Gradient Boosting Machines (GBMs)

## Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/SugnikMukherjee/Audio_Classification_FYP.git
    ```
2. Navigate to the backend directory:
    ```bash
    cd  SugnikMukherjee/Audio_Classification_FYP/backend
    ```
3. Install the required dependencies:
    ```bash
    npm install
    ```

## Usage
1. Start the backend server:
    ```bash
    npm start
    ```
2. The server will start running at `http://localhost:5000`. You can now make requests to this server for audio classification tasks.

## API Endpoints
- `/classify`: POST endpoint for classifying audio files. Send a POST request with the audio file to classify.

## Results
The performance of each model is evaluated using metrics such as accuracy, precision, recall, and F1-score. Results are presented in the form of confusion matrices, classification reports, and accuracy scores.

## Contributors
- Shubhabrata Ghosh
- Anmol Sharma

## License
This project is licensed under the [MIT License](LICENSE).

For any questions or suggestions, please contact [sugnikmukherjee.ac@gmail.com].
