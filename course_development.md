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

Students can save work as html (which works really well), File:Save and Export Notebook As...:HTML.  That saves a single html file to the users' computer.

Save/Export to pdf or webpdf doesn't work, but you can use File:Print:Save as PDF

Overview of Notebook in Binder, can click the folder icon and see which files are there.  You can actually save files during the sessions, then right click and download to the local computer.

Binder Limitations:

Memory, 8GB


Can have session in the console, click Tabs:Console1.  Not what I thought, kinda stupid.  Or else I need to learn more.


They can send you address for their binder, wonder how long it 'hangs around'
https://mybinder.org/v2/gh/l3-hpc/intro-computational-marine-sciences/1c74411c79321a5a86da36b67b91f1812efc55f9?urlpath=lab%2Ftree%2FMobile.ipynb
