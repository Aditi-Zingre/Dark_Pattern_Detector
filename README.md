
# Dark_Pattern_Detector

# Overview
This project aims to detect and classify dark patterns in web content using natural language processing (NLP), web scraping and machine learning (ML) techniques. Dark patterns refer to design elements or techniques used to manipulate users into taking actions they may not intend to take. The Confirm Shaming Detection System, one of the dark pattern is a web application built to automatically identify and mitigate instances of confirm shaming in e-commerce websites. This project utilizes Flask, a lightweight web framework for Python, to handle server-side logic and provide a dynamic user experience.

# Installation
To run this project, you need to install the following libraries and dependencies:




## Deployment

To deploy this project run

```bash
!pip install transformers datasets evaluate accelerate optuna optimum
!pip install onnxruntime-gpu
!pip install pydataset
!pip install gtts
!pip install anvil-uplink
!pip install flask_cors

```
# Usage

1. Clone the repository: 
```bash 
git clone https://github.com/your-username/dark-pattern-recognition.git
cd dark-pattern-recognition
```

2. Install dependencies:
```bash 
pip install -r requirements.txt
```

3. Run the main script:
```bash
python main.py
```

# Features

1. Web scraping to extract text from websites.
2. Data preprocessing for model training.
3. Training a sequence classification model using Transformers and ONNX Runtime.
4. Quantizing and optimizing the trained model.
5. Text-to-speech conversion for analysis results.
6. Dark pattern analysis and classification.
7. Webpage analysis for hidden elements and misleading buttons.
8. Model evaluation and visualization (confusion matrix, ROC curve).

# How to Contribute
1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Make your changes and commit them (git commit -am 'Add new feature').
4. Push to the branch (git push origin feature-branch).
5. Create a new Pull Request.

# Acknowledgments
1. Thanks to Hugging Face for their Transformers library.
2. Special thanks to the Flask and Python communities for their support and contributions to open-source software.