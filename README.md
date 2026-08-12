# OIBSIP - Data Science Internship Tasks

This repository contains my Oasis Infobyte Data Science internship task submissions. The project is organized in the requested per-task format: `OIBSIP_domain_taskno`.

All notebooks run with standard CPython; Anaconda is not required. They were tested with Python 3.14, and Python 3.11-3.14 is recommended.

## Submission Folders

| Task | Folder | Title |
| --- | --- | --- |
| 1 | `OIBSIP_DataScience_task1` | Iris Flower Classification |
| 2 | `OIBSIP_DataScience_task2` | Unemployment Analysis with Python |
| 3 | `OIBSIP_DataScience_task3` | Car Price Prediction |
| 4 | `OIBSIP_DataScience_task4` | Email Spam Detection |
| 5 | `OIBSIP_DataScience_task5` | Sales Prediction |

Each task folder includes:

- A clear `README.md` with objective, steps performed, tools used, and outcome.
- The source notebook under `notebook/`.
- The executed notebook under `outputs/`.
- The dataset under `data/` where applicable.

## Run the notebooks

Clone the repository and move into it:

```bash
git clone <your-repository-url>
cd OIBSIP
```

Create and activate a virtual environment (recommended).

Windows PowerShell:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

macOS/Linux:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install all dependencies from the repository root:

```bash
pip install -r requirements.txt
```

Start Jupyter from the repository root:

```bash
jupyter notebook
```

Open one of the source notebooks below and run its cells in order:

| Task | Source notebook |
| --- | --- |
| 1 - Iris Flower Classification | `notebooks/task_1_iris_flower_classification.ipynb` |
| 2 - Unemployment Analysis | `notebooks/task_2_unemployment_analysis.ipynb` |
| 3 - Car Price Prediction | `notebooks/task_3_car_price_prediction.ipynb` |
| 4 - Email Spam Detection | `notebooks/task_4_email_spam_detection.ipynb` |
| 5 - Sales Prediction | `notebooks/task_5_sales_prediction.ipynb` |

The required datasets are included in the repository. Make sure Jupyter is launched from the same activated virtual environment where you installed `requirements.txt`.

## Submission Checklist

For the final submission form, provide:

- Name
- Email
- Domain: Data Science
- Task title
- GitHub repository link
- Demo video link, if applicable
- LinkedIn post link

Make sure all GitHub, video, and LinkedIn links are public and accessible before submitting.
