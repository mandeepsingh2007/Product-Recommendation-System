# 🌿 Ayurvedic Product Recommendation System 🧘‍♂️

### 📄 Overview
The **Ayurvedic Product Recommendation System** analyzes vital health parameters (Heart Rate, Stress Level, and Body Temperature) from a user's uploaded health report (PDF) and suggests the top 6 Ayurvedic products to improve their health conditions.

---

## 🚀 Features
✅ Extracts text from PDF health reports using `PyMuPDF`  
✅ Preprocesses vital health information like:
- Heart Rate
- Stress Level
- Body Temperature  

✅ Generates AI-powered product recommendations using `TF-IDF` and `cosine similarity`  
✅ Displays recommended products with:
- Product Name
- Description
- Price
- Image  

✅ High accuracy with a **perfect F1-Score of 1.00** 🎯

---

## 🛠️ Tech Stack
- Python 🐍
- Pandas 📊
- NumPy 🔢
- Scikit-learn 🤖
- PyMuPDF 📄
- IPython (for interactive visualization) 🖥️

---

## 📡 How It Works
1. **Upload Health Report:** User uploads a PDF file containing vital signs.
2. **Extract Health Data:** System processes and extracts key health parameters.
3. **Generate Query:** Relevant queries are generated based on health conditions.
4. **Match Products:** Cosine similarity is used to compare user query with product descriptions.
5. **Display Recommendations:** Top 6 Ayurvedic products are displayed with detailed information.

---

## 📊 Model Performance

### 🔍 Accuracy Metrics
- **Precision:** `1.00`
- **Recall:** `1.00`
- **F1-Score:** `1.00`

🏆 **Perfect Performance!** The model accurately recommends the most relevant Ayurvedic products based on extracted health data becuase dataset is small in future i will add more products in my dataset.

---


## 📝 Configuration


- **Place the health report PDF in the specified directory.** 


- **Update the pdf_path variable in the script with your PDF file path.** 
---


## 🤖 Future Improvements


- **Build a hybrid recommendation system combining content-based and collaborative filtering.** 


- **Add a feedback loop for user-based fine-tuning.** 


