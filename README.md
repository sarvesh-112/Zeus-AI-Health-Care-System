
Personalized Medical Recommendation System using Machine Learning

An intelligent, interactive healthcare assistant that predicts diseases based on user-provided symptoms and offers personalized recommendations including medications, precautions, diets, and workouts. This web-based system uses a trained Support Vector Machine (SVM) model and intuitive UI for efficient and accurate health predictions.

---

## 🚀 Live Demo (Locally)

> 💬 Try symptoms like:

headache, high\_fever, nausea, pain\_behind\_the\_eyes, muscle\_pain


> 🎯 Output → **Predicted Disease:** Malaria



## 📌 Features

✅ Predicts disease from multiple user-input symptoms  
✅ Smart dropdown with auto-complete for 130+ symptoms  
✅ Real-time speech recognition input  
✅ Trained SVM model for high accuracy  
✅ Outputs:
- Disease description  
- Medications  
- Precautions  
- Diet suggestions  
- Workout recommendations  

✅ Responsive Bootstrap UI  
✅ Easy local deployment  



## 🛠️ Tech Stack

| Layer          | Technology                |
|----------------|----------------------------|
| Frontend       | HTML, CSS, Bootstrap       |
| Backend        | Python, Flask              |
| Machine Learning | Scikit-learn (SVM Classifier) |
| Data Storage   | CSV files                  |
| Deployment     | Localhost (Render-ready)   |



## 🔍 Project Workflow

1. **Input:**  
   - User types or speaks symptoms.  
   - Autocomplete dropdown makes entry fast and accurate.

2. **Preprocessing:**  
   - Symptoms converted into a binary vector using `symptoms_dict`.

3. **Prediction:**  
   - Vector fed to a trained SVM classifier (`svc.pkl`).  
   - Predicted label is mapped to disease name.

4. **Output:**  
   - Disease Name  
   - Description (`description.csv`)  
   - Medications (`medications.csv`)  
   - Precautions (`precautions_df.csv`)  
   - Diet (`diets.csv`)  
   - Workout (`workout_df.csv`)

---

## 📂 Directory Structure

```

├── app.py
├── models/
│   └── svc.pkl
├── datasets/
│   ├── description.csv
│   ├── precautions\_df.csv
│   ├── medications.csv
│   ├── diets.csv
│   └── workout\_df.csv
├── templates/
│   ├── index.html
│   ├── about.html
│   ├── contact.html
│   ├── developer.html
│   └── blog.html
├── static/
│   └── image.png
├── requirements.txt
└── README.md

```

---

## 🧪 Sample Use Case

### 🧾 Input:
```

Symptoms: headache, high\_fever, nausea, pain\_behind\_the\_eyes, muscle\_pain

````

### ✅ Output:
- **Disease:** Malaria  
- **Description:** Malaria is a mosquito-borne disease caused by parasites...  
- **Precautions:** Use mosquito repellent, Wear full sleeves...  
- **Medications:** Chloroquine, Artemisinin-based combination therapy (ACT)...  
- **Diet:** Hydrating fluids, fresh fruits, easily digestible food...  
- **Workout:** Light walking, rest-intensive routine...

---

## ⚙️ Installation

```bash
# Clone this repository
git clone https://github.com/your-username/medical-diagnosis-ml.git
cd medical-diagnosis-ml

# Set up a virtual environment
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py

# Open in browser
Deployed link: https://zeus-ai-health-care-system.onrender.com/

````

---

## 📜 Requirements

```txt
Flask
pandas
numpy
scikit-learn
```

You can install them with:

```bash
pip install -r requirements.txt
```

---

## 👨‍💻 Developer

| Name            | Role                          |
| --------------- | ----------------------------- |
| Sarvesh Ganesan | Creator & Fullstack Developer |

---

## 📢 Disclaimer

This application is meant for **educational and informational purposes only**. It is **not a replacement for professional medical advice, diagnosis, or treatment**. Always consult your doctor for accurate medical guidance.

---

## 📄 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

```

---

✅ **Ready to copy-paste into your `README.md` file**  
Let me know if you'd like me to generate `requirements.txt`, deployment setup, or GitHub tags (badges) too!
```
