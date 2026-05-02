# 🎓 SnapClass – AI Attendance System

SnapClass is an AI-powered attendance system that uses **Face Recognition + Voice Recognition** to automate classroom attendance.
Built using **Streamlit, Python, and Supabase**, it provides a seamless experience for both teachers and students.

---

## 🚀 Live Demo

👉 **Try the app here:**
🔗 https://snapclass-main12.streamlit.app

---

## ✨ Features

### 👨‍🏫 Teacher Panel

* Create and manage subjects
* Take attendance using:

  * 📸 Face Recognition (image upload)
  * 🎤 Voice Recognition (audio input)
* View attendance records
* Share subject codes with students

### 👨‍🎓 Student Panel

* Login using Face ID
* Register using:

  * Face embedding
  * Optional voice enrollment
* Join subjects via code

---

## 🧠 AI Capabilities

* Face embeddings using `dlib`
* Voice embeddings for identification
* Machine learning classifier (SVM)
* Real-time attendance detection

---

## 🛠️ Tech Stack

* **Frontend:** Streamlit
* **Backend:** Python
* **Database:** Supabase
* **ML Libraries:**

  * dlib
  * scikit-learn
  * numpy

---

## 📂 Project Structure

```
snapClass/
│
├── src/
│   ├── screens/
│   ├── components/
│   ├── pipelines/
│   ├── database/
│   └── ui/
│
├── app.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repo

```bash
git clone https://github.com/your-username/snapClass.git
cd snapClass
```

### 2️⃣ Create virtual environment

```bash
python -m venv venv
source venv/bin/activate
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the app

```bash
streamlit run app.py
```

---

## 🔐 Environment Variables

Create a `.env` file and add:

```
SUPABASE_URL=your_url
SUPABASE_KEY=your_key
```
---

## 📌 Future Improvements

* Real-time video attendance
* Advanced voice recognition
* Analytics dashboard for teachers
* Mobile app integration

---

## 🤝 Contributing

Feel free to fork the repo and submit pull requests!

---

## 📄 License

This project is for educational purposes.

---

## 👨‍💻 Author

**Nakul Charak**
