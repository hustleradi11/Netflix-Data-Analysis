# Netflix Data Analysis

Netflix movies analysis with Python. This project cleans, analyzes, and visualizes movie data to uncover trends in genres, popularity, votes, and release years.

## Project Files

- `Netflix Analysis.ipynb` - main Jupyter notebook with the analysis workflow
- `mymoviedb.csv` - movie dataset used by the notebook
- `requirements.txt` - Python packages needed to run the notebook

## Setup

Clone the repository:

```bash
git clone https://github.com/hustleradi11/Netflix-Data-Analysis.git
cd Netflix-Data-Analysis
```

Create and activate a virtual environment:

```bash
python -m venv .venv
.venv\Scripts\activate
```

On macOS/Linux, activate it with:

```bash
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Run The Notebook

Start Jupyter Notebook:

```bash
jupyter notebook "Netflix Analysis.ipynb"
```

Or execute the notebook from the command line:

```bash
jupyter nbconvert --to notebook --execute "Netflix Analysis.ipynb" --output executed-notebook.ipynb
```

## Main Libraries

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter

## Notes

The notebook expects `mymoviedb.csv` to be in the same folder as `Netflix Analysis.ipynb`.
