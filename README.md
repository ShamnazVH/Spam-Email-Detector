# Spam-Email-Detector
This Advanced Email Spam Detection System leverages machine learning and natural language processing to accurately classify emails as spam or legitimate (ham). Built with Python and scikit-learn, the project demonstrates a complete ML workflow from data preprocessing to model deployment.

## Key Features
### 🔍 Sophisticated Text Preprocessing 
Advanced regex-based cleaning (URLs, emails, phone numbers removal) NLTK stopword removal and Porter stemming Special character and whitespace normalization

### ⚙️ Intelligent Feature Engineering
TF-IDF vectorization with bigrams (1-2 n-grams) 7 custom features: message length, word count, capital letter ratio, special character count, URL/email/phone presence Sparse matrix optimization for efficient computation

### 🤖 Multi-Model Comparison
Four algorithms evaluated: Naive Bayes, Logistic Regression, SVM, Random Forest 5-fold cross-validation for robust performance metrics Hyperparameter tuning with GridSearchCV Automatic best model selection based on accuracy

### 📊 Comprehensive Evaluation
Detailed classification reports (precision, recall, F1-score) Confusion matrix visualization with seaborn Probability-based confidence scoring Real-world sample email testing

### 💾 Production-Ready Outputs
Serialized model files (pickle format) Reusable vectorizer for inference Model metadata storage Visual performance analytics

### Technical Stack
Language: Python 3.x ML Libraries: scikit-learn, scipy NLP: NLTK (Natural Language Toolkit) Data Processing: pandas, numpy Visualization: matplotlib, seaborn Platform: Google Colab (cloud-based, GPU-enabled)

### Performance Highlights
The system achieves high accuracy through ensemble feature combination, comparing both traditional text features (TF-IDF) and engineered numerical features. Cross-validation ensures the model generalizes well to unseen data.

Use Cases
Email filtering systems SMS spam detection Message classification pipelines Educational ML demonstrations Text classification research
