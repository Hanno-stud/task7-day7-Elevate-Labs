# Task 7: SVM Classification - Breast Cancer Dataset

## Objective
Build SVM models using both linear and RBF kernels to classify tumors as malignant (M) or benign (B) from medical features.

## Dataset
- Features: radius, texture, area, smoothness, etc.
- Target: Diagnosis (M = Malignant, B = Benign)

## Tools Used
- Scikit-learn
- NumPy, Pandas
- Seaborn & Matplotlib
- PCA for visualization

## Steps Performed
Step 1 : Import the Libraries 📌
 <br/> **Libraries** : [pandas](https://pandas.pydata.org/), [numpy](https://numpy.org/), [matplotlib](https://matplotlib.org/), [seaborn](https://seaborn.pydata.org/), [sklearn](https://scikit-learn.org/stable/) and [google.colab](https://colab.research.google.com/notebooks/io.ipynb) <br/>
(this **google.colab** can only be used within Google Colab enivronment and it helps in uploading files from your local file system) <br/> <br/>
Step 2: Load and Prepare Dataset 📂  <br/> <br/>
Step 3: Feature Scaling and Data Splitting 📊 <br/> <br/>
Step 4: Train and Evaluate Linear SVM 🔍 <br/> <br/>
Step 5: Train and Tune RBF SVM with GridSearchCV 🎓🏋️‍♂️📚💪 <br/> <br/>
Step 6: PCA and Decision Boundary Plotting 📈 <br/> <br/>
Step 7: Decision Boundary Function ⚙️ƒ🛠️🦾 <br/> <br/>
Step 8: Cross-Validation 🔁 <br/> <br/>
Step 9: Final Execution Pipeline 🚀 <br/> <br/>

## Sample Results
- Linear SVM Accuracy: ~96%
- RBF SVM Accuracy (after tuning): ~98%
- Cross-validation Accuracy: ~97%

## Visualization
- PCA used to reduce to 2D for plotting SVM decision boundaries.

## Conclusion
SVM with RBF kernel gives better classification performance on this medical dataset after hyperparameter tuning.

OUTPUT

![image](https://github.com/user-attachments/assets/324a3c17-a953-4b74-b9ab-1a83328c8eea)
<br/>

![image](https://github.com/user-attachments/assets/c702ba0a-67f0-4a15-aa23-e18374f30ba6)

