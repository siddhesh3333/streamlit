# 🌼 Iris Species Classifier – Streamlit Web App

This repository contains an interactive **machine learning web application** built using **Streamlit**. The app predicts the species of an iris flower based on its sepal and petal measurements using a **Random Forest Classifier** trained on the classic **Iris dataset** from scikit-learn.

---

## 🚀 Features

✅ Loads and preprocesses the Iris dataset  
✅ Trains a Random Forest Classifier automatically  
✅ Interactive sliders for input feature selection  
✅ Real-time species prediction  
✅ Lightweight, fast, and beginner-friendly  
✅ Demonstrates integration of pandas, scikit-learn, and Streamlit  

---

## 🧠 Tech Stack

| Component | Purpose |
|----------|---------|
| **Python** | Core language |
| **pandas** | Data handling |
| **scikit-learn** | ML model + dataset |
| **Streamlit** | Web UI framework |

---

## 📦 Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

2. (Optional but recommended) Create a virtual environment
python -m venv .venv


Activate it:

Windows

.venv\Scripts\activate


macOS / Linux

source .venv/bin/activate

3. Install dependencies
pip install streamlit pandas scikit-learn

▶️ Run the Application
streamlit run app.py


Once running, your browser will open automatically.
If not, navigate to the URL shown in the terminal (usually):

http://localhost:8501

🏗 How It Works
✅ Load Dataset

Iris dataset imported from scikit-learn

Converted into a pandas DataFrame

Cached for performance using @st.cache_data

✅ Train Model

RandomForestClassifier trained on startup

Uses four features:

Sepal length

Sepal width

Petal length

Petal width

✅ User Interaction

Sidebar sliders accept measurement inputs

Values are fed into the model for prediction

✅ Output

Displays predicted species name dynamically

📊 Example Prediction Output
Prediction
The predicted species is: versicolor

🧩 Future Enhancements (Optional Ideas)

✨ Show prediction probabilities
✨ Add data visualizations
✨ Display confusion matrix and accuracy
✨ Allow model selection from UI
✨ Improve UI styling and descriptions

📁 Project Structure
.
├── app.py          # Main Streamlit application
├── README.md       # Project documentation

📝 Notes

🔹 This project is intended for learning and demonstration
🔹 Typos in output string can be corrected if desired
🔹 No dataset files are required—loaded automatically

📜 License

This project is open-source and available for personal or educational use.
If publishing publicly, consider adding a license (MIT recommended).

⭐ Contributions

Feel free to:

Fork the repo

Submit pull requests

Open issues for ideas or improvements

If you like the project, star the repository! ⭐

🙌 Acknowledgments

Dataset courtesy of:

scikit-learn Iris Dataset (Fisher, 1936)

Built using:

Streamlit

scikit-learn

pandas
