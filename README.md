
## Overview
This repository presents a Hate Speech Detection Model for the Amharic language, fine-tuned from the multilingual BERT (mBERT) model. Leveraging the HuggingFace Trainer API, this model is specifically designed to detect hate speech in Amharic with high accuracy and precision.

### Key Features
- Fine-tuned mBERT Model: Built on Davlan's bert-base-multilingual-cased-finetuned-amharic from Hugging Face.
- HuggingFace Trainer API: Streamlined training and evaluation process.
- High Performance: Achieved impressive metrics on a comprehensive dataset.

---

## Model Details
### Model Architecture
- Base Model: Davlan's bert-base-multilingual-cased-finetuned-amharic (pretrained multilingual BERT).
- Fine-tuned Task: Sequence classification for Amharic hate speech detection.

### Training Parameters
- Epochs: 15
- Learning Rate: 5e-5

### Performance Metrics
- F1-Score: 0.9172
- Accuracy: 91.59%

---

## Dataset
The model was fine-tuned using a dataset sourced from Mendeley Data. The dataset consists of 30,000 labeled instances, making it one of the most comprehensive datasets for Amharic hate speech detection.

### Dataset Overview
- Total Samples: 30,000
- Source: Mendeley Data Repository
- Language: Amharic

---

## Installation

### Prerequisites
Ensure you have the following installed on your machine:
- Python 3.8+
- Jupyter Notebook

### Steps
1. Clone the repository:
      git clone https://github.com/Esubalew-kunta/amharic-hate-speech-detection.git
   
2. Navigate to the project directory:
      cd amharic-hate-speech-detection-using-ML
   
3. Launch Jupyter Notebook:
      jupyter notebook
   
4. Open and run the notebook file:
   
   Hate_speech_detection_using_amharic_language.ipynb
   

---

## Model Usage
To use this model for Amharic hate speech detection, you can follow the steps in the Google Colab notebook to load and test the model on new data. The notebook includes all necessary instructions for:

- Loading the fine-tuned mBERT model.
- Preprocessing Amharic text data.
- Making predictions on new instances.


---

## Contributing
Contributions are welcome! If you have suggestions or want to improve the model, feel free to fork the repository and submit a pull request.

---

## Acknowledgments
- Dataset Contributors: Special thanks to the contributors who provided labeled Amharic text datasets.
---
##### The model can make mistake. Check for critical information.

#### Copyright &copy; 2023. Done by  Esubalew Kunta.
