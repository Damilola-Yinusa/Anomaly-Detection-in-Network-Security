# Anomaly Detection in Network Security 

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [Relevance to Today's World](#relevance-to-todays-world)
8. [License](#license)
9. [Acknowledgments](#acknowledgments)

## Introduction
This repository contains a data-driven project designed to identify anomalies in network traffic, thereby contributing to more robust network security measures. The project is structured as a Jupyter Notebook and employs a variety of machine learning algorithms to classify network activity into 'Normal' and 'Attack.' 

## Features
- **Data Loading**: Automated scripts for loading the UNSW-NB15 dataset.
- **Data Preprocessing**: Comprehensive preprocessing steps, including handling of missing values, normalization, and type conversions.
- **Feature Engineering**: Techniques like label encoding, one-hot encoding, and standard scaling were used to prepare the dataset for machine learning algorithms.
- **Model Training and Evaluation**: Utilized supervised learning models such as Random Forest, SVM, and Gradient Boosting for classification tasks. Models are rigorously evaluated using metrics like accuracy, precision, and recall.

## Technologies Used
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Jupyter Notebook

## Installation
1. Clone this GitHub repository.
   ```
   git clone <repo_url>
   ```
2. Navigate to the project directory.
   ```
   cd <project_folder>
   ```
3. Install the required packages.
   ```
   pip install -r requirements.txt
   ```

## Usage
- Open the Jupyter Notebook `Anomaly_Detection_in_Network_Security_Main.ipynb`.
- Run all the cells in sequence to execute the project.

## Contributing
Contributions, issues, and feature requests are welcome. Please feel free to check the issues page for any upcoming tasks you might have.

## Relevance to Today's World
In today's digitally interconnected world, the need for robust cybersecurity solutions is more critical than ever. This project serves as a timely response to this challenge by offering a machine learning-based framework for detecting abnormal activities in network systems, thus enhancing an organization's cybersecurity posture.

## License
This project is under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments
- Thanks to the creators of the UNSW-NB15 dataset for providing a comprehensive dataset for network activities.
- Special thanks to all contributors including but not limited (to Henry Jaiyeoba) and anyone who finds this project useful.
