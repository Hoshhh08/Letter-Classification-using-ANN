# Artificial Neural Network (ANN) Classification Project

## Project Overview
This project implements an Artificial Neural Network (ANN) for multi-class classification using a given dataset. The model is built using TensorFlow/Keras and undergoes hyperparameter tuning to optimize performance. The primary goal is to analyze how hyperparameter tuning impacts model accuracy and classification metrics.

## Dataset Description
The dataset consists of multiple numerical features:
- **xbox, ybox, width, height, onpix, xbar, ybar, x2bar, y2bar, xybar, x2ybar, xy2bar, xedge, xedgey, yedge, yedgex**
- The target variable represents a categorical label for classification.

## Workflow
1. **Data Preprocessing**
   - Handled missing values (if any)
   - Scaled features using StandardScaler
   
2. **Model Implementation**
   - Built an ANN model using TensorFlow/Keras
   - Defined activation functions, optimizer, loss function, and layer structure

3. **Hyperparameter Tuning**
   - Used `GridSearchCV` and `RandomizedSearchCV` to find the best combination of:
     - Number of neurons
     - Activation functions
     - Optimizers
     - Batch size
     - Number of epochs

4. **Model Evaluation**
   - Compared the default and tuned models using precision, recall, F1-score, and accuracy
   - Evaluated classification report and performance metrics

5. **Testing the Model**
   - Created a sample test row
   - Applied the trained scaler and made predictions

## Results
- **Default Model**: Achieved a baseline accuracy with standard hyperparameters.
- **Tuned Model**: Improved accuracy, precision, and recall after optimization.
- The final model showed **enhanced classification performance**, proving the importance of hyperparameter tuning.

## How to Run the Notebook
1. Install dependencies using:
   ```bash
   pip install tensorflow numpy pandas scikit-learn
   ```
2. Open the Jupyter Notebook and run all cells.
3. Modify `test_row` with custom input values to test predictions.

## Key Takeaways
- Demonstrated proficiency in ANN implementation.
- Showcased hyperparameter tuning techniques.
- Improved model performance through optimization.
- Developed a structured ML pipeline from data preprocessing to model evaluation.

---

