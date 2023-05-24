# Titanic Survival Prediction

<p align="center">
  <img src="https://github.com/Amr1997/Machine-learning-projects/blob/main/assets/titanic.png" alt="Titanic Survival Prediction">
</p>

## Introduction

In this project, I used a dataset of Titanic passenger information to predict whether a passenger would survive the sinking of the Titanic or not. I used a logistic regression model to make predictions based on features such as age, gender, and passenger class.

## Dataset

The Titanic dataset contains information about passengers on the Titanic, including their age, gender, passenger class, and whether or not they survived the sinking of the ship. The dataset is available in the `data` directory and can be loaded using the Pandas library.

## Model

I used a logistic regression model to predict whether a passenger would survive or not. The model was trained using the training set from the Titanic dataset, and evaluated on the test set. I also performed some feature engineering to create new features, such as family size and passenger titles, to improve the performance of the model.

## Results

The final model achieved an accuracy of 80% on the test set, which is a decent performance considering the simplicity of the model and the limited amount of data available. The model can be further improved by using more advanced machine learning techniques and incorporating additional features.

## Running the Project

To run theproject, follow these steps:

1. Clone the repository:
```
git clone https://github.com/Amr1997/Machine-learning-projects.git
```

2. Navigate to the `Titanic-Survival-Prediction` directory:
```
cd Titanic-Survival-Prediction
```

3. Install the required packages:
```
pip install -r requirements.txt
```

4. Train and evaluate the model:
```
python train.py
```

5. Make predictions on new data:
```
python predict.py
```

## Conclusion

This project demonstrates the application of machine learning techniques to a real-world problem. By analyzing and processing data from the Titanic disaster, we were able to predict whether a passenger would survive or not based on their characteristics. This project can be extended to include more advanced machine learning techniques and additional features to further improve the accuracy of the model.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

This project was inspired by the Kaggle competition [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic), which provides a dataset and a platform for participants to compete and improve their models. Special thanks to the Kaggle community for providing such a great resource for learning and practicing machine learning.
