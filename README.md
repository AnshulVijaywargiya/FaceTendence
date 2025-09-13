# FaceTendence – AI-Powered Face Recognition Attendance System

*FaceTendence* is a smart, automated attendance management system that leverages *Face Recognition* and *OpenCV* to make attendance tracking seamless, secure, and efficient.  
The system is deployed with a backend + frontend architecture and integrates with a *MySQL database* for persistent storage of attendance records.

---

## 📌 Overview

Traditional attendance systems are slow, error-prone, and labor-intensive. *Attendify* automates the process with *real-time face recognition* and an intuitive web interface.  
This project is ideal for classrooms, workplaces, and event tracking where accuracy and time efficiency are crucial.

---

## ✨ Features

- *🔍 Face Recognition:* Detects and recognizes faces with high accuracy.
- *⚡ Real-time Processing:* Instantly marks attendance as faces are detected via live camera feed.
- *🖥 Web Interface:* Simple login system for admins and users with easy attendance viewing.
- *💾 Database Integration:* Attendance data is stored in a MySQL database for secure and reliable record-keeping.
- *⚙ Customizable:* Adjustable recognition thresholds, camera sources, and user enrollment.
- *🔒 Privacy-Focused:* Facial data is processed securely without unnecessary external storage.

---

## 🗂 Project Structure

```plaintext
📂 Smart-Attendance-System-Backend
 ├── 📂 Web                    # Frontend web interface (HTML/CSS/JS)
 ├── 📂 test_images           # Sample images for testing
 ├── 📓 Good_SAS.ipynb        # Main notebook with working SAS pipeline
 ├── 📓 Individual_brightness.ipynb
 ├── 📓 Making_Pickle.ipynb   # Generates pickle files for face encodings
 ├── 📓 Optimal_face_recog.ipynb
 ├── 📓 Optimal_face_recog_only_livefeed.ipynb
 ├── 📓 Optimal_face_recog_with_two_pickles.ipynb
 ├── 📓 code_with_using_pkl.ipynb
 └── 📄 README.md
