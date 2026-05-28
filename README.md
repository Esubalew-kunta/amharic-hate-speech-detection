# Amharic Hate Speech Detection

Hate speech classifier for Amharic text, built by fine-tuning mBERT on 30,000 labeled samples.
Accuracy: 91.59% | F1: 0.9172

---

## Live Demo

Try the model in your browser — no code needed:
https://huggingface.co/spaces/esubalew-kunta/amharic-hate-speech-detector

---

## Overview

Amharic has over 57 million speakers but very few NLP tools. Most hate speech detection models are built for English or other widely spoken languages, which means harmful content in Amharic goes undetected on social media.

I built this classifier to help close that gap. It takes an Amharic sentence as input and returns a label: hate speech or not hate speech.

---

## Model Details

### Architecture

- Base model: Davlan/bert-base-multilingual-cased-finetuned-amharic
- Task: Binary sequence classification

### Training

- Epochs: 15
- Learning rate: 5e-5
- Training framework: HuggingFace Trainer API

### Results

| Metric | Score |
|---|---|
| Accuracy | 91.59% |
| F1 Score | 0.9172 |

---

## Dataset

The model was trained on a dataset from Mendeley Data containing 30,000 labeled Amharic sentences.

| Field | Details |
|---|---|
| Total samples | 30,000 |
| Source | Mendeley Data Repository |
| Language | Amharic |

---

## Installation

**Requirements**

- Python 3.8+
- Jupyter Notebook

**Steps**

1. Clone the repository:

        git clone https://github.com/Esubalew-kunta/amharic-hate-speech-detection.git

2. Go into the project folder:

        cd amharic-hate-speech-detection-using-ML

3. Start Jupyter:

        jupyter notebook

4. Open and run:

        Hate_speech_detection_using_amharic_language.ipynb

---

## Using the model

You can also run this in Google Colab. The notebook walks through loading the model, preparing Amharic text input, and getting predictions. Each step has comments explaining what is happening.

---

## What I plan to add

The current model only does binary classification. I want to extend it to detect the type of hate speech, for example ethnicity-based or religion-based content. I also plan to push the trained model to Hugging Face so other researchers working on Ethiopian languages can load it directly.

---

## Contributing

If you want to test it on a different dataset or improve the training setup, feel free to fork and open a pull request.

---

## Note

The model can make mistakes, especially on sentences that mix Amharic with other languages or use informal slang. Do not use it in any real system without additional testing.

---

*Esubalew Kunta, 2025*
