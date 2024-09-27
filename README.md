# neural-network-challenge-2
The Attrition Prediction Model aims to predict two outcomes:
1. Department: The department to which an employee belongs (multi-class classification).
2. Attrition: Whether an employee will leave the company (binary classification).
- This project leverages deep learning techniques to model both outcomes based on employee features such as age, job level, salary, performance rating, and other factors. The model consists of shared layers and two output layers, each responsible for predicting one of the outcomes.

# Model Structure:
1. Shared Layers:
The first few layers of the model are shared between the two tasks (Department and Attrition), helping the network learn common patterns from the input data.
- Input Layer: Accepts employee features.
- Dense Layers: Two dense layers with 64 and 32 units, ReLU activation functions, and L2 regularization to prevent overfitting.
2. Output Layers:
The model has two branches after the shared layers:
- Department Output: Uses a softmax activation for multi-class classification. It predicts the department of the employee.
- Attrition Output: Uses a sigmoid activation for binary classification. It predicts whether the employee will leave the company.

# Loss Functions:
- Department Output: Categorical Crossentropy
- Attrition Output: Binary Crossentropy

- # Training Process:
- Optimizer: Adam optimizer is used for efficient gradient-based optimization.
- Batch Size: Set to 32.
- Epochs: The number of epochs can be modified, but the default is set to 50.

# Summary:
This notebook summarizes the most important factors that influence employee attrition, providing data-driven recommendations for reducing turnover in an organization.
