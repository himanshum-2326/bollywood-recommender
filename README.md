# 🎬 Bollywood Movie Recommendation System  
### 👥 Team Project — Lead: **Himanshu Singh Mehra**

A machine learning powered **content-based movie recommendation system** built exclusively for **Bollywood movies**.

This system recommends similar movies based on:

- Genre  
- Story / Overview  
- Director  
- Cast  

Built using **Python, Pandas, Scikit-Learn & Streamlit**.

---

## 🚀 Project Features

- ✔ Content-based ML model using TF-IDF  
- ✔ Cosine similarity for movie matching  
- ✔ Streamlit Web UI  
- ✔ Bollywood-only dataset  
- ✔ Fast and Lightweight  
- ✔ Works locally with CSV dataset  

---

## 📂 Project Structure

```
bollywood-recommender/
│
├── data/
│   └── IMDB-Movie-Dataset(2023-1951).csv   # Dataset included
│
├── src/
│   └── app_streamlit.py                    # Main app
│
├── README.md
└── requirements.txt
```

---

## 📊 Dataset Information

This project uses a curated Bollywood movie metadata dataset containing:

- Movie Name  
- Year  
- Genre  
- Story Overview  
- Director  
- Cast  

Dataset is already included in the `data/` folder.

---

## 🧪 Installation

Install the dependencies:

```
pip install -r requirements.txt
```

---

## ▶️ Running the Application

Run the Streamlit app:

```
python -m streamlit run src/app_streamlit.py
```

App will open at:

```
http://localhost:8501
```

---

## 🧠 How the Recommendation System Works

1. Preprocess movie metadata  
2. Combine fields into a single text “soup”  
3. Convert text → numerical vectors using **TF-IDF**  
4. Calculate similarity using **Cosine Similarity**  
5. Return Top N similar movies for the selected movie  

---

## 📈 Future Improvements

- Add user-based collaborative filtering  
- Add IMDb ratings and popularity filters  
- Add poster images & trailers  
- Deployment on Streamlit Cloud  
- Actor/Director-based filtering  

---

## 👥 Team Members

| Role           | Name                     |
|----------------|--------------------------|
| Team Lead      | **Himanshu Singh Mehra** |
| Member 1       | **Ameer Ali**            |
| Member 2       | **Shashank Mehra**       |
| Member 3       | **Veer pratap singh**    |
| Member 4       | **Sahil vaswani**        |

---

## 🏆 Project Status

✔ Fully Completed  
✔ Successfully Tested  
✔ Fully Working Streamlit UI  
