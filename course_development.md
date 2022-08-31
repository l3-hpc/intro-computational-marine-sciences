Python for Earth Sciences

Instructor: Rebekah Esmaili

Sorry these instructions are just for mac and Linux. If you Windows, I've had success with using/recommending [Git Bash](https://gitforwindows.org).  Then you might do these exactly, but I **did not** test it.  (Volunteers?)


To get the materials for this course:
```
cd ~
git clone https://github.com/l3-hpc/intro-computational-marine-sciences.git
```

Then get the materials from Rebekah's course:
```
cd ~
git clone https://github.com/modern-tools-workshop/AGU-python-workshop-2021.git
cp AGU-python-workshop-2021/01_Basic_Data_Analysis_and_Visualization.ipynb intro-computational-marine-sciences
```

Open in Jupyter Notebook.  Edit with much attribution.

Stuff I changed...

We will make the environment, so they don't need to know Conda and whatnot.  We can move these notes somewhere else.

DATA.  Use hers, but maybe find other ones.  I need to look where to store data, they don't like it in GitHub...
```
cp -r ~/AGU-python-workshop-2021/data ~/intro-computational-marine-sciences
```

I also renamed the Notebook to Lab3_..etc.
