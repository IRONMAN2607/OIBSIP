# OIBSIP_DataScience_task2 - Unemployment Analysis with Python

This repository contains Oasis Infobyte Data Science Task 2.

## Objective
Analyze unemployment trends in India and study the impact around the COVID-19 period.

## Steps Performed
1. Loaded the unemployment dataset.
2. Cleaned date and column formats.
3. Analyzed region-wise unemployment rates.
4. Visualized monthly trends and pre/post-COVID differences.

## Tools Used
- Python 3.11+
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn

## Outcome
A concise exploratory analysis showing unemployment patterns across regions and time periods.

## Project Structure
```text
OIBSIP_DataScience_task2/
├── README.md
├── requirements.txt
├── data/
│   └── Unemployment_Rate_upto_11_2020.csv
├── notebook/
│   └── task_2_unemployment_analysis.ipynb
├── outputs/
│   └── task_2_executed.ipynb
└── docs/
    └── report.md
```

## How to Run
Clone this task repository and move into it:

```bash
git clone <your-task-2-repository-url>
cd OIBSIP_DataScience_task2
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

Open `notebook/task_2_unemployment_analysis.ipynb` and run all cells in order. The notebook reads the dataset from this repository's local `data/` folder.

## Demo Video
https://www.linkedin.com/posts/angad-mistry-b9a9812b5_datascience-python-jupyter-ugcPost-7493306016126795778-3tNH/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEvI0WYBUxBQqoR_4tnaCXym9uvXolHJ45w
