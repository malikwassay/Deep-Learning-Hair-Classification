**Hair Type Classification using Deep Learning**
This project explores hair type classification using deep learning models, namely InceptionV3, VGG16, and AlexNet. The dataset contains images of various hair types (Curly, Straight, Kinky, Wavy, Dreadlocks), and the models are trained and evaluated to classify them effectively.

**Features**
  - **Pre-trained Models:** Uses InceptionV3 and VGG16 pre-trained on ImageNet.
  - **Custom Model:** AlexNet implemented from scratch.
  - **Data Augmentation:** Employs robust data augmentation techniques for better generalization.
  - **Evaluation Metrics:** Accuracy, Precision, Recall, F1 Score, and Confusion Matrix.
  - **Dataset Splitting:** Organized into training, validation, and testing datasets.

**Summary Table**
**Model Performance Metrics**
The summary table highlights the performance of the three models based on their classification metrics:

![image](https://github.com/user-attachments/assets/c8bb3592-a3f0-4e52-97d6-0c7e991f7015)

**Installation**
**Clone the repository:**

```bash
git clone https://github.com/malikwassay/Deep-Learning-Hair-Classification.git
cd hair-type-classification
```

```bash
pip install -r requirements.txt
```


**Dataset**
Data set can be downloaded through https://www.kaggle.com/datasets/kavyasreeb/hair-type-dataset

**Results**
**InceptionV3**:
Accuracy: 92%
Best Performance: Dreadlocks (F1 Score: 96%)

**VGG16:**
Accuracy: 79%
Best Performance: Straight (Precision: 100%)

**AlexNet:**
Accuracy: 71%
Best Performance: Straight (Precision: 88%)

