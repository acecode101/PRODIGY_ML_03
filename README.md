Cats vs Dogs Classification using Support Vector Machine (SVM)

This project implements a Support Vector Machine (SVM) to classify images of cats and dogs from the Kaggle dataset. The task involves image preprocessing, feature extraction, and model training using SVM to build a binary classifier.

Workflow:

Data Loading and Preprocessing:

Uploaded and extracted the training and test sets.

Images were resized to 64x64 pixels and normalized using ImageDataGenerator.

Data flattened for SVM input.

Model Training:

Utilized a linear SVM classifier for binary classification.

Feature scaling applied using StandardScaler to improve model performance.

Dimensionality Reduction:

Principal Component Analysis (PCA) was applied to reduce the feature space to 2 dimensions, making it easier to visualize decision boundaries.

Evaluation:

Achieved accuracy and performance metrics, including precision, recall, and F1-score.

Generated a confusion matrix and classification report for detailed model evaluation.

Visualization:

Visualized training and test images.

Plotted decision boundaries after PCA reduction.

Feature importance was visualized using SVM coefficients.

Misclassifications and class distributions were analyzed and visualized.

Key Libraries:

TensorFlow/Keras

Scikit-learn

Matplotlib

Seaborn

Results:

Successfully classified images of cats and dogs.

Achieved a reasonable accuracy with insightful visualizations for performance evaluation and feature importance.
