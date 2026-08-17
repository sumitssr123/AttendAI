# 📸 SnapClass — AI-Powered Face & Voice Recognition Attendance System 🎙️✨

> ⚡ **Automating large-scale classroom attendance through multi-photo face embeddings, SVC classification, and speaker verification.**

---

## 🌐 Live Interactive Demo & Source Notice 🚀

* 🔗 **Live Application Demo:** [Experience SnapClass on Streamlit](https://sumitssr123-attendai-app-gz0hpv.streamlit.app/)
---

## 🎯 The Core Problem & Solution 💡

* ⏳ **The Pain Point:** Calling roll manually for classrooms of 60–70+ students drains valuable lecture time and introduces human error.
* 🧠 **The SnapClass Solution:** Teachers simply snap a few classroom group photos 📷 or activate voice recognition 🗣️. The system extracts biometric embeddings, resolves duplicates across frames, and generates instant attendance records in SQL.

---

## 🔥 Key Features at a Glance 🌟

* 🔐 **Role-Based Authentication:** Secure signup/login with dedicated Teacher & Student dashboards.
* 📸 **Multi-Photo Face Recognition:** Upload multiple row-wise classroom pictures without duplicate marking.
* 🎙️ **Voice Biometric Verification:** Backup attendance identification using voice embedding similarity matching.
* 📲 **Instant QR Enrollment:** Frictionless subject joining via dynamically generated QR codes and invite links.
* 🤖 **Smart Embeddings & SVC Engine:** Deep learning face representations classified using a Support Vector Classifier.
* 📊 **Automated Present/Absent Logs:** Real-time generation of full attendance logs, saved directly to a relational SQL database.

---

## 🛠️ Technology Stack 💻

* 🐍 **Backend & Core ML:** Python, Scikit-Learn (Support Vector Classifier / SVC)
* 👁️ **Computer Vision:** Pretrained Deep Learning Face Recognition & Alignment Pipeline
* 🎧 **Audio Processing:** Speaker Embedding & Voice Similarity Matching
* 🗄️ **Database:** SQL-based Relational Database
* 🎨 **Application Frontend:** Streamlit

---

## 🔄 How It Works: System Workflow ⚙️

**1. Student Onboarding 🧑‍🎓**
* Account Creation ➡️ Face Capture via Webcam ➡️ Face Embedding Storage ➡️ Optional Voice Sample Recording ➡️ Scan Teacher QR to Join Subject.

**2. Teacher Attendance Flow 👩‍🏫**
* Create Subject ➡️ Upload Classroom Group Photos ➡️ AI Detects & Crops Faces ➡️ Embeddings Classified via SVC ➡️ Cross-Photo Duplicate Resolution ➡️ Review Present/Absent Summary ➡️ Commit to SQL.

---

## 📊 Evaluation & Robust Handling 📈

* 🛡️ **Set Membership Handling:** Merges detections from multiple angles into a single unique set of present students.
* 🎯 **Evaluation Metrics:** Evaluated across Precision, Recall, F1-Score, False Acceptance Rate (FAR), and False Rejection Rate (FRR).