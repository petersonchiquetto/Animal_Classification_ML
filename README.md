# Animal_Classification_ML 🐶🐷

This repository contains a machine learning model for classifying animals like pigs 🐷 and dogs 🐶. Explore the code and learn how accurate animal classification is achieved! 

## Features

* **Animal classification:** Distinguishes between pigs 🐷 and dogs 🐶 based on provided features.
* **Machine learning:** Utilizes the `LinearSVC` model from scikit-learn for classification. 🧠
* **Accuracy calculation:** Calculates and displays the accuracy of the model. 💯

## Technologies Used

* **Python:** The programming language used for the algorithm. 🐍
* **scikit-learn:** A powerful and versatile machine learning library for Python, providing tools for classification, regression, clustering, dimensionality reduction, and more. 🤖

## Code Overview

The code defines features (long hair, short legs, and barking) and creates datasets for pigs 🐷 and dogs 🐶 based on these features. It then trains a `LinearSVC` model from scikit-learn on this data and predicts the class of a mystery animal. ⁉️ Finally, it evaluates the model's accuracy.

**Training the model:**

The `LinearSVC` model is trained using a supervised learning approach. This means that the model is provided with a set of labeled data, where each data point is associated with a known class (pig or dog). The model learns to identify patterns and relationships in the data that distinguish between the two classes. 

**Scikit-learn:**

Scikit-learn is a popular open-source machine learning library for Python. It provides a wide range of algorithms and tools for building and training machine learning models, including classification, regression, clustering, and dimensionality reduction. Scikit-learn is built on top of NumPy, SciPy, and matplotlib, making it easy to integrate with other scientific Python libraries.

## Getting Started

To run this code, you need to have Python and scikit-learn installed. You can then copy and paste the code into a Python file or Jupyter Notebook and run it. 🚀

## Results

The model achieved an accuracy of 66.67% on the test data. 🎉

## Contributing

Contributions are welcome! If you have any ideas for improvements or want to add more features, feel free to submit a pull request. 🤝

## License

This project is licensed under the MIT License - see the LICENSE file for details. 📜
