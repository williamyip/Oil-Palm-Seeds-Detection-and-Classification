# Oil Palm Seed Detection and Classification

---

## Introduction
Object detection and classification is a classic problem in computer vision. It has been
widely applied in various fields, e.g., biometrics, surveillance, industry production
control. Object detection usually requires output the bounding box of detected object
and the label of its object type. On the other hand, image classification requires to
produce object type(s) as the output for a given input image. 

## Objectives
In this project, I attempt to apply object detection and image classification
techniques to detect oil palm seeds that are present in an image and classify each of
them into category of good or bad quality.

## Dataset
There are in total 110 images of good quality oil palm seeds and 105 images of bad
quality seeds. Each image contains 10 oil palm seeds of the same category. The
images are stored in two different folders “/GoodSeed” and “/BadSeed” which are
accessible at [here](https://drive.google.com/drive/folders1am1DG21TZJ8fiYNPADPoc04N9JkB8Cy8?usp=sharing).

You should keep a separate testing dataset which must contain 20 images of good
quality seeds and 20 images of bad quality seeds, respectively. The specific image
files that should be included in the testing dataset are specified in “testdata.csv” file
accessible at [here](https://drive.google.com/drive/folders/1UcFoMGnBto_8lj90srdeKiM8PxeNYk8V?usp=sharing).

## Requirements
1. Design a method to locate each oil palm seed present in an image and classify
it into the category of good or bad quality.
2. The method should be able to output a bounding box (rectangular or circle)
for each of the oil palm seed detected.
3. The method should be able to output a label as to whether the oil palm seed
detected is of good quality or bad quality. The label can either be text-based,
or colour based.
4. Evaluate the method both quantitatively and qualitatively for
detection and classification accuracy.
7. Design new method for locating and classifying oil palm
seeds.
8. Only use the training dataset for designing and developing the
method.
9. Use the testing dataset for evaluating the method. The ground
truth of the testing dataset should not be part of the input to the program and
should only be used as part of the evaluation on the results obtained for the
testing dataset.

## Novelty and Results
Please refer to the Report.pdf
