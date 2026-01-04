#  Hand Gesture Recognition using SVM

**Machine Learning Project | Prodigy Infotech Internship**

##  Project Overview

This project implements a **Hand Gesture Recognition system** using a **Support Vector Machine (SVM)** classifier.
The model is trained on grayscale hand gesture images from the **LeapGestRecog dataset** and classifies different gesture categories based on pixel-level features.

The project focuses on **traditional machine learning techniques** for image classification without using deep learning models.

---

##  Dataset

* **Dataset Name:** Leap Gesture Recognition (LeapGestRecog)
* **Source:** Kaggle
* **Path Used:**

  ```
  /kaggle/input/leapgestrecog/leapGestRecog
  ```
* **Structure:**

  ```
  leapGestRecog/
  ├── 00/
  │   ├── 01_palm/
  │   ├── 02_l/
  │   ├── ...
  ├── 01/
  ├── ...
  ```

Each subject folder contains multiple gesture classes.

---

##  Approach

### 1. Image Loading & Preprocessing

* Images loaded in **grayscale**
* Resized to **64 × 64**
* Flattened into 1D feature vectors
* Limited to **200 images per gesture class** to balance the dataset

### 2. Feature Representation

* Pixel intensity values used as features
* No deep learning or feature extractors (pure classical ML)

### 3. Model Training

* **Algorithm:** Support Vector Machine (SVM)
* **Kernel:** Linear
* **Train–Test Split:** 80% training, 20% testing

### 4. Evaluation

* Accuracy score
* Detailed classification report (precision, recall, F1-score)

---

##  Tech Stack

* **Python**
* **OpenCV**
* **NumPy**
* **Matplotlib**
* **scikit-learn**

---

##  How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/gesture-recognition-svm.git

# Open the notebook or script in Kaggle or local environment
# Ensure dataset is placed correctly

# Run the script
python gesture_recognition.py
```

---

##  Output

* Displays total number of samples
* Number of gesture classes
* Model accuracy
* Full classification report

Example:

```
Accuracy: XX.XX%
```

---

##  Key Learnings

* Image preprocessing using OpenCV
* Handling multi-class image classification
* Applying SVM to real-world image datasets
* Dataset balancing for fair training
* Performance evaluation using classification metrics

---

##  Future Enhancements

* Use **HOG** or **SIFT** features
* Experiment with **RBF kernel**
* Compare with **CNN-based models**
* Real-time gesture recognition using webcam

---

##  Acknowledgements

* **Kaggle** – Leap Gesture Recognition Dataset
* **Prodigy Infotech** – Machine Learning Internship

---

##  Contact

Feel free to connect on LinkedIn or explore more ML projects on GitHub!

---

