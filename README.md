# Machine Learning Beginner Class - Final Project

## Rock-Paper-Scissors Image Classification using TensorFlow Keras

### Overview

This repository contains the final project submission for the Machine Learning Beginner class on Dicoding. The project focuses on image classification, specifically recognizing hand gestures representing rock, paper, and scissors. TensorFlow Keras is utilized for building and training the deep learning model.

### Project Structure

- **Dataset:** The project uses the 'rockpaperscissors' dataset, which can be downloaded [here](https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip). The dataset is divided into training and validation sets, following a 60-40 split.

- **Data Augmentation:** Image data augmentation is implemented to enhance the model's performance. This includes rotation, horizontal flip, shear, and fill mode adjustments.

- **Model Architecture:** A sequential model is constructed using Convolutional Neural Networks (CNN). The model comprises multiple convolutional and pooling layers, followed by dense layers for classification.

- **Training:** The model is trained using the Adam optimizer and categorical cross-entropy loss. The training process is monitored, and the model with the highest validation accuracy is saved using callbacks.

- **Prediction:** The trained model is capable of predicting images uploaded to Google Colab. The prediction result, along with the uploaded image, is displayed.

### How to Use

1. Download the 'rockpaperscissors.zip' dataset from the provided [link](https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip).

2. Extract the zip file, and ensure that the dataset is in the correct structure.

3. Open the provided .ipynb file in Google Colab.

4. Execute each code cell sequentially.

5. Upload an image of a hand gesture (rock, paper, or scissors) when prompted.

6. View the prediction result.

### Dependencies

- TensorFlow
- Keras
- NumPy
- Matplotlib

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
Feel free to explore and experiment with the code! If you have any questions or suggestions, don't hesitate to reach out.
Happy coding! 🚀
