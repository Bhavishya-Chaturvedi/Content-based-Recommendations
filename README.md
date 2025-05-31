# 🎬 Movie Recommender System

A simple and interactive **Movie Recommender System** built using **Streamlit** and powered by **machine learning**. This app recommends movies based on similarity scores and fetches movie posters using **TMDb API**.

---

## 🚀  Demo

![image](https://github.com/user-attachments/assets/b91a598e-8289-4ff8-b291-771caa1d9ef9)
![image](https://github.com/user-attachments/assets/fdf9bad0-d61a-4965-ac33-94a4ae69c259)
*poster may not be visible due to API rate limits
---

## 📁 Project Structure

├── .gitignore # Specifies files ignored by Git (e.g., pickle files)

├── Movie-recommender-system.html # Exported version of the notebook

├── Movie-recommender-system.ipynb# Jupyter Notebook version of the project

├── README.md # You're here!

├── app.py # Streamlit app to run the recommender system


---

## 🧠 How It Works

- The movie data is preprocessed and stored in `.pkl` (pickle) files.
- On selecting a movie from the dropdown, the app:
  1. Calculates similarity scores
  2. Recommends top 5 similar movies
  3. Fetches and displays posters via TMDb API

---

## 🛠️ Tech Stack

- Python 🐍
- Pandas
- Scikit-learn
- Streamlit
- TMDb API

---

## 🗂️ Note on Pickle Files

📦 The required `.pkl` files (`movies_dict.pkl`, `similarity.pkl`) are **ignored** in the repository via `.gitignore` due to **upload size restrictions** on GitHub.

> 🔐 To run the app locally, you will need to generate or request these files. You can use the **.ipynb** file for generating them 

---

## ⚙️ How to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Movie-Recommender-System.git
   cd Movie-Recommender-System


   ```bash
   streamlit run app.py



---

If you like this project, ⭐️  it to find it easy.  
