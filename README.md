 Phishing_email_detector

Introduction:
Phishing emails deceive users to compromise sensitive information. 
This project employs machine learning techniques to classify emails accurately as Safe or Phishing.

Objectives:
1. Build a robust phishing email detection model.
2. Compare performance of multiple machine learning methods.
3. Apply hyper-parameter tuning to optimize results.
4. Handle class imbalance with advanced techniques.

Use-Case
Phishing detection helps organizations:
Prevent financial fraud and data theft.
Safeguard sensitive user information.
Improve email security for better user trust.

Overview:
- 18,000+ emails labeled as Safe or Phishing.
- Features: Email Text preprocessed into TF-IDF vectors.
- Class imbalance: 8,000 Safe vs. 10,000 Phishing emails.
Balancing was done using SMOTE (Synthetic Minority Oversampling Technique).

Models Evaluated/Method Used:
1. Random Forest
2. Support Vector Machines (SVM)
3. Logistic Regression
4. Naive Bayes

Additional Techniques:
- TF-IDF for feature extraction.
- SMOTE for class balancing.

Results Obtained:
SVM:
- Accuracy Improved to 96.5%
Random Forest:
-- Accuracy Improved to 94.2%
Logistic Regression
--Accuracy improve to 89.6%
Naïve Bayes
--Accuracy improved to 88.2%


