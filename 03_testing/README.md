## 3. Testing

Now we know how to version the data, the models, the environment and how link it to the source code. But we don't know it the data is what we expect and if the code behaves as it should. Let's write some tests!

**Objectives:**

- Learn how to define a test function and how to write an assertion.
- Learn the approach to data testing.
- Learn the approach to feature engineering testing.

**Dependencies:**

- notebooks:
  - exercises (start with this one): `testing_initial.ipynb`
  - solutions (check out if you're stuck): `testing_final.ipynb`
- dataset: `wine_synthetic.csv`
- install: `pip install -U pytest`, `pip install pandas-profiling` (if it doesn't work, try `conda install -c conda-forge pandas-profiling`), `pip install ipywidgets`, `pip install ipytest` (the last one you need only if you want to run pytest in a notebook)

**Instructions:**

Follow the notebook with the following exercises:

1. Pandas profiles: generate the reports about the datasets
2. Testing with `pytest`:
  - Test the functions
  - Test the datasets
  - Test engineered features
