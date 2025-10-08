# Customer-Churn-Prediction-Using-Deep-Learning
This project predicts whether a customer is likely to leave (churn) or stay with a bank using deep learning (ANN).   It combines exploratory data analysis (EDA)  and a  TensorFlow-based neural network model to identify key churn drivers such as age, tenure, credit score, balance, and activity status.

Project Overview - 
- Performs detailed EDA to understand churn behavior.
- Builds and trains an ANN model using TensorFlow & Keras.
- Evaluates model performance using accuracy and classification metrics.
- Provides insightful visualizations to interpret patterns behind churn.

ANN Architecture
  | Layer          | Type  | Activation | Output Neurons |
| -------------- | ----- | ---------- | -------------- |
| Input Layer    | Dense | ReLU       | 11             |
| Hidden Layer 1 | Dense | ReLU       | 7              |
| Hidden Layer 2 | Dense | ReLU       | 6              |
| Hidden Layer 3 | Dense | ReLU       | 6              |
| Output Layer   | Dense | Sigmoid    | 1              |

