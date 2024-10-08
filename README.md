# pathbio3

To run locally, first clone the repository using (in a terminal/command line window)
```
git clone https://github.com/rmcolq/pabi3.git
```

This may take up to 5 minutes because the subsampled read files are still quite large.

You will need conda or mamba to install dependancies in a containerized environment. If you do not have either, conda can be installed from [here](https://docs.anaconda.com/miniconda/miniconda-install/) or mamba from [here](https://mamba.readthedocs.io/en/latest/installation/mamba-installation.html). Mamba is a little faster for installation.
```
cd pabi3
mamba env create -f environment.yml # replace with `conda env create -f environment.yml` if using conda
conda activate pabi3
```

Finally open up the notebooks in your browser with jupyter using 
```
jupyter lab
```
