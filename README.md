# half-marathon-analysis

Km split analysis for half marathons — km splits (compared with topography) and pace deviation. Includes configurable target paces (e.g. 2-hour goal). Bring your own data and swap in the source file.

## Setup

```bash
pip install -r requirements.txt
```

Open `main_analysis.ipynb` in VS Code or any notebook environment.

## Source file

Place your data file in the `data/` folder, named `half_marathon_YYYYMMDD.ods` (or `.xlsx`), and update `EXCEL_FILE` in the notebook to match. You can also place the topography image in the same folder and name it `topography_YYYYMMDD.ods`.