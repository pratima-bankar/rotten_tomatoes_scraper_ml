# 🎬 Movie Sentiment Prediction: Scraping & Machine Learning on Rotten Tomatoes

## 📌 Project Overview
This project focuses on **predicting audience sentiment** (positive or negative) for movies using **web scraping** and **machine learning**. It involves scraping **Rotten Tomatoes** for movie data, preprocessing it, and training a classification model to predict whether a movie's audience score is positive (≥50%) or negative (<50%).

## 🚀 Features & Workflow

### **📌 Step 1: Web Scraping Rotten Tomatoes**  
✅ **Scraped at least 500 movies** from Rotten Tomatoes using **Selenium & BeautifulSoup**  
✅ **Extracted movie details**, including:  
   - 🎬 **Title, Genre, Director, Cast, Release Year, Duration**  
   - ⭐ **Audience Score & Critic Score**  
   - 🎭 **Genre Trends & Review Patterns**  
✅ **Stored the data in a structured CSV file** for further analysis  

### **📌 Step 2: Machine Learning for Audience Sentiment Prediction**  
✅ **Preprocessed and cleaned the scraped data** for training  
✅ **Binarized the Audience Score**:  
   - **Positive (≥50%)** 🎉  
   - **Negative (<50%)** 💔  
✅ **Split dataset into training (75%) & testing (25%) sets**  
✅ **Engineered features such as:** Genre, Critic Score, Director’s influence, Cast popularity, etc.  
✅ **Trained multiple models (Logistic Regression, Random Forest, XGBoost, SVM)**  
✅ **Hyperparameter tuning for best performance**  
✅ **Evaluated model performance using Accuracy, Precision, Recall**  

## 📂 Files & Code Structure
```
📂 movie-sentiment-prediction
│── 📄 README.md                # Project documentation
│── 📂 notebooks                 # Jupyter Notebooks for scraping & ML
│   ├── Web_Mining_Extraction_File .ipynb   # Scraping movie data from Rotten Tomatoes
│   ├── Webmining_Model_Training.ipynb     # Preprocessing & Training ML model
│── 📂 data                      # Raw & processed datasets
│── 📂 models                    # Trained machine learning models
```

## 🎯 How to Run the Project

### **📌 Step 1: Setup the Environment**
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/movie-sentiment-prediction.git
   cd rotten_tomatoes_scraper_ml
   ```

### **📌 Step 2: Run Web Scraping Notebook**
Execute `Web_Mining_Extraction_File .ipynb` to scrape and store movie data.

### **📌 Step 3: Train and Evaluate the Model**
Run `Webmining_Model_Training.ipynb` to:  
1. Load and preprocess the dataset  
2. Train & tune machine learning models  
3. Evaluate performance on test data  

### **📌 Step 4: Make Predictions**
After training, use the model to predict sentiment for new movies.

## 🏆 Results & Insights  
- Identified **key factors influencing audience sentiment**.  
- **Compared different models** to determine the best predictor.  
- **Cleaned and labeled dataset** for future analysis.  
