# hackerearth - Identify the dance form

This was a simple solution for the Identify the dance form competition organized by hackerearth.

No External Data, Ensembling or Pseudolabelling techniques was used for this submission.

Link to problem: https://www.hackerearth.com/problem/machine-learning/identify-the-dance-form-deea77f8/description/

Libraries used:
- Pytorch
- Sklearn
- open-cv
- Albumentations
- pytorch-image-models https://github.com/rwightman/pytorch-image-models

Steps to reproduce the solution:
- Download the data files and unzip it into the ./data/ folder
- Change model to ResNet18
- Run the notebook
- It will produce the submission.csv file as output.

The simple solution used above was one of my 3 submissions using the relatively shallow ResNet18 Model
It scored 84.5277 inn CV, 88.06930 in public LB and 85.57376 in private LB

Legal Disclaimer: All Trademarks referred to are the property of their respective owners.
