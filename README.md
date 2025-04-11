# Attendify 🎓 - Face Recognition-Based Attendance System

Attendify is a Python-based desktop application that uses **face recognition** to automate student attendance. It combines a GUI built with **Tkinter**, facial recognition via **face_recognition** and **OpenCV**, and student data storage using **SQLite**.

> ⚠️ The UI is designed to show the idea's implementation space and is kept minimal.

_______________________________________________________________________

## 💡 Features

- 🎥 Real-time face recognition using webcam
- 📝 Add students by uploading an image
- 🗑️ Remove students from the database
- 💾 Stores face encodings and student data in SQLite
- 🧠 Auto-detects and labels known/unknown faces live

_______________________________________________________________________

## 🛠️ Tech Stack

- **Python**
- **Tkinter** for GUI
- **OpenCV** for webcam feed
- **face_recognition** for face detection and encoding
- **Pillow (PIL)** for image handling
- **SQLite3** for lightweight local database
- **pickle** for serializing face encodings

_______________________________________________________________________

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/geo-cherian-mathew-2k28/attendify.git
   cd attendify
2. **Install dependencies**
    ```bash
    pip install face_recognition opencv-python pillow
3.**Run the application**
    ```bash
    python attendify.py
_______________________________________________________________________
📸 How It Works
Launch the app — it opens the webcam and starts detecting faces.

Click "Add Students" to input a name, ID, and upload a face image.

Face encodings are stored in the SQLite database.

Recognized faces are marked in the webcam feed with names; unknown ones are labeled as "Unknown."

You can also remove students from the database using the UI.

🧪 Demo Screens
💻 The UI is simple and designed to demonstrate functionality.

Webcam feed area

Add/Remove student window

Real-time face detection with label overlay

🧠 Future Improvements
📅 Date-based attendance logs

📊 Attendance statistics dashboard

🔐 Role-based access (admin/student)

🌐 Web-based version
_______________________________________________________________________
Author
Developed by Geo Cherian Mathew
🌐 LinkedIn: https://in.linkedin.com/in/geo-cherian-mathew-2a9b17330
_______________________________________________________________________

