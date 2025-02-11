# CNN-Skin-Cancer

## Brief Description
Incorporate robustness into a vanilla convolutional neural network for skin cancer lesion classification

## Dataset
* Source: https://www.kaggle.com/datasets/bhaveshmittal/melanoma-cancer-dataset
  * License: CC0 - Public Domain
    
* General  information  (before  data  preparation  and/or preprocessing): 
  * Images: photos of skin cancer lesions categorized as benign or  malignant, set in  their respectives  files of training  data  (11879 images)  and  test  data  (2000 images). 
  * Resolution: 224x224 pixels.
  * File type: JPG image.
    
* Specific information (after data preparation and/or preprocessing):
  * Balanced dataset: ratio 1.1 (benign/ malignant images).
  * Noise: there was no noise present in the dataset.
  * Data normalization: it was not applied in this project.

* Some data instances without augmentation (see Figure 1)
   
![image](https://github.com/user-attachments/assets/42826b70-9353-41ed-a7b2-e4a19e01ff5a)

## Description
* The aim is to develop better and deeper insights into the construction process of robust convolutional neural networks  that  can generalize without compromising the respective performance.
  * The ever-changing environmental conditions that surround the medical  field  studying  skin  cancer,  such  as  the  skewed distributions of data due to a predominant set of images of certain skin colours, the lack of instances with or without hair and  tattoos,  and  the  noise  and/or  high  discrepancies  in  the quality of the images caused by variations in resolution, focus, contrast, and brightness specific to each capturing equipment motivate this project. 
* A regularized vanilla convolutional neural network was developed ande applied, using the dropout technique, to predict or classify if the skin cancer lesion present in the image is considered benign or malignant.

  ![image](https://github.com/user-attachments/assets/58497849-01aa-4331-8349-aaa139d0aabc)

## Key Insights
* After conducting several experiments, the hypothesis test statistically concludes that the various values and combinations of the regularization technique applied (i.e., dropout rates) in the Fully Connected Layers of a vanilla convolutional neural network were not sufficient on their own to achieve the goal of increasing the robustness and  generalization  abilities  of  the  model,  and  also  reducing  its susceptibility to overfitting when classifying the skin cancer lesion images as benign or malignant. 

