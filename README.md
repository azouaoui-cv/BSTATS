# BSTATS
MVA Biostatistics class project on Learning Representations for Counterfactual Inference (https://arxiv.org/abs/1605.03661)

## Requirements

The [CFR repository](https://github.com/clinicalml/cfrnet) is developed in Python 2.7 and uses ``tensorflow==0.12.0-rc1`` and ``numpy==1.11.3``. 

The dependencies can easily be reproduced using [(Mini)conda](https://conda.io/miniconda.html) as follow.

To instanciate the conda environment, run ``conda create --file conda-env.txt --name bstats``.

Then use pip to install the required Python packages: ``pip -r requirements.txt``.

To use the virtual environment: ``source activate bstats``

To install a custom kernel in jupyter lab/notebook: ``ipython kernel install --user --name=bstats`` (see additional information [here](https://anbasile.github.io/programming/2017/06/25/jupyter-venv/))
