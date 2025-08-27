# Virtual Humanoid Female Robot – Demo

🎯 **Project Overview:**  
This AI-powered humanoid robot accepts **text, voice, or gestures** as input and generates **three simultaneous outputs**:  
1. Text displayed on screen  
2. Speech in female voice (using gTTS)  
3. 3D animation updated based on detected emotion (happy, sad, neutral)  

The project demonstrates **multimodal AI, NLP, sentiment analysis, computer vision, full-stack integration, and 3D animation handling**.

---

## **Demo Video:**  
🎥 Watch the robot in action: [YouTube Demo Video]  

---

## **Technologies Used:**  
- **Backend:** Python, Rasa, Flask  
- **Frontend:** HTML, CSS  
- **Computer Vision:** OpenCV, MediaPipe  
- **Natural Language Processing & Sentiment Analysis:** VADER  
- **Text-to-Speech:** gTTS  
- **3D Animation:** `.glb` files, ModelViewer  

---
## **System Architecture (Conceptual):**  
<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/a5e6add2-fe5d-425e-bd79-1dd68c04ad0e" />

## **Features Highlight:**  
- Multimodal input: **text, voice, gestures**  
- Gesture recognition:
  - Thumbs Up  
  - Victory  
  - Open Palm  
  - Fist  
  - No Gesture Detected  
  *(Webcam activates when “gesture” button is clicked)*  
- Synchronous output: **text + voice + animation**  
- Emotion-based animation update: **happy, sad, neutral**  
- Full conversation displayed as **text on screen**  

---

## **Screenshots / GIFs:**  
 
### Emotion-based Animations
<img src="happy.gif" width="600px" alt="Happy Animation"/><br>

<img src="sad.gif" width="600px" alt="Sad Animation"/><br>

<img src="neutral.gif" width="600px" alt="Neutral Animation"/><br>

<img src="voiceinput.gif" width="600px" alt="Voice Input Animation"/>


### Gesture Recognition (Screenshots)
<img src="victory1.png" width="600px" alt="Victory"/> 

<img src="thumbsup.png" width="600px" alt="Thumbs Up"/>

Remaining gestures (Open Palm, Fist, No Gesture Detected) and full robot interactions are demonstrated in the YouTube demo video: Watch Demo

---

## **How to Run the Demo (Important Notes):**  

> ⚡ This repository contains only **demo snippets and documentation**.  
> The **full codebase (including Rasa setup)** is private to avoid misuse and complexity.  

### 🔧 Development Setup (for reference):  

1. **Run Rasa server:**  
   ```bash
   rasa run
   rasa run actions
2. **Run Flask frontend:**
   ```bash
   python app.py

Flask will start a local server at:
👉 http://localhost:5000/ (open this in your browser to view the interface).

Interact with the robot:

- Type text input
- Speak into the microphone for voice input
- Enable webcam and use gestures (thumbs up, victory, palm, fist)

⚡ Note for recruiters / reviewers:

The localhost server runs only on the developer’s machine.

To see the fully working system, please refer to the YouTube demo video: Watch Demo

The full private repo can be shared on request.




