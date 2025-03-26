# 👗 Fashion Recommender System

The **Fashion Recommender System** is an AI-powered application that suggests similar fashion items based on an uploaded image. It utilizes **ResNet50** for feature extraction and **KNN (K-Nearest Neighbors)** for similarity search.

## 🚀 Features
- **Deep Learning-Based Image Feature Extraction** (ResNet50)
- **Efficient Similarity Matching** using Euclidean Distance & KNN
- **User-Friendly Streamlit Interface** for easy interaction
- **Instant Fashion Recommendations** from a dataset of images
- **Fast Processing** with precomputed embeddings

---

## 🛠️ Technologies Used
- **Python**
- **TensorFlow & Keras** (ResNet50 for feature extraction)
- **Scikit-Learn** (KNN for similarity search)
- **Streamlit** (for web-based UI)
- **OpenCV & PIL** (for image handling)
- **Pickle** (for saving precomputed embeddings)

---

## 📂 Project Structure
```
|-- fashion-recommender-system/
|   |-- images/                # Dataset of fashion images
|   |-- uploads/               # User uploaded images
|   |-- embeddings.pkl         # Precomputed image features
|   |-- filenames.pkl          # Image paths
|   |-- app.py                 # Feature extraction & embedding generation
|   |-- main.py                # Streamlit UI for recommendations
|   |-- test.py                # Testing script for recommendations
|   |-- README.md              # Project Documentation
```

---

## 📌 How to Run
### 1️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 2️⃣ Generate Image Embeddings
```bash
python app.py
```

### 3️⃣ Run the Web App
```bash
streamlit run main.py
```

### 4️⃣ Test the Model
```bash
python test.py
```

---

## 🖼️ How It Works
1️⃣ **Upload an image** (e.g., a shirt, dress, etc.).
2️⃣ **Feature extraction** is performed using ResNet50.
3️⃣ **KNN searches** for the most similar fashion items.
4️⃣ **Top 5 matching images** are displayed as recommendations.

---

## 🎯 Future Enhancements
🔹 **Expand the dataset** for diverse fashion categories.  
🔹 **Improve UI/UX** with a more interactive experience.  
🔹 **Integrate real-world e-commerce APIs** (Amazon, Flipkart).  

👤 Khushbunaz Dalal
💼 AI & Data Science Enthusiast

---

## 🤝 Contribution
Feel free to contribute by submitting **pull requests** or **raising issues**! 🚀

