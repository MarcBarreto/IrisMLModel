# IrisMLModel

## Table of Contents
1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Data](#data)
6. [Model](#model)
7. [Evaluation](#evaluation)
8. [License](#license)

## Introduction
The IrisMLModel project aims to learn the Julia programming language for machine learning purposes. The project utilizes various libraries such as MLJ for model creation and OpenML for loading the Iris dataset. The project involves data loading, preprocessing, model training, and evaluation.

## Project Structure
The project is organized as follows:
```sh
  IrisMLModel
  ┣ 📂 env
  ┃ ┗ 📜 Project.toml
  ┣ 📜 NeuralNetworkClassifier.ipynb
  ┣ 📜 LICENSE
  ┣ 📜 .gitignore
  ┗ 📜 README.md
```


## Installation
To run this project, you need to have Julia installed along with the required packages. Follow the instructions below to get started:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/IrisMLModel.git
   cd IrisMLModel
   ```
2. **Install Julia**:

  Download and install Julia from the official [Julia website](https://julialang.org/).

3. **Install Required Packages**:
  Open Julia and install the required packages:
    ```bash
    using Pkg
    Pkg.activate("env")
    Pkg.instantiate()
    Pkg.add("MLJ")
    Pkg.add("MLJFlux")
    Pkg.add("OpenML")
    Pkg.add("DataFrames")
    Pkg.add("Plots")
    ```

## Usage
To use the IrisMLModel project, follow these steps:

1. **Open the Jupyter Notebook**:

  Launch Jupyter Notebook:
  ```sh
    jupyter notebook
  ````
  Open NeuralNetworkClassifier.ipynb.
  
2. **Run the Notebook**:

  Execute the cells in the main.ipynb notebook sequentially. The notebook includes the following steps:
    * Environment setup
    * Data loading and preprocessing
    * Model creation and training
    * Model evaluation and learning curve plotting

## Data

  * Dataset: Iris
  * Source: OpenML Dataset 61
  * The dataset contains information about different species of the Iris flower and is commonly used for classification tasks.

## Model
  Neural Network Classifier
    * Algorithm: Neural Network Classifier
    * Library: MLJ and MLJFlux
    * Training: The model is trained using the Iris dataset.
    * Epochs: 30

## Evaluation

The notebook includes sections for evaluating the model, where various metrics and visualizations are used to assess the performance of the neural network classifier. A learning curve is plotted to show the error based on cross-entropy over different epochs.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.

-----

Feel free to explore and modify the code to suit your needs!
