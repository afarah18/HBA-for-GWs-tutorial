# Hierarchical Bayesian Analysis for CBC populations: a tutorial
A brief tutorial on hierarchical Bayesian analysis of gravitational wave source populations, made for the ICERM workshop "Scientific Machine Learning for Gravitational Wave Astronomy."
The tutorial is contained within this notebook: [intro_HBA_tutorial.ipynb](intro_HBA_tutorial.ipynb), and all the data you need is in [`inputs/`](inputs).

## setup
### local
To run this tutorial on your local machine, clone this repository and set up the conda environment with
```
git clone https://github.com/afarah18/HBA-for-GWs-tutorial.git
cd HBA-for-GWs-tutorial
conda env create -f environment.yml
```
Then, open the notebook and select the `icerm_population_tutorial` conda environenment as your kernel.

**Note:** you have everything in [`requirements.txt`][requirements.txt`] installed in a different environment, you can skip the conda environment creation and just use your own environment.

### Google colab
Alternatively, you can run on google colab and potentially make use of GPU or TPU speedups. Open the notebook in google colab here: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/afarah18/HBA-for-GWs-tutorial/blob/main/intro_HBA_tutorial.ipynb)

Then, connect to a runtime (try to get a GPU or TPU!) and uncomment the lines in the first cell.
