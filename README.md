# 🤖 Bujji - Emotion-Sensitive Chatbot

**Bujji** is an interactive chatbot that detects a user’s **facial expression** in real-time using a webcam and responds empathetically. Unlike traditional chatbots that rely only on text sentiment analysis, Bujji integrates **facial emotion recognition** with a conversational interface to create a more human-like interaction.

---

## 🌟 Features

* 🎭 **Facial Expression Detection** using DeepFace / CNN models
* 💬 **Emotion-aware conversation replies** (happy, sad, angry, surprised, neutral, etc.)
* 🎨 **Dynamic UI themes** (randomized interface designs)
* 🧠 **Predefined empathetic responses** for each detected emotion
* 🖼️ **Tkinter-based desktop application** with simple chat interface
* 🔄 **Non-repetitive responses** (rotates between multiple replies for variety)

---

## 🧠 Tech Stack

* **Frontend/UI**: Tkinter (Python GUI)
* **Backend**: Python
* **Machine Learning**: DeepFace (Emotion Recognition), CNN architectures
* **Libraries**: OpenCV, Tkinter, DeepFace, Random
* **Dataset Reference**: Facial Expression Dataset (for training emotion models)

---

## 📊 Supported Emotions

The chatbot can detect and respond to the following emotions:

* 😀 Happy
* 😢 Sad
* 😠 Angry
* 😲 Surprised
* 😐 Neutral
* 😨 Fearful
* 🤢 Disgusted

---

## 🧪 How It Works

1. User enters their **name** in the start screen.
2. Webcam captures the user’s face.
3. The system analyzes facial expressions using **DeepFace** to detect the **dominant emotion**.
4. The chatbot greets the user with their **name + emotion**.
5. User can then type messages, and the bot replies empathetically based on the detected emotion.
6. Responses are randomized to avoid repetition and maintain natural flow.

---

## 📁 Project Structure

```
📦 Emotion-Detection-ChatBot  
 ┣ 📜 index.html (optional web interface)  
 ┣ 📜 style.css (optional styling for web UI)  
 ┣ 📜 chatbot.js (optional JS logic for web UI)  
 ┣ 📜 emotion_model.py (ML model logic - optional extension)  
 ┣ 📜 main.py (Tkinter Chatbot with facial expression detection)  
 ┣ 📊 comparison_chart.png (Model comparison chart)  
 ┣ 📷 emotion_faces.png (Sample dataset faces)  
 ┗ 📄 README.md (Documentation)  
```

---

## 🚀 Getting Started

### 🔧 Installation

Make sure you have Python 3.x installed. Then, install the dependencies:

```bash
pip install opencv-python deepface
```

### ▶️ Run the Application

```bash
python main.py
```

---

## 📸 Demo Flow

1. Launch the chatbot.
2. Enter your name → Webcam starts.
3. System detects your **facial expression**.
4. Chatbot greets you with:

   ```
   Bujji: Hello [Your Name], why are you feeling [Emotion] today?
   ```
5. Start chatting — responses adapt to your detected emotion.

---

## 📊 Accuracy Comparison

We experimented with multiple models like **VGG16, ResNet, ANFIS, SVM**, etc. The chosen method (DeepFace + CNN) provides competitive accuracy for real-time emotion recognition.

---

## 🚧 Future Enhancements

* 🎤 **Voice interaction support** (speech-to-text & text-to-speech)
* 🌐 **Web-based chatbot interface**
* 🤖 **Smarter conversational AI integration (transformers)**
* 🧑‍🤝‍🧑 **Multi-user detection** for group conversations

---

## 📜 License

This project is for **academic and research purposes**. Free to use and modify.

