# Fake News Detection

The project aims to develop a machine-learning model capable of identifying and classifying any news article as fake or not. The distribution of fake news can potentially have highly adverse effects on people and culture. This project involves building and training a model to classify news as fake news or not using a diverse dataset of news articles. We have used four techniques to determine the results of the model.

1. **Logistic Regression**
2. **Decision Tree Classifier**
3.  **Random Forest Classifier**

## Project Overview

Fake news has become a significant issue in today's digital age, where information spreads rapidly through various online platforms. This project leverages machine learning algorithms to automatically determine the authenticity of news articles, providing a valuable tool to combat misinformation.

## Dataset

We have used a labelled dataset containing news articles along with their corresponding labels (true or false). The dataset is divided into two classes:
- True: Genuine news articles
- False: Fake or fabricated news articles

## System Requirements 

Hardware :
1. 4GB RAM
2. i3 Processor
3. 500MB free space

Software :
1. Anaconda
2. Python

## Dependencies

Before running the code, make sure you have the following libraries and packages installed:

- Python 3
- Scikit-learn
- Pandas
- Numpy
- Seaborn
- Matplotlib
- Regular Expression



## Installation

To set up the Fake News Detector project on your local machine, follow these steps:

### 1. Clone the Repository

Begin by cloning the repository from GitHub. This will download all necessary files, including datasets, scripts, and configuration files, to a local folder named `Fake-News-Detection`:

```bash
git clone https://github.com/De-bya/Fake-News-Detection.git
cd Fake-News-Detection
```
### 2. Create a Virtual Environment (Optional)

It's recommended to create a virtual environment to isolate the project dependencies and avoid conflicts with other Python packages installed on your system.

```bash
python -m venv venv
source venv/bin/activate     # On Linux or macOS
venv\Scripts\activate        # On Windows
```

### 3. Install Required Packages

The project dependencies are listed in requirements.txt. Use the following command to install them:

```bash
pip install -r requirements.txt
```


