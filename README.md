# Machine Learning Project - Music Genre Classification

This project is part of the class 'Machine Learning Project' at DHBW Stuttgart. The goal of the project is to train a Convolutional Neural Network (CNN) to classify music genres using the GTZAN dataset.

## Dataset

The GTZAN dataset is used for training the model. You can download the dataset from [Kaggle](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification).

## Setup

### 1. Download the Dataset

1. Go to [Kaggle](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification) and download the dataset.
2. Create a `data` folder in the project directory and place the downloaded data there.
3. Alternatively, you can run the notebook `src/data.ipynb` to download the data. For this, you need to first create a Kaggle API key and place the `kaggle.json` file in the `src` folder.

### 2. Environment Setup

1. Create a virtual environment and install the required dependencies using `requirements.txt`:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

### 3. Data Preprocessing

Run the `src/data_preprocessing.ipynb` notebook to preprocess the data.

### 4. Model Training and Evaluation

The model definition, training, and evaluation are done in the `src/cnn.ipynb` notebook.

## Project Structure

# Machine Learning Project - Music Genre Classification

This project is part of the class 'Machine Learning Project' at DHBW Stuttgart. The goal of the project is to train a Convolutional Neural Network (CNN) to classify music genres using the GTZAN dataset.

## Dataset

The GTZAN dataset is used for training the model. You can download the dataset from [Kaggle](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification).

## Setup

### 1. Download the Dataset

1. Go to [Kaggle](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification) and download the dataset.
2. Create a `data` folder in the project directory and place the downloaded data there.
3. Alternatively, you can run the notebook `src/data.ipynb` to download the data. For this, you need to first create a Kaggle API key and place the `kaggle.json` file in the `src` folder.

### 2. Environment Setup

1. Create a virtual environment and install the required dependencies using `requirements.txt`:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

### 3. Data Preprocessing

Run the `src/data_preprocessing.ipynb` notebook to preprocess the data.

### 4. Model Training and Evaluation

The model definition, training, and evaluation are done in the `src/cnn.ipynb` notebook.

## Project Structure
├── data # Directory to store the dataset
├── src # Source files and notebooks
│ ├── data.ipynb # Notebook to download the data
│ ├── data_preprocessing.ipynb # Notebook for data preprocessing
│ ├── cnn.ipynb # Notebook for model definition, training, and evaluation
├── requirements.txt # Required dependencies
├── README.md # Project readme file
└── venv # Virtual environment directory

## Kaggle API Setup

To use the Kaggle API, follow these steps:

1. Log in to your Kaggle account.
2. Go to your account settings and create a new API token. This will download a file named `kaggle.json`.
3. Place the `kaggle.json` file in the `src` directory of this project.

## Running the Project

1. Ensure the dataset is available in the `data` directory or use the `src/data.ipynb` notebook to download it.
2. Preprocess the data using the `src/data_preprocessing.ipynb` notebook.
3. Train and evaluate the model using the `src/cnn.ipynb` notebook.

## Acknowledgments

This project is part of the Machine Learning Project class at DHBW Stuttgart.
