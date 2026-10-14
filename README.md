<div align="center">
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=800&size=32&duration=3500&pause=1500&color=fa71cd&center=true&vCenter=true&width=900&height=70&lines=%F0%9F%8E%99%EF%B8%8F%20Voice%20Emotion%20Detection" alt="Voice Emotion Detection"/>

<b><i>Recognise emotions from speech with deep learning</i></b>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=36BCF7&center=true&vCenter=true&width=700&lines=%F0%9F%8E%99%EF%B8%8F%20Hear%20the%20emotion;%F0%9F%98%80%20Happy%20%C2%B7%20%F0%9F%98%A2%20Sad%20%C2%B7%20%F0%9F%98%A0%20Angry%20%C2%B7%20%F0%9F%98%90%20Neutral;%F0%9F%A7%A0%20Deep%20learning%20on%20audio%20features" alt="Typing SVG" />

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/> <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask"/> <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow"/> <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" alt="Keras"/> <img src="https://img.shields.io/badge/Librosa-4B8BBE?style=for-the-badge&logo=python&logoColor=white" alt="Librosa"/> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn"/> <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>

<img src="https://img.shields.io/github/stars/PreciousBharath/VOICE-EMOTION-DETECTION?style=social" alt="stars"/> <img src="https://img.shields.io/github/forks/PreciousBharath/VOICE-EMOTION-DETECTION?style=social" alt="forks"/> <img src="https://img.shields.io/github/last-commit/PreciousBharath/VOICE-EMOTION-DETECTION?style=flat-square&color=blueviolet" alt="last commit"/> <img src="https://img.shields.io/github/repo-size/PreciousBharath/VOICE-EMOTION-DETECTION?style=flat-square&color=success" alt="repo size"/>
</div>

---

## 🎙️ About the Project

Upload a voice clip and the app recognises the speaker's **emotion — happy, sad, angry or neutral**. Audio features (MFCCs) are extracted with **Librosa** and classified by a **Keras deep-learning model**, all wrapped in a Flask web app with login.

## ✨ Key Features

- 🎧 Upload a speech clip for analysis
- 🎼 **MFCC feature extraction** with Librosa
- 🧠 Keras model `voice_emotion_model.h5`
- 🏋️ Training (`train_voice_emotion.py`) & CLI prediction (`predict_voice_emotion.py`) scripts
- 🔐 Signup / login + about page

## 🧠 How It Works

```mermaid
flowchart LR
V["🎙️ Voice Clip"] --> F["🎼 MFCC Features"] --> M["🧠 Deep Learning Model"] --> E{"😀😢😠😐 Emotion"}
```

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Language | Python 3 |
| Audio | Librosa |
| Deep Learning | TensorFlow / Keras |
| Web | Flask · HTML5 · CSS3 |

## 📂 Project Structure

```text
VOICE-EMOTION-DETECTION/
├── app.py · app1.py
├── train_voice_emotion.py
├── predict_voice_emotion.py
├── voice_emotion_model.h5 · label_encoder.pkl
├── requirements.txt
└── templates/ (index, login, signup, result, about)
```

## 🚀 Getting Started

```bash
git clone https://github.com/PreciousBharath/VOICE-EMOTION-DETECTION.git
cd VOICE-EMOTION-DETECTION
pip install -r requirements.txt
python app.py
```

## 🤝 Contributing

Contributions, issues and feature requests are welcome! Feel free to ⭐ star the repo and open a pull request.

## 👨‍💻 Author

<div align="center">

**Bharath** — Software Developer · Project Engineer · Technical Trainer

<a href="https://github.com/PreciousBharath"><img src="https://img.shields.io/badge/GitHub-PreciousBharath-181717?style=for-the-badge&logo=github"/></a>
<a href="https://linkedin.com/in/connectbharath"><img src="https://img.shields.io/badge/LinkedIn-connectbharath-0A66C2?style=for-the-badge&logo=linkedin"/></a>

### 🍔 EAT · 😴 SLEEP · 💻 CODE · 🔁 REPEAT

⭐ **If you found this project useful, give it a star!** ⭐

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

</div>
