# Indian-Art-Style-Classification

# 🎨 Indian Folk Art Classifier using EfficientNet and Gradio

This project is a deep learning-based image classifier designed to recognize traditional Indian folk art styles. The model uses **EfficientNet** for feature extraction and is deployed using **Gradio** to create a user-friendly web interface.

---

## 📌 Features

- Classifies paintings into **8 Indian folk art styles**:
  - Gond Painting
  - Kalighat Painting
  - Kangra Painting
  - Kerala Mural
  - Madhubani Painting
  - Mandana Art Drawing
  - Pichwai Painting
  - Warli Painting
- Provides a **confidence score** for the prediction.
- Returns **"None of the above"** if prediction confidence is low (< 50%).
- Lightweight, interactive **Gradio-based frontend** for easy access.

---

## 🚀 Demo

You can run the web app using:

```bash
python app.py
