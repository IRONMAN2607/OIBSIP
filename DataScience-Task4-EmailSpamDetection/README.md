# OIBSIP_DataScience_task4 - Email Spam Detection

This repository contains Oasis Infobyte Data Science Task 4.

## Objective
Classify SMS/email messages as spam or ham using text processing and machine learning.

## Steps Performed
1. Loaded the spam message dataset.
2. Prepared labels and message text.
3. Converted text into machine-readable features.
4. Trained and evaluated a spam classifier.

## Tools Used
- Python 3.11+
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

## Outcome
A text classification model that detects spam messages from message content.

## Project Structure
```text
OIBSIP_DataScience_task4/
├── README.md
├── requirements.txt
├── data/
│   └── SMSSpamCollection
├── notebook/
│   └── task_4_email_spam_detection.ipynb
├── outputs/
│   └── task_4_executed.ipynb
└── docs/
    └── report.md
```

## How to Run
Clone this task repository and move into it:

```bash
git clone <your-task-4-repository-url>
cd OIBSIP_DataScience_task4
```

Create and activate a virtual environment:

```bash
python -m venv .venv
```

Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

macOS/Linux:

```bash
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Start Jupyter from this repository root:

```bash
jupyter notebook
```

Open `notebook/task_4_email_spam_detection.ipynb` and run all cells in order. The notebook reads the dataset from this repository's local `data/` folder.

## Demo Video
https://www.linkedin.com/posts/angad-mistry-b9a9812b5_datascience-python-jupyter-ugcPost-7493306902978920448-VIE9/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEvI0WYBUxBQqoR_4tnaCXym9uvXolHJ45w