# 🌸 Flower Classification with EfficientNet

Deep learning image classification project trained on the **104 Flower Species dataset** from Kaggle.

## 🚀 Overview
- 🖼 104 Flower Classes
- 🧠 EfficientNetB0 (Transfer Learning)
- ⚙️ TensorFlow / Keras
- 📦 TFRecord Dataset
- 💾 Saved in modern `.keras` format

---

## 📊 Model Training

The model was trained on Kaggle using GPU/TPU acceleration.

Steps:
1. Load TFRecord dataset
2. Preprocess images (224x224)
3. Train EfficientNetB0
4. Generate submission file

---

## 🌐 Streamlit Demo

Run locally:

```bash
pip install -r requirements.txt
streamlit run app.py

