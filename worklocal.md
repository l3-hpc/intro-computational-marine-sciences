# How to do this stuff on a local machine, or outside of Binder

## macOS

Using miniconda, I did, from **this** gitrepo,
```
conda env create --prefix ~/env_disl -f environment.yml 
conda activate ~/env_disl
```

You need to use the same environment as binder, or else you will get different errors than students and will not be able to troubleshoot.

Then to launch Jupyter notebook, to edit the Notebook, do
```
jupyter notebook Mobile.ipynb
```

That should open Mobile page in a web browser.  I use Chrome on a mac studio. (It shouldn't matter.)

## Google Colab

This was annoying and I might recommend not using it.  I will try again later.
