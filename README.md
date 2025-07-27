# Handwritten Digit Recognition with CNN
This project uses a Convolutional Neural Network (CNN) to classify handwritten digits from the popular MNIST dataset. The model was trained and fine-tuned with data augmentation and regularization techniques to achieve 99.375% accuracy on Kaggle, placing in the top 200 out of 1,500+ participants.

## Project Highlights
- Data Augmentation to prevent overfitting
- EarlyStopping and ReduceLROnPlateau callbacks
-  Batch Normalization, Dropout, and LeakyReLU for improved training
-  Achieved top-tier Kaggle performance (99.375%)

## Model Architecture
- `Conv2D` layers for feature extraction
- `BatchNormalization` for training stability
- `MaxPooling2D` and `Dropout` for regularization
- `LeakyReLU` activations
- `Flatten` → `Dense` → `Softmax` for classification

 ## Training Performance
 - Training and validation accuracy quickly reached ~99%
 - No significant overfitting observed
 - Model saved using best validation performance with `ModelCheckpoint`
 - [Visualized](github.com/kevinveeder/digit-cnn/visual_loss_accuracy.png) loss and accuracy across 90+ epochs 

