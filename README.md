# Melanoma Detection
> CNN-based model that can accurately detect melanoma.
> Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
> The Purpose is to build a solution that can evaluate images and alert dermatologists about the presence of melanoma and has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?
  - This project deals with building a CNN to detect the presence of melanoma from skin lesion sample images.
- What is the business problem that your project is trying to solve?
  -  Reduce health experts' efforts in detecting skin conditions caused by melanoma.
- What is the dataset that is being used?
  - The dataset being used here is a sample of 2239 images classified among 9 types of skin conditions.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Dropout layer helped in fixing the overfitting in the model
- Augmentor helped in balancing the imbalanced classes in the data, by increasing the samples of each class
- The final model provides an 88% accuracy on the train dataset and 78% on the validation dataset
- This model can provide a good estimate to the health experts when looking for the melanoma skin condition

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- jupyter notebook - version 7.2.2
- pandas - version 2.2.2
- numpy - version 1.23.5
- matplotlib - version 3.9.2
- Augmentor - version 0.2.12
- tensorflow - version 2.12.0
- python - version 3.11.8

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- Upgrad lectures were frequently visited for syntax and understanding to write code in jupyter notebook.


## Contact
Created by [Apoorv Jain (@apoorvjain1)] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
