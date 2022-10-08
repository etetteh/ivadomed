`ivadomed` is an integrated framework for medical image analysis with deep learning.

The technical documentation is available [here](https://ivadomed.org).  The more detailed installation instruction is available [there](https://ivadomed.org/installation.html)

## Installation

``ivadomed`` requires Python >= 3.7 and < 3.10 as well as PyTorch == 1.8. We recommend working under a virtual environment, which could be set as follows:

```bash
python -m venv ivadomed_env
source ivadomed_env/bin/activate
```

### Install from release (recommended)

Install ``ivadomed`` and its requirements from `Pypi <https://pypi.org/project/ivadomed/>`__:

```bash
pip install --upgrade pip
pip install ivadomed
```

### Install from source

Bleeding-edge developments builds are available on the project's master branch on Github. Installation procedure is the following:

```bash
git clone https://github.com/neuropoly/ivadomed.git
cd ivadomed
pip install -e .
```


