# Instructions for running the Jupyter notebooks

In order to run the notebooks provided for the lectures and the tutorials (PC), two options are available:

## Using your own environment

For this option, simply download the Jupyter notebooks from this site and run them on your own machine. To install the software environment required to run the course notebooks, follow the procedure below.

```{admonition} Procedure to install Jupyter Notebook from the command line

- Install the latest version of `miniforge` available on [GitHub](https://github.com/conda-forge/miniforge).


- Create a new environment for the course:

`mamba create -n apm41012 python=3.12`


- Activate the apm41012 environment:

`mamba activate apm41012`


- Install the Python packages required for the course:

`mamba install jupyterlab mpmath numpy scipy matplotlib plotly sympy`


- Start the Jupyter server:

`jupyter lab` or `jupyter notebook`
```

## Using the School's JupyterHub

For this option, simply download the Jupyter notebooks from this site and copy them to the School's `JupyterHub` server (see the procedure below).

```{admonition} Using the School's JupyterHub

- In a browser, go to https://jupytercloud.idcs.polytechnique.fr/ and click the `jupyter` link, then the `Sign in with CNRS/INSMI/Mathrice OpenID-Connect Provider` button


- Select the institution Ecole Polytechnique Palaiseau, then use your Polytechnique credentials to log in to the platform


- On the `Server Options` page, click the MAP412 box, which launches a `JupyterLab` with all the modules required for the course


- Click the `Upload files` icon in the left sidebar menu to upload a notebook from your machine to the `JupyterLab`, then run it


- Retrieve a notebook from the platform to your machine by right-clicking the notebook name in the left sidebar and choosing `download`


- Note: move your notebooks to the `persistent` directory so that they are kept for a future session
```
