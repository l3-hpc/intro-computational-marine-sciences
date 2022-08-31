Using miniconda, I did, from this gitrepo,
```
conda env create --prefix ~/env_disl -f environment.yml 
conda activate ~/env_disl
```

Need to use the same environment as binder, or else you will get different errors and not be able to troubleshoot.

Then to launch Jupyer notebook, to edit the Notebook, do
```
jupyter notebook Mobile.ipynb
```

That should open Mobile page in a web browser.  I use Chrome.
