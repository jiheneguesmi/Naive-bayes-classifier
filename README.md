# Naive-bayes-classifier
# Naïve Bayes Classifier for URL Detection  

- This project implements a **Naïve Bayes classification model** to detect **malicious URLs**, particularly those used in **phishing attacks**.  
- The goal is to classify URLs as **legitimate** or **malicious** based on extracted features such as **URL length, presence of special characters, number of subdomains, and HTTPS usage**.  
- The dataset consists of **651,191 URLs**, categorized into four classes: **benign, phishing, malware, and defacement**.  
- The model achieves an **accuracy of 89.5%**, performing well in detecting legitimate URLs but with a **false negative rate of 27%** for phishing cases.  

## 📌 Technologies Used  
- **Python**  
- **scikit-learn**  
- **pandas**  
- **NumPy**  
- **Matplotlib & Seaborn** (for data visualization)  

## 📌 Implementation Details  
- The dataset undergoes **preprocessing and feature extraction** to enhance classification accuracy.  
- The model chosen is **Gaussian Naïve Bayes**, known for its efficiency in probabilistic classification.  
- Feature extraction includes analyzing **URL structure, domain properties, and presence of suspicious patterns**.  


