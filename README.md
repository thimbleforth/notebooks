# notebooks

A small collection of runnable notebooks and helper shell cells used for local tooling and experiments.

I've decided I'll put one of these together every now and then, after going through one of my late night experiments.

## Notebooks

- **openssl-local-ca.ipynb**: Local PKI with OpenSSL — a step-by-step, runnable guide to create a root CA and issue per-service TLS certificates. See [openssl-local-ca.ipynb](openssl-local-ca.ipynb).

### openssl-local-ca Quick Start

**Requirements:**

- `VSCode` with the `Jupyter Notebooks` extension set
- or `Jupyter Notebooks` app itself or through Anaconda
- `openssl` (either native on Linux or inside your WSL2 or MSYS instance on Windows)
- a local Python kernel (I tested on Python 3.12; any recent version should work fine)

**Run interactively**: open [openssl-local-ca.ipynb](openssl-local-ca.ipynb) in VSCode/JupyterLab/Notebook and execute cells sequentially.
