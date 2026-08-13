# OIBSIP - Data Science Task Repository Workspace

This workspace contains five separate Oasis Infobyte Data Science task folders. Each folder is prepared to be uploaded as its own public GitHub repository, and each repository should use the folder name as the GitHub repository name.

## Separate Repositories to Create

| Task | GitHub repository name | Title |
| --- | --- | --- |
| 1 | `OIBSIP_DataScience_task1` | Iris Flower Classification |
| 2 | `OIBSIP_DataScience_task2` | Unemployment Analysis with Python |
| 3 | `OIBSIP_DataScience_task3` | Car Price Prediction |
| 4 | `OIBSIP_DataScience_task4` | Email Spam Detection |
| 5 | `OIBSIP_DataScience_task5` | Sales Prediction |

## How to Publish

For each task, create a separate GitHub repository with the exact matching name above. Then upload only that task folder's contents to the matching repository.

Example for Task 1:

```bash
cd OIBSIP_DataScience_task1
git init
git add README.md requirements.txt .gitignore notebook outputs docs
git commit -m "Add OIBSIP Data Science task 1"
git branch -M main
git remote add origin <your-task-1-repository-url>
git push -u origin main
```

Repeat the same process for each task folder with its own repository URL.

## Folder Contents

Each standalone task folder includes:

- `README.md` - objective, steps performed, tools used, outcome, and run instructions.
- `requirements.txt` - dependencies for that task repository.
- `.gitignore` - common Python/Jupyter ignored files.
- `notebook/` - source notebook.
- `outputs/` - executed notebook with results.
- `data/` - dataset where needed.
- `docs/report.md` - brief report template.

## Running a Task Repository

Inside any task folder:

```bash
python -m venv .venv
pip install -r requirements.txt
jupyter notebook
```

Open the notebook inside `notebook/` and run all cells in order.

## Submission Checklist

For the final submission form, provide:

- Name
- Email
- Domain: Data Science
- Task title
- GitHub repository link for the specific task
- Demo video link, if applicable
- LinkedIn post link

Make sure all links are public and accessible before submitting.
