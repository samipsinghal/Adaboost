# Adaboost Implementation

This repository contains the implementation of the Adaboost algorithm as part of the course DLF21 (Deep Learning Fundamentals 21).

## Overview

This project involves the implementation of the Adaboost algorithm, a powerful ensemble method that combines the predictions of multiple weak learners to produce a strong learner. The notebook includes the steps to preprocess the data, implement the Adaboost algorithm, and evaluate its performance. The accuracy using the ensemble method is significantly higher compared to using a decision tree independently. The maximum accuracy achieved with the ensemble method was around 98%, whereas it was around 88% with only a decision tree.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run the notebook and reproduce the results, you need to have Python and the necessary libraries installed. Follow the steps below to set up your environment:

1. Clone the repository:
    ```sh
    git clone https://github.com/samipsinghal/Adaboost.git
    cd Adaboost
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

To use this repository, open the `adaboost.ipynb` notebook in Jupyter Notebook or Jupyter Lab. You can run the cells in the notebook to understand the steps involved in the implementation of the Adaboost algorithm and see the results of various experiments.

## Project Structure

The repository is structured as follows:

- `adaboost.ipynb`: Main Jupyter Notebook containing the project implementation.
- `Copy_of_dlf21_hw1_prob5.ipynb`: Additional notebook related to the homework assignment.
- `requirements.txt`: List of Python libraries required to run the notebooks.

## Examples

Here are some of the key sections covered in the main notebook (`adaboost.ipynb`):

1. **Introduction to Adaboost**: Overview of the Adaboost algorithm, its importance, and applications.
2. **Data Preparation**: Steps to preprocess the data for training the Adaboost model.
3. **Algorithm Implementation**: Detailed implementation of the Adaboost algorithm.
4. **Training and Evaluation**: Training the Adaboost model on the dataset and evaluating its performance.
5. **Results and Analysis**: Visualization and analysis of the results obtained from the experiments. The accuracy using the ensemble method is significantly higher compared to using a decision tree independently. The maximum accuracy achieved with the ensemble method was around 98%, whereas it was around 88% with only a decision tree.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to create a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
