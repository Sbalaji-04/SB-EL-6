## K-Nearest Neighbors (KNN) Classification

### Steps Completed

1. **Dataset Selection and Loading**
   - Loaded the Iris dataset using `pandas.read_csv()`
   - Dropped the irrelevant `Id` column

2. **Exploratory Data Analysis**
   - Used `.info()`, `.describe()`, `.nunique()`, and `.isnull().sum()` to analyze the data

3. **Feature Scaling**
   - Applied `StandardScaler()` to normalize the feature values

4. **Train-Test Split**
   - Used `train_test_split()` to split data into 70% train, 30% test

5. **KNN Model Training and Evaluation**
   - Trained KNN models for values of K from 1 to 20
   - Plotted Accuracy vs. K
   - Selected best K (K = 3)
   - Evaluated model using `accuracy_score` and `confusion_matrix`

6. **Decision Boundary Visualization**
   - Chose 2 features (`PetalLengthCm`, `PetalWidthCm`) for 2D visualization
   - Plotted decision boundaries using `matplotlib.contourf()`
   - Encoded string labels to integers for compatibility

