# Naive Bayes Classifier on Social Network Ads Dataset

This Google Colab notebook demonstrates a implementation of the **Naive Bayes** classification algorithm using the Social Network Ads dataset. The dataset is used to predict whether a user purchases a product based on their age and estimated salary.

## 📊 Dataset Overview

- Dataset: `Social_Network_Ads.csv`
- Features: Age, Estimated Salary
- Target: Purchased (0 or 1)

## 🚀 Getting Started

### 1. Clone the Repository or Upload the Notebook

```bash
git clone https://github.com/MaddyRizvi/social-network-naive-bayes.git
```

Or simply upload the notebook to [Google Colab](https://colab.research.google.com/) and start running the cells.

### 2. Upload the Dataset

Make sure to upload `Social_Network_Ads.csv` to your Colab session by using the file upload tool.

```python
from google.colab import files
uploaded = files.upload()
```

### 3. Run the Notebook

The notebook includes the following steps:

- Data loading and preprocessing
- Train-test split
- Feature scaling using `StandardScaler`
- Training a `GaussianNB` classifier
- Prediction and evaluation
- Visualization of decision boundaries

## 📈 Output

- Predicted output for a sample input: `[30, 87000]`
- Confusion Matrix and Accuracy Score
- Visualizations for both Training and Test sets

## 🧠 Libraries Used

- numpy
- pandas
- matplotlib
- scikit-learn

## 🖼️ Visualizations

The notebook contains plots showing the decision boundary of the Naive Bayes classifier over the training and test data.

## 📂 Folder Structure

```
├── NaiveBayes_SocialNetworkAds.ipynb
├── Social_Network_Ads.csv
├── README.md
└── CONTRIBUTING.md
```

## 🤝 Contributing

Contributions are welcome! Please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
