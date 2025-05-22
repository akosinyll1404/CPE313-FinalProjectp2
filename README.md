# YOLOv11-Based Employee Activity Classifier
![GIF](assets/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif)
A Streamlit web application using a custom-trained YOLOv11 model (`best_path.pt`) to classify employee states as **"working"** or **"not working"** from uploaded images and videos. This project leverages computer vision to support real-time monitoring of workplace activity and well-being.

## 📌 Project Objective

Maintaining employee satisfaction and productivity is essential to organizational success. Traditional monitoring methods often lack real-time responsiveness. This system introduces an Computer vision approach to detect anomalies in employee behavior, enabling proactive support and creating a more responsive and employee-centric work environment.

## 🚀 Features

- 🔍 Real-time classification of uploaded images and videos  
- 📷 Detects "working" vs. "not working" states based on activity and facial expression  
- 🖥️ Simple, interactive Streamlit interface  
- 🧠 Powered by a custom YOLOv11 model (`best_path.pt`)

## 📁 File Structure

```
main/
├── assets/              # Image and video assets for demo or UI
├── notebooks/           # Jupyter notebooks (e.g., training, evaluation)
├── .gitattributes       # Git LFS configuration
├── README.md            # Project documentation
├── best.pt              # Trained YOLOv11 model (via Git LFS)
├── main_app.py          # Streamlit web application
├── requirements.txt     # Python dependencies

````

## 📷 Usage

* Upload an image or video file via the Streamlit interface.
* The model will process the file and display predictions.
* Results are visualized with annotated bounding boxes and labels.

### Try it here.[FinalProjectDeployment.](https://cpe313-finalproject-by-popenyll.streamlit.app/)

## 🧠 Model

The model is a custom YOLOv11 object detector trained to distinguish between working, idle and non-working states based on employee posture, gestures, and facial cues.

## 🛡️ License

This project is licensed under the MIT License.

---

**Author:** Jann Moises Nyll B. De los Reyes
**Contact:** \[[qjmnbdelosreyes@tip.edu.ph](qjmnbdelosreyes@tip.edu.ph)]



---
