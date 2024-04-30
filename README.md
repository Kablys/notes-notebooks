# Notebooks for notes

Using Literate programming to learn, experiment and store notes about everyting I can.

## Setting up Jupyter

`pip install jupyterlab` & `jupyter lab`\
or\
`pip install notebook` & `jupyter notebook`

## Setting up languages

- Deno `curl -fsSL https://deno.land/install.sh | sh`. [Other installation](https://docs.deno.com/runtime/manual/getting_started/installation)
  - `deno jupyter --unstable`
  - `deno jupyter --unstable --install`
- DuckDB
  - `pip install duckdb jupysql pandas`
- xeus-sqlite. Requires installing mamba.
  - `curl -L -O "https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-$(uname)-$(uname -m).sh"`
  - `bash Miniforge3-$(uname)-$(uname -m).sh`
  - `mamba create -n xeus-sqlite`
  - `mamba activate xeus-sqlite`
  - `mamba install xeus-sqlite jupyterlab -c conda-forge`
- Bash
  - `pip install bash_kernel`
  - `python -m bash_kernel.install`

## Setting up other

- Visulization
  - __[Mermaid.js](https://mermaid.js.org)__ included in JupyterLab 4.1 and Notebook 7.1
  - graphviz/dot
    - [jupyter-dot-kernel](https://github.com/laixintao/jupyter-dot-kernel). `sudo apt-get install graphviz`, `pip install dot_kernel`
  - PlantUML
    - `pip install iplantuml`
    - `sudo apt install plantuml`

## Alternatives to Jupyter

- Julia - [Pluto.jl](https://plutojl.org/)
- R -  R Notebook https://rmarkdown.rstudio.com/lesson-10.html
- JavaScript - [ObservableHQ](https://observablehq.com)
- Python - [marimo](https://marimo.io/) reactive