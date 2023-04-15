# RSNA-Intraparenchymal-Hemorrhage-Detection

## Overview of Project
Create a rapid, cloud-based, deployable ML method to detect ICH potentially across the hospital enterprise to help patients and clinical teams.


### The data we are working with:
https://www.kaggle.com/c/rsna-intracranial-hemorrhage-detection



### Data Preprocessing
- Originally dataset was downloaded from Kaggle; it has intraparenchymal, subarachnoid, subdural, intraventricular, epidural, any, 6 types of hemorrhage, number of labeled images for each type is 752,807.   The number of labels exceeds the actual number of images, because one patient being labeled in one group, may also have been applied in another group.

- Processed 1000 Intraparenchymal  positive images and 1000 negative images for Auto-ML with explainability

Also processed 3000 Intraparenchymal  positive images  and 3000 negative images, 6000 in total and run autoML without explainability

-  Originally dicom file contain metadata and image pixel array; the goal is to extra the metadata and save them into a CSV file, and convert the dicom files into png files; 

- Save metadata into a CSV file
<img width="503" alt="Capture" src="https://user-images.githubusercontent.com/38533045/232234567-b4b65e6c-9a77-43b6-8199-59edb3567928.PNG">


- Image Preprocessing:  .dcm -> 3 window -> combined 3 channel .png
<img width="457" alt="Capture2" src="https://user-images.githubusercontent.com/38533045/232234569-090bd440-fe0f-4ae2-9a7b-7b13ec6a3b9d.PNG">


- 3 channel image ready for autoML

<img width="454" alt="Capture9" src="https://user-images.githubusercontent.com/38533045/232235482-590443d2-7a2f-447f-87d3-7861652b2efc.PNG">


### Auto ML performance

<img width="707" alt="Capture10" src="https://user-images.githubusercontent.com/38533045/232235408-e3bccf62-f366-4af8-aed0-63f2c7c20622.PNG">




### Packages/Technologies 
Google cloud storage fuse

numpy

pandas

listdir

openCV

matplotlib

pydicom

Google Cloud Auto ML





