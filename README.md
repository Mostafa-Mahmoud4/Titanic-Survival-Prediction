# Titanic Survival Prediction with Neural Network

## 1. Load Data:
   - Import libraries: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, TensorFlow.
   - Load Titanic dataset from CSV.
   - Check data overview, missing values, and class distribution.

## 2. Data Preprocessing:
   - Drop unnecessary columns: 'PassengerId', 'Name', 'Ticket', 'Cabin'.
   - Fill missing values: 'Age' with median, 'Embarked' with mode.
   - Encode categorical variables: 'Sex', 'Embarked' using one-hot encoding.

## 3. Split Data:
   - Separate features (X) and target variable (y).
   - Split data into training and testing sets (80-20 split).

## 4. Build Neural Network:
   - Create a Sequential model with three dense layers.
   - Use ReLU activation for hidden layers and sigmoid for output.
   - Compile the model with Adam optimizer and binary cross-entropy loss.

## 5. Train Model:
   - Train model on training data (50 epochs, batch size 32).
   - Validate with 20% of training data.

## 6. Evaluate Model:
   - Evaluate trained model on training and testing data.
   - Print train and test accuracy.

