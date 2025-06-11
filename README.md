# KD-Text-Summarization


## 📁 Project Structure

```text
KD-Text-Summarization/
├── distillation/               # Code related to the distillation process
├── distilled-models-saved/     # Stores distilled (student) models after training
├── raw-datasets/               # Original input datasets used for summarization
├── student-models/             # Summarization evaluation results for student models
├── summarized-datasets/        # Summarized versions of the datasets
├── teacher-models/             # Summarization evaluation results for teacher models
├── venv/                       # Python virtual environment (excluded in .gitignore)
├── .gitignore
├── README.md
└── requirements.txt
```


## Execution Order


## ✅ Requirements
Install the necessary dependencies using:

pip install -r requirements.txt


Please run the files in the following order:


#### Teacher Models

cd teacher-models

python KDTS_llama3.1_70b_V1_270525.py

1 - `KDTS_llama3.1_70b_V1_270525.py`
2 - `KDTS_gemma2_27b_V1_270525.py`
3 - `KDTS_qwen2.5_72b_V1_270525.py`
4 - `KDTS_falcon_40b_V1_270525.py`





Student Models

1 - `KDTS_llama3.1_8b_V1_270525.py`
2 - `KDTS_gemma2_2b_V1_270525.py`
3 - `KDTS_qwen2.5_7b_V1_270525.py`
4 - `KDTS_falcon_7b_V1_270525py`






