# Assignment 4 — BERT Fine-tuning for Commonsense Validation
**Course: Applied Natural Language Processing | University of Arizona**

## 📌 Task Overview
Commonsense statement validation on the **SemEval-2020 ComVE** shared task — 
classifying which of two statements is less likely to be true based on 
commonsense reasoning.

## 🧠 Approach
Fine-tuned a pre-trained **BERT** transformer model using the HuggingFace 
Transformers library:
- `AutoTokenizer` for text tokenization
- `AutoModelForSequenceClassification` for binary classification
- HuggingFace `Trainer` API for training pipeline
- Reproducibility controls via seed initialization
- Evaluated using accuracy and F1-score metrics

## 🛠️ Tools & Technologies
`Python` `HuggingFace Transformers` `BERT` `PyTorch` `Scikit-learn`
`Pandas` `NumPy` `Jupyter Notebook` `Google Colab`

## 📁 Files
| File | Description |
|---|---|
| `Pretrained_LM_Subtask_A.ipynb` | BERT fine-tuning — binary classification (true/false statement) |
| `Pretrained_LM_Subtask_B.ipynb` | BERT fine-tuning — identifying the wrong concept |
| `Pretrained_LM_Subtask_C.ipynb` | BERT fine-tuning — generating a reason for incorrectness |

## 🔑 Key Concepts Demonstrated
- Transformer fine-tuning with HuggingFace
- Transfer learning for NLP classification tasks
- Multi-subtask NLP pipeline
- Modern LLM workflow implementation
