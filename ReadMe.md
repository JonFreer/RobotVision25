This repository contains the weekly lab exercises for the Robot Vision Module.

Each week it will be updated with the content for that week. `git clone` for the first week and then `git pull` for the following weeks.

If you are missing dependencies such as skimage in your vLab instance, please make sure you have created the appropriate venv environment.

### Setup virtual environment
Define a new virtual environment and install your required packages. Then create a new kernel within your virtual environment and select this kernel when executing your notebook file.

```
cd /jupyter/work
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install ipykernel [other-packages]
python3 -m ipykernel install --prefix=/jupyter/work --name=venvkernel
```
