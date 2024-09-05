# CNN_MRI_Brain

**MRI Brain Tumor Detection using CNN Model**

In this project, I developed a **Convolutional Neural Network (CNN)** to detect brain tumors from MRI images. The goal was to accurately classify MRI scans into two categories: **tumor** and **no tumor**. I utilized a dataset of labeled MRI images to train the CNN model, which is a deep learning architecture widely used for image classification tasks.

### Key Steps:
1. **Data Preprocessing**:
   - Loaded and visualized the MRI images.
   - Resized the images for uniform input size to the CNN model.
   - Normalized pixel values to enhance model performance and reduce computational complexity.
   
2. **Model Architecture**:
   - Built a CNN architecture with multiple convolutional layers, followed by max-pooling layers for feature extraction.
   - Applied **ReLU** activation functions to introduce non-linearity and **Softmax** for binary classification.
   - Utilized **dropout layers** to reduce overfitting and improve generalization.

3. **Training and Evaluation**:
   - Split the dataset into training and validation sets to monitor model performance.
   - Trained the model using **-Binary-cross-entropy loss** and **SGD optimizer** to minimize error and improve accuracy.
   - Evaluated the model based on metrics like **accuracy**, **AUC**, and **ROC** to ensure reliable tumor detection.

4. **Results**:
   - Achieved [insert accuracy] accuracy on the validation set, demonstrating the CNN model’s ability to detect brain tumors effectively from MRI scans.
   - Visualized classification results to further understand the model’s predictions.

### Tools and Libraries:
- **Python**, **Pytorch**, **cv2**, **Seaborn** **Pandas** **NumPy**, and **Matplotlib**.

---

This description highlights the key technical aspects of the project while providing an overview of the approach and results. You can customize the accuracy and other specifics based on the actual outcome of the project.