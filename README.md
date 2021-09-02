# MLOPS Pipeline: Detail explanation of end to end Model deployment.

## 0. Prerequisites:

- install Conda (Anaconda/[Miniconda](https://docs.conda.io/en/latest/miniconda.html))
- create a virtual environment: `env_mlops`:
  `conda create --name env_mlops python=3.9`
- activate the virtual environment:
  `conda activate env_mlops`

[Conda cheat sheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)

**Note:** Everything will be installed and run in this virtual environment.

## 1. Data versioning with DVC

**Objectives:**

- how to version a dataset 
- how to use a specific version of a data in your code
- Understand the interoperability between Git and DVC 

## 2. Experiment versioning (tracking)

How to track the model based on the v2 notebook.
Track by saving metrics to txt. => But this only tracks model performance. 
When we have many versions -> readability. What about env?

**Objectives:**
 
- How experiment tracking helps with linking the code, the results and the environment details. 
- Pay attention about how this increases the reproducibility.

## 3. Testing

After we know how to version the data, the models, the environment and how link it to the source code. But we don't know it the data is what we expect and if the code behaves as it should. Let's write some tests!

**Objectives:**

- How to define a test function and how to write an assertion.
- How to the approach to data testing.
- How to the approach to feature engineering testing.

## 4. Automation 

**Objectives:** 

### 4.1 Automate model testing

- How to automate testing with Git and [CML](https://cml.dev/).
- Understand the processes that run after the Git Action workflow is triggered.

### 4.2 Automate model performance comparison

What if we want to compare the performances of two different models? Is the one that we are developing better than the one on the master branch (current best one)? 

To do it automatically, we can leverage DVC pipelines. If you are interested, read:

- introduction to [DVC pipelines](https://dvc.org/doc/start/data-pipelines)
- video [Machine Learning Pipelines with DVC](https://www.youtube.com/watch?v=71IGzyH95UY)
## 5. Deploy a model

We will follow [this tutorial](https://www.freecodecamp.org/news/end-to-end-machine-learning-project-turorial/).

### 5.1 Prepare and test the app locally

**Objectives:**

- See the steps of a model deployment.

### 5.2 Deploy to Heroku
