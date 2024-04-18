# Cyber-Attack-Detection - IoT Security Model Evaluation
This repository is a submission of EE257 course project for Spring 2024.

## Overview

This project evaluates various machine learning models for IoT security using the RT2022-IoT dataset. It includes feature engineering techniques, hyperparameter tuning, and model evaluation to assess the performance of different models.

## Features

- **Data Preprocessing**: Includes data cleaning, encoding categorical variables, and scaling features.
- **Feature Engineering**: Implements feature selection and creation techniques to enhance model performance.
- **Model Development**: Trains and evaluates various machine learning models, including Logistic Regression, KNN, SVM, Decision Trees, and Random Forest.
- **Hyperparameter Tuning**: Utilizes GridSearchCV to optimize model hyperparameters and improve performance.
- **Model Evaluation**: Generates classification reports and confusion matrices to assess model performance.
- **Visualization**: Utilizes matplotlib and seaborn libraries to visualize model performance metrics and feature importance.

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Kamlesh364/Cyber-Attack-Detection.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

## Usage

- Open the Jupyter Notebook `Kamlesh_EE257_finalProject.ipynb`.
- Follow the instructions and execute each code cell sequentially to preprocess data, train models, and evaluate performance.

## Results

- The project demonstrates the effectiveness of Random Forest and Decision Tree models, especially when applied with Min-Max Scaling, for the RT2022-IoT dataset.
- Model performance metrics, including accuracy, precision, recall, and F1-score, are showcased through visualizations and classification reports.
- Hyperparameter tuning improves model performance, with Random Forest achieving the highest accuracy and average cross-validation accuracy.

## Future Enhancements

- Integration of models into practical IoT security systems.
- Exploration of ensemble methods and deep learning architectures for further optimization.
- Real-time evaluation and deployment of models in IoT environments.

## Contributors

- [Kamlesh Kumar](https://github.com/kamlesh364)

## License

This project is licensed under the [MIT License](LICENSE).

## References

[1]. Sharmila, B.S., Nagapadma, R. Quantized autoencoder (QAE) intrusion detection system for anomaly detection in resource-constrained IoT devices using RT-IoT2022 dataset. Cybersecurity 6, 41 (2023). doi:10.1186/s42400-023-00178-5.

[2]. S., B. and Nagapadma, Rohini. (2024). RT-IoT2022. UCI Machine Learning Repository. doi:10.24432/C5P338.

[3]. Pedregosa et al., Scikit-learn: Machine Learning in Python, JMLR 12, pp. 2825-2830, 2011.
