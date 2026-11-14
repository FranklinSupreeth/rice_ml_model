# 🌾 Grain Vision – Rice Prediction Model

A machine learning web app that identifies the **variety of a rice grain** from an image and reports how confident the model is in its prediction.

### 🔗 Live Demo
**👉 [rice-ml-model-2-albz.onrender.com](https://rice-ml-model-2-albz.onrender.com/)**

> Hosted on Render's free plan — the first load may take 30–60 seconds while the server wakes up.

---

## ✨ Features

- 📤 **Image upload** – choose a JPG or PNG image of a rice grain
- 🌾 **Single grain or sample** – works with one grain or a group of grains
- 🤖 **Variety classification** – the model predicts the rice variety
- 📊 **Confidence score** – shows how sure the model is about the result
- 📱 **Responsive UI** – works on desktop and mobile

---

## 🖥️ How to Use

1. Open the [live demo](https://rice-ml-model-2-albz.onrender.com/).
2. Click **"Click to choose a rice grain image"** and select a JPG or PNG file.
3. Click **Classify Grain**.
4. View the predicted rice variety and its confidence score.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Language | Python |
| Machine Learning | Image classification model |
| Web Framework | Flask |
| Frontend | HTML, CSS, JavaScript |
| Deployment | Render |

---

## 📁 Project Structure

```
rice-prediction/
├── app.py               # Web app and prediction route
├── requirements.txt     # Python dependencies
├── model/               # Trained model files
├── templates/           # HTML pages
├── static/              # CSS, JS and images
└── README.md
```

---

## ⚙️ Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>

# 2. Create and activate a virtual environment
python -m venv venv
# Windows:
venv\Scripts\activate
# macOS / Linux:
source venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Start the app
python app.py
```

Then open **http://localhost:5000** in your browser.

---

## 🚀 Deployment (Render)

| Setting | Value |
|---|---|
| Service type | Web Service |
| Build Command | `pip install -r requirements.txt` |
| Start Command | `gunicorn app:app` |

---

## ⚠️ Disclaimer

This project is built for learning and academic purposes. Predictions may not be 100% accurate, especially for blurry, poorly lit or mixed-variety images.

---

## 👤 Author

**Franklin Supreeth**
MCA – Kristu Jayanti University, Bengaluru

⭐ If you found this project useful, consider giving it a star!
