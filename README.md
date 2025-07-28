# Book-Recommender-System
A content-based book recommendation system using Python and Jupyter Notebook
# 📚 Book Recommender System

A content-based book recommendation system built using Python, Jupyter Notebook, and machine learning techniques. This project recommends similar books based on a selected book's title using cosine similarity on book features like title, author, and genre.

---

## 🚀 Features

- Recommend top similar books based on input
- Uses content-based filtering with cosine similarity
- Interactive user experience

---

## 📂 Project Structure
book-recommender-system/
│
├── book_recommender_system.ipynb # Main notebook
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── screenshots/ # UI screenshots


---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## 📊 How It Works

1. Loads book dataset
2. Preprocesses data (lowercasing, removing NaNs, etc.)
3. Combines important book features
4. Transforms the data using `CountVectorizer`
5. Computes cosine similarity matrix
6. Recommends books based on user selection

---

## 🖼️ Screenshots

<img width="1366" height="728" alt="Book Recommender system - Personal - Microsoft​ Edge 23-05-2024 21_59_28" src="https://github.com/user-attachments/assets/d301d6c1-c2ef-4674-9b5c-d8064ad1b010" />

<img width="1366" height="728" alt="Book Recommender system - Personal - Microsoft​ Edge 23-05-2024 22_02_11" src="https://github.com/user-attachments/assets/63abbcb2-943c-49f3-819c-da7a14360e35" />

<img width="1366" height="622" alt="Book Recommender system - Personal - Microsoft​ Edge 23-05-2024 22_02_39" src="https://github.com/user-attachments/assets/4e542b86-0e1b-4150-93c8-97193c85245b" />

<img width="1081" height="626" alt="Book Recommender system - Personal - Microsoft​ Edge 23-05-2024 22_04_14" src="https://github.com/user-attachments/assets/3de1125f-0e72-4436-8d0a-fbc564318b7c" />

<img width="1366" height="728" alt="Book Recommender system - Personal - Microsoft​ Edge 23-05-2024 22_04_55" src="https://github.com/user-attachments/assets/0a3937c9-c78f-41de-8267-82a0b93e2ed8" />



✨ Future Improvements:

Deploy with Streamlit or Flask

Integrate external book APIs for real-time data
