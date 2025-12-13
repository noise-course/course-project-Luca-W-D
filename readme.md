## Prepare Environment
There are a few options for preparing your environment.

1. **If you don't want to risk break an existing environment**, run these commands to create a new conda environment with our (tested) library versions
```
conda create --name ex_jupyter_env python==3.12
conda activate ex_jupyter_env
pip install -r requirements.txt
```

2. **If you want to just add a handful of packages,** go ahead and pip install
 * seaborn
 * plotly
 * ipywidgets
 * ipython

## Getting Started
To launch the notebook from the root of the repo, run

```
cd final
jupyter lab .
```