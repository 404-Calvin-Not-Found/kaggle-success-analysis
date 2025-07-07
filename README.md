# Meta Kaggle Hackathon 2025 – Project XPANSE

A deep dive into Kaggle's competitive landscape — this project analyzes medal distributions, user behavior, successful kernel patterns, and participation trends using the Meta Kaggle dataset.


---

## Required Datasets

This project uses **Meta Kaggle**, the official dataset provided by Kaggle itself.

Download instructions:

1. Go to the [Meta Kaggle Dataset](https://www.kaggle.com/datasets/kaggle/meta-kaggle)
2. Download the following CSVs:
   - `Users.csv`
   - `Kernels.csv`
   - `KernelVersions.csv`
   - `ForumMessages.csv`
   - `Datasets.csv`
   - `Submissions.csv`

Once downloaded, place them in a folder named `data` at the root level:

```

meta-kaggle-hackathon/
└── data/
    ├── Users.csv
    ├── Kernels.csv
    ├── KernelVersions.csv
    ├── ForumMessages.csv
    ├── Datasets.csv
    └── Submissions.csv

````

---

## How to Run

1. Clone this repo:

```bash
git clone https://github.com/<your-username>/meta-kaggle-hackathon.git
cd meta-kaggle-hackathon
````

2. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Run each notebook inside the `notebooks/` folder sequentially.

---

## Notebooks Overview

| Notebook                              | Description                              |
| ------------------------------------- | ---------------------------------------- |
| `01_medal_analysis_start.ipynb`       | Medal distributions and tier breakdown   |
| `02_kernel_success_patterns.ipynb`    | Patterns in successful kernel creation   |
| `03_user_participation_trends.ipynb`  | Yearly activity trends                   |
| `04_medalist_evolution.ipynb`         | Growth journeys of medalists             |
| `05_kernel_structure_analysis.ipynb`  | Source code metrics vs medal outcome     |
| `06_final_summary_and_insights.ipynb` | Summary, visual wrap-up, and conclusions |

---

## Outputs

All generated plots will be saved in the `outputs/` folder and include visualizations like:

* Medal distribution by tier and year
* Votes vs. medals
* Markdown/code patterns
* Total lines vs. medal
* Medalist growth trajectories

---

## Team

**Team XPANSE**

*(Priyanshu Biswas)*
*(Rajdeep Chatterjee)*
*(Anuvab Das)*



Meta Kaggle Hackathon 2025 Submission

---

## Questions?

Feel free to open an issue or contact us through [Kaggle discussions](https://www.kaggle.com/competitions/meta-kaggle-hackathon/discussion).

---
