
# Open 311 Classifier

The very humble beginnings of a classifier for Bloomington's 311 System.

## What's what:

### Open311 Classifier Logistic Plus.ipynb
This notebook is the 'furthest along'. The others can likely ultimately be removed.

### requirements.txt
The usual, shows which packages we used, set up your Jupyter environment appropriately.

### open311lbfgs.pkl
This is the pickled model, if you want to do that.

### data/ 
Has the data. I (Steve) made some changes after identifying many 'Excessive Growth' reports erroneously labeled as 'Trash'. In general there seems a bit of confusion where things were labeled 'Trash' that were not trash. The fixed one is called 'Open311DataFixed.csv'. The original is also here so you can see what changes were made via 'diff' or the like.

### research/
Some findings and documents about the 311 effort in general, and a couple examples of other cities' data. 
