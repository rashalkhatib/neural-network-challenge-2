# neural-network-challenge-2
This model can be used by HR to predict whether employees are likely to leave the company. It also predicts which employees can be better suited in different departments within the company.

# Dataset Overview:
- The dataset contains various features related to employees, such as age, years since last promotion, distance from home, education level, job satisfaction, total working years, and job involvement. These factors are explored and analyzed to determine their influence on whether an employee leaves the organization.
# Preparing & preprocessing the data:
- X_df includes 10 columns that include features related to the employees.
- y_df includes the "attrition" column and the "department" column.
- The features and target sets have been split into training and testing sets.
- The X data was converted into numeric data.
- StandardScaler was used to fit the scaler for training data and was used to transform both the training and testing data.
- OneHotEncoder was used to fit the encoder for training data and was used to transform both the training and testing data.
# Create, compile, and train the model:
- 2 layers were created to create, compile, and train the model. The model was evaluated with the testing data.
- The accuracy for both department and attrition was printed.

# Summary:
This notebook summarizes the most important factors that influence employee attrition, providing data-driven recommendations for reducing turnover in an organization.
