# OIBSIP_DataScience_task3 - Car Price Prediction

This repository contains Oasis Infobyte Data Science Task 3.

## Objective
Predict used car selling prices based on vehicle attributes.

## Steps Performed
1. Loaded and inspected the car dataset.
2. Prepared categorical and numerical features.
3. Trained regression models.
4. Evaluated prediction quality using regression metrics.

## Tools Used
- Python 3.11+
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

## Outcome
A regression-based prediction workflow for estimating used car prices.

## Project Structure
```text
OIBSIP_DataScience_task3/
├── README.md
├── requirements.txt
├── data/
│   └── car data.csv
├── notebook/
│   └── task_3_car_price_prediction.ipynb
├── outputs/
│   └── task_3_executed.ipynb
└── docs/
    └── report.md
```

## How to Run
Clone this task repository and move into it:

```bash
git clone <your-task-3-repository-url>
cd OIBSIP_DataScience_task3
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

Open `notebook/task_3_car_price_prediction.ipynb` and run all cells in order. The notebook reads the dataset from this repository's local `data/` folder.

## Demo Video
https://www.linkedin.com/posts/angad-mistry-b9a9812b5_datascience-python-jupyter-ugcPost-7493306675584737280-jnLt/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEvI0WYBUxBQqoR_4tnaCXym9uvXolHJ45w
