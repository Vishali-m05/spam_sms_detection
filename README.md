
## 📩 Spam SMS Detection

This project focuses on detecting spam messages from a collection of SMS text data using natural language processing (NLP) and machine learning models.

### 📌 Abstract

The goal of this project is to automatically identify whether a given SMS message is spam or not. This can help in improving email/SMS filters and in securing user communication channels from unwanted messages. The dataset used is a collection of SMS messages labeled as "ham" (legitimate) or "spam" (unwanted). The notebook walks through the steps of data preprocessing, vectorization, model training, and evaluation.

---

### 🛠️ Technologies Used

* **Python** 🐍
* **Pandas** – For data manipulation
* **NumPy** – For numerical computations
* **Matplotlib** & **Seaborn** – For data visualization
* **Sklearn** – For machine learning models and preprocessing
* **CountVectorizer** – To convert text into numerical features
* **Multinomial Naive Bayes** – As the classification model

---

### 📊 Dataset

* The dataset contains SMS messages labeled as:

  * `ham`: Non-spam (legitimate) messages
  * `spam`: Spam messages

The data was loaded and analyzed to explore distribution, length of messages, and word frequency.

---

### 📈 Model Training & Evaluation

* **Preprocessing**: Includes lowercase conversion, removing special characters, stopword removal, and stemming.
* **Vectorization**: Used `CountVectorizer` to convert text to a matrix of token counts.
* **Model**: Multinomial Naive Bayes (ideal for text classification problems).
* **Evaluation Metrics**:

  * Accuracy
  * Precision
  * Confusion Matrix

---

---

### 📂 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/spam_sms_detection.git
   cd spam_sms_detection
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:

   * Use Jupyter Notebook or VSCode to open `spam_sms_detection.ipynb`.

---

