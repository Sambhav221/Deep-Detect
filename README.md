# DeepDetect

A Flask-based web application for detecting deepfake videos using face recognition and machine learning. The system allows users to upload videos and receive **real/fake predictions** with visual confidence metrics including **pie charts** and **model comparison graphs**.

---

## 🚀 Features

- Upload video and detect deepfakes
- Frame-by-frame face detection using `dlib`
- Real-time prediction with accuracy score
- Pie chart visualizations and model comparisons
- Clean and interactive web interface (Flask)

---

## ⚙️ Installation

1. **Clone the Repository**

```bash
git clone https://github.com/Sambhav221/DeepFake_Detection1.git
cd DeepFake_Detection1
```

2. **Create and Activate Virtual Environment (Recommended)**

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

3. **Install Python Dependencies**

```bash
pip install -r requirements.txt
```

---

## 🧠 dlib Installation on Windows

“Due to GitHub file size limits, the dlib package (.whl) is provided instead of source files. Please install it manually using the command below.”

Since `dlib` may not install via pip directly on Windows, use this precompiled wheel:

📦 [Download dlib-19.22.99 .whl](https://drive.google.com/file/d/1NCPdZ1FbInnFQpZuUFgywCbzGxCFkuWp/view?usp=sharing)

Once downloaded, install it using this command:

```bash
pip install "C:\Users\KIIT0001\Downloads\dlib-19.22.99-cp310-cp310-win_amd64.whl"
```

✅ To verify installation:

```bash
python -c "import dlib; print(dlib.__version__)"
```

Expected output:
```
19.22.99
```

---
⚠️ Note: This wheel file is for Windows users only. If you're on macOS or Linux, please refer to the [official dlib installation guide](http://dlib.net/).

## ▶️ Run the Application

```bash
python server.py
```

Then open your browser and go to:  
[http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 📁 Folder Structure

```
DeepFake_Detection1/
│
├── server.py              # Flask backend
├── templates/             # HTML UI pages
├── static/                # CSS, JS, images
├── uploads/               # Uploaded video storage
├── requirements.txt       # Python dependencies
├── README.md              # This file
└── ...
```

---

## 🙌 Credits

- Developed by Sambhav Kumar Sahoo
- Built using: `Flask`, `dlib`, `OpenCV`, `matplotlib`, `scikit-learn`, and more

---

## 📬 Contact

Feel free to connect or raise an issue if you face any problem.  
📧 Email: [sambhavsahoo109@gmail.com]  
🔗 LinkedIn: [https://www.linkedin.com/in/sambhav-sahoo-47ab0a289]
