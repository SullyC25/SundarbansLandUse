# Sundarbans Land Cover Classification Project

## Introduction
The Sundarbans is one of the world's largest mangrove forests it is located on the border between Bangladesh and India. Covering approximately 10,000 km², this ecologically crucial area acts as a natural barrier against cyclones from the Bay of Bengal. It faces threats from deforestation, climate change, and human encroachment, leading to significant land cover changes(Rahman and Begum, 2011). Innovative solutions like AI tools are essential for environmental monitoring and management in such dynamic and vulnerable landscapes(Rahman et al, 2013)


## Project Overview
This project utilizes AI to classify land cover and land use in the Sundarbans using satellite imagery. Our goal is to differentiate between water bodies, forest regions, and urban areas to aid in monitoring changes and implementing conservation strategies.

## Data Source
We utilize high-resolution optical images from the Sentinel-2 satellite, collected from April 2018. These images are crucial for environmental monitoring and provide the spectral detail required for precise classification tasks.

## Methodology
We apply a supervised learning approach, using the IRIS tool to manually label images and train our model. This method ensures enhanced accuracy by utilizing pre-identified labels to guide the learning algorithm.

![image](https://github.com/SullyC25/SundarbansLandUse/assets/160886905/ce784566-2e39-48f7-a752-c17371c91763)

![image](https://github.com/SullyC25/SundarbansLandUse/assets/160886905/56058047-b8a3-4737-9886-72303b06082b)

## Problem Description
The dynamic nature of land use and land cover in the Sundarbans poses significant challenges. Rapid changes due to natural and anthropogenic factors complicate tracking land usage and its impact on local and global ecosystems. This project leverages AI to provide a clearer picture of the evolving interlinkages among forest, river, and urban areas.

## Results
![image](https://github.com/SullyC25/SundarbansLandUse/assets/160886905/45e1cfac-9367-46f1-8c61-2d85edc6b487)



## Issues and Proposed Improvements
### Challenges:
- **Cloud Cover:** Clouds can obscure important details and introduce data interpretation errors.

![image](https://github.com/SullyC25/SundarbansLandUse/assets/160886905/d02387d3-2307-493f-83bd-9b38b8ef1ec5)

- **Distinguishing Features:** Urban and other land uses often share similar spectral signatures, leading to classification ambiguities.
- **River Classification:** Rivers are generally clear and distinct, presenting fewer classification difficulties.


### Improvements for Model Validation:
- **Comparison with Ground Truth Labels:** Enhancing model accuracy by comparing predictions with actual ground truth labels.
- **Confusion Matrix:** Employing a confusion matrix in testing methodology to visually assess the model’s performance across different classes.

## Conclusion
Despite challenges like cloud cover and distinguishing between land uses, this project highlights AI's potential in enhancing the monitoring and management of the Sundarbans. Through rigorous validation and the use of advanced techniques like confusion matrices, we aim to refine our classification methods, supporting more effective conservation strategies.

## References
- Rahman, M. et al., 2013. "Comparison of Landsat image classification methods for detecting mangrove forests in Sundarbans." *International Journal of Remote Sensing*, 34(4), pp.1041-1056.
- Rahman, M.M. and Begum, S., 2011. "Land cover change analysis around the Sundarbans Mangrove Forest of Bangladesh using remote sensing and GIS application." *Journal of Science Foundation*, 9(1-2), pp.95-107.














