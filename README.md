# jupyter-earth

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pangeo-data/jupyter-earth/HEAD/?urlpath=lab)
[![NSF-1928406](https://img.shields.io/badge/NSF-1928406-blue)](https://nsf.gov/awardsearch/showAward?AWD_ID=1928406)
[![NSF-1928374](https://img.shields.io/badge/NSF-1928374-blue)](https://nsf.gov/awardsearch/showAward?AWD_ID=1928374)

Source repository for the Jupyter meets the Earth project website: https://pangeo-data.github.io/jupyter-earth/

## Build the documentation

The documentation for this repository is built using the beta version of
[Jupyter Book](https://beta.jupyterbook.org). It will be automatically updated
any time changes are made to the `docs/` folder and pushed to master.

To build the documentation locally, run these steps:

* **Install the Jupyter Book 2.0 CLI** using `conda`:

  ```
  conda env create -f environment.yml
  conda activate jupyter-earth
  ```
* **Build the `docs/` folder**:

  ```
  jupyter-book build docs/
  ```

This will create a folder in `docs/_build/html` where you can preview your
site. For example, with `chrome docs/_build/html/index.html`.
