# Text Classification with Neural Networks

This project demonstrates how to perform text classification using Neural Networks. The primary task is to classify movie reviews as positive or negative based on textual data from the IMDB dataset.

## Table of Contents
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Model Architecture](#model-architecture)
- [Usage](#usage)
- [Results](#results)

## Dataset
The dataset used in this project is the IMDB dataset, which contains 50,000 movie reviews with the following structure:
- **review**: The textual content of the review.
- **sentiment**: The label indicating the sentiment of the review (positive or negative).

You can download the dataset from [Kaggle link](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews).

## Project Structure
1. **Data Preprocessing**:
    - Remove special characters and HTML tags.
    - Convert text to lowercase.
    - Remove stop words using NLTK.
    - Tokenize and pad sequences.
2. **Model Building**:
    - Utilize embedding layers for word representation.
    - Build a sequential neural network with layers like LSTM and Dense.
3. **Evaluation**:
    - Split data into training and testing sets.
    - Train the model using the training set and evaluate performance on the test set.

## Technologies Used
- Python
- Keras (for deep learning models)
- NLTK (for text preprocessing)
- Pandas & NumPy (for data manipulation)
- Google Colab (for execution environment)

## Model Architecture
The model consists of the following components:
- **Embedding Layer**: To convert words into dense vectors.
- **LSTM Layer**: For capturing sequential dependencies in the text.
- **Dense Layers**: For classification output.

## Usage
1. Clone this repository:
    ```bash
    git clone https://github.com/thanghd1112/Text-Classification-with-Neural-Networks.git
    ```
2. Open the `07_textClassification.ipynb` notebook.
3. Load the IMDB dataset into the specified path.
4. Run the notebook cells sequentially.

## Results
The model achieves high accuracy on the test set, demonstrating its effectiveness in classifying movie reviews. The exact results (e.g., accuracy, loss) can be found in the notebook's output section.
