# multilingual_emotion_detection_in_voice


---

## 🌍 Multilingual Emotion Detection in Voice

This project demonstrates how to build a **multilingual voice-based emotion detection system**. The system processes speech audio files, extracts features, and classifies the speaker's emotion using machine learning models.

---

### 🎯 Objective

Detect emotions such as **happy**, **sad**, **angry**, etc., from **speech recordings**, possibly across multiple languages.

---

### 🧰 Tools & Libraries Used

* **Librosa** – for audio feature extraction (e.g., MFCCs)
* **NumPy**, **Pandas** – for data manipulation
* **Scikit-learn** – for machine learning (e.g., SVM, Random Forest)
* **Matplotlib**, **Seaborn** – for visualization
* Possibly **pyAudioAnalysis** or other utilities for audio handling

---

### 📁 Dataset

The notebook likely works with datasets such as:

* **RAVDESS**, **CREMA-D**, or similar datasets that include labeled emotions in multiple languages or accents.
* Audio files (.wav) with labeled emotional content.

---

### 🔍 Workflow Summary

1. **Loading Audio Data**

   * Load `.wav` files and corresponding emotion labels.

2. **Feature Extraction**

   * Extract features like MFCC (Mel Frequency Cepstral Coefficients) using `librosa`.

3. **Data Preprocessing**

   * Normalize features, encode labels, split into training and testing sets.

4. **Model Training**

   * Train classifiers (e.g., SVM, Random Forest) on the extracted features.

5. **Evaluation**

   * Use accuracy, confusion matrix, classification report to evaluate performance.

6. **Visualization**

   * Show feature distributions, confusion matrices, and emotion prediction results.

---

### 🚀 How to Run

1. Install dependencies:

   ```bash
   pip install librosa scikit-learn pandas matplotlib seaborn
   ```

2. Run the notebook cell by cell in Jupyter Notebook or JupyterLab.

---

### 📊 Potential Output

* Model accuracy score on test set
* Confusion matrix showing how well each emotion is detected
* Sample predictions from audio clips

---

### 🔮 Possible Extensions

* Add support for real-time emotion detection via microphone
* Integrate deep learning models like LSTM or CNN
* Expand to include more diverse languages and dialects

---

