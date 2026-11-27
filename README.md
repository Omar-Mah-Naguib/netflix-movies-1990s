# Netflix movies from the 1990s

This Python notebook explores movie runtimes in a sample of Netflix titles. It plots the runtime distribution for films released from 1990 through 1999 and counts action movies under 90 minutes.

## Results

| Metric | Result |
| --- | ---: |
| Movies from the 1990s in the dataset | 183 |
| Most frequent exact runtime | 94 minutes |
| Action movies under 90 minutes | 7 |

## Run the analysis

The notebook was tested with Python 3.13, pandas 2.3.3, and Matplotlib 3.10.7. From the repository root, run:

```sh
python -m pip install -r requirements.txt
python -m jupyterlab notebook.ipynb
```

In JupyterLab, choose **Run → Run All Cells**. Keep `netflix_data.csv` next to the notebook.

## Data source

`netflix_data.csv` is the 4,812-record dataset supplied with DataCamp's [Investigating Netflix Movies](https://www.datacamp.com/projects/1674) guided project. The source archive did not include a separate dataset license. The results describe the supplied sample.
