# Animal-Image-Classifier-Using-Transfer-Learning
This project focuses on classifying images of cats and dogs using Transfer Learning with the MobileNetV2 model, pre-trained on ImageNet. The model was trained on a dataset of 25,000 images, achieving 97.75% accuracy on the test set. It is intended for use in pet adoption platforms to automate image classification for better user experience.

**Problem Objective**
Classification Task: Classify pet images (cats and dogs) for B2B market applications, specifically for pet adoption and selling websites.
Prototype Application: The classifier helps websites like Only4Pets auto-categorize images of pets uploaded by sellers, streamlining the user interface and improving efficiency.

**Technology Stack**
Pre-trained Model: MobileNetV2 (trained on ImageNet)
Libraries Used: TensorFlow, Numpy, PIL, Matplotlib, ScikitLearn, OpenCV
Dataset: Kaggle Dogs vs Cats dataset
Platform: Google Colab

**Pre-processing & Model Architecture**
Binary Classification: Cat = 0, Dog = 1
Image Resizing: 25k images resized to 224x224 pixels
Data Splitting: 80% training, 20% testing
Model: MobileNetV2 (Transfer Learning)
Performance: Achieved 99.37% training accuracy and 97.75% test accuracy
Optimization: Adam optimizer and Sparse Categorical Cross-Entropy loss function

**Applications**
B2B Market: Pet adoption websites can use this model to automate the classification of uploaded pet images, enhancing the user experience and reducing manual effort.
