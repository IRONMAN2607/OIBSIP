# OIBSIP_DataScience_task5 - Sales Prediction

This repository contains Oasis Infobyte Data Science Task 5.

## Objective
Predict product sales using advertising spend across marketing channels.

## Steps Performed
1. Loaded the advertising dataset.
2. Explored relationships between TV, radio, newspaper, and sales.
3. Trained regression models.
4. Evaluated model performance and interpreted results.

## Tools Used
- Python 3.11+
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

## Outcome
A regression workflow that estimates sales from advertising investment.

## Project Structure
```text
OIBSIP_DataScience_task5/
├── README.md
├── requirements.txt
├── data/
│   └── Advertising.csv
├── notebook/
│   └── task_5_sales_prediction.ipynb
├── outputs/
│   └── task_5_executed.ipynb
└── docs/
    └── report.md
```

## How to Run
Clone this task repository and move into it:

```bash
git clone <your-task-5-repository-url>
cd OIBSIP_DataScience_task5
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

Open `notebook/task_5_sales_prediction.ipynb` and run all cells in order. The notebook reads the dataset from this repository's local `data/` folder.

## Demo Video
https://www.linkedin.com/posts/angad-mistry-b9a9812b5_datascience-python-jupyter-ugcPost-7493307133741031424-FLED/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEvI0WYBUxBQqoR_4tnaCXym9uvXolHJ45w