# Breast Cancer Detection
This project focuses on classifying breast cancer images as either benign or malignant using a Convolutional Neural Network (CNN) model based on DenseNet201. By leveraging transfer learning, the model achieves high accuracy in distinguishing between benign and malignant tumors.

### Data Preprocessing
- Utilized OpenCV and PIL to load and process images.
- Applied data augmentation using ImageDataGenerator from Keras to improve model generalization.
- Split the dataset into training and validation sets for effective model evaluation.

### Model Architecture
- Used DenseNet201 as the backbone of the CNN model for feature extraction.
- Applied transfer learning to leverage pre-trained weights on the ImageNet dataset.
- Added custom layers for binary classification with a softmax activation function.

### Training
- Trained the model using Adam optimizer with a learning rate scheduler to reduce learning rate when the validation accuracy plateaus.
- Employed ReduceLROnPlateau and EarlyStopping callbacks for better training performance.
- Achieved significant accuracy in classifying breast cancer images through effective training and validation strategies.

### Results
- The model demonstrated high accuracy in classifying images, with detailed performance metrics and visualizations.
- Plotted training and validation accuracy and loss curves using Matplotlib.
