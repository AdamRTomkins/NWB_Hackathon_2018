# Neurodata Without Borders Tutorials


## Intallation

This tutorial relies on some basic assumptions as to what is installed. Primarily, the tutorials are all written using [Jupyter Lab](https://github.com/jupyterlab/jupyterlab). We will also be using the following packages

1. h5py
2. matplotlib
3. neo
4. numpy
5. elephant
6. quantities
7. seaborn
8. pynwb

```
pip install jupyterlab
pip install elephant
pip install h5py
pip install seaborn
pip install -U pynwb --find-links https://github.com/NeurodataWithoutBorders/pynwb/releases/tag/latest  --no-index
``` 

for the depreciated files
```
pip install nwb
```