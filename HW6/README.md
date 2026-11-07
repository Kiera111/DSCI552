# DSCI 552 Homework 6

## Structure

- `notebook/Zuo_Xiyi_HW6.ipynb`: completed, executed homework notebook
- `data/aps_failure_training_set.csv`: APS Failure training set
- `data/aps_failure_test_set.csv`: APS Failure test set
- `requirements.txt`: Python dependencies

## Run

```bash
python -m pip install -r requirements.txt
cd notebook
jupyter notebook Zuo_Xiyi_HW6.ipynb
```

The notebook reads the data with the relative paths `../data/aps_failure_training_set.csv` and `../data/aps_failure_test_set.csv`. Run it from the `notebook` directory. The first 20 lines of each CSV are the data-file preamble, and the column names begin on the next line.
