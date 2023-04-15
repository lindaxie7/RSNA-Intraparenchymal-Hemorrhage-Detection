# RSNA-Intraparenchymal-Hemorrhage-Detection

[Data Preprocessing Code](https://github.com/lindaxie7/NYC-CitiBike-Analysis/blob/main/NYC_CitiBike_Challenge_starter_code.ipynb)

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



- Image Preprocessing:  .dcm -> 3 window -> combined 3 channel .png




### Auto ML performance





### Technologies 


