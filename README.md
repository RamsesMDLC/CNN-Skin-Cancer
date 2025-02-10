# CNN-Skin-Cancer

## Brief Description
Incorporate robustness into a vanilla convolutional neural network for skin cancer lesion classification

## Dataset
* Source: https://www.kaggle.com/datasets/bhaveshmittal/melanoma-cancer-dataset
  * License: CC0 - Public Domain
* General  information  (before  data  preparation  and/or preprocessing): 
  *  Images: photos of skin cancer lesions categorized as benign or  malignant, set in  their respectives  files of training  data  (11879 images)  and  test  data  (2000 images). 
  * Resolution: 224x224 pixels.
  * File type: JPG image.
* Specific information (after data preparation and/or preprocessing):
 * Balanced dataset: ratio 1.1 (benign/ malignant images).
 * Noise: there was no noise present in the dataset.
 * Data normalization: it was not applied in this project.
 * Data distribution used in this project (see Table I) and some data instances without augmentation (see Figure 1)

![image](https://github.com/user-attachments/assets/42fc19d7-e71b-450c-8fc4-62a15f95cb9f)

![image](https://github.com/user-attachments/assets/42826b70-9353-41ed-a7b2-e4a19e01ff5a)


### Data Dictionary
| Column     | Description                          |
|------------|--------------------------------------|
| `public_reference`    | reference code of the vehicle                 |
| `mileage`     | mileage of the vehicle         |
| `reg_code` | registration code of the vehicle                 |
| `standard_colour` | color of the vehicle      |
| `standard_make` | manufacturer of a vehicle, e.g. Tesla    |
| `standard_model` | model of vehicle, e.g. Corolla     |
| `vehicle_condition` | new or used     |
| `year_of_registration` | date the vehicle was registered    |
| `body_type` | body type of the vehicle e.g. SUV     |
| `crossover_car_and_van` | true or false    |
| `fuel_type` | The vehicle fuel type e.g. Diesel     |
| `price` | target variable (in £)     | 

![image](https://github.com/user-attachments/assets/4d215b52-2a80-4d5f-b267-bee5b9d6df8d)


