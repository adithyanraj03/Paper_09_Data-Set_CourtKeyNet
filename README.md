
## Overview
This repository contains image datasets organized in multiple clusters for computer vision research. The data is structured for a specialized detection task that is part of ongoing academic research.

## Repository Structure
```
├── data_raw-cluster00/  # First cluster of dataset files
├── data_raw-cluster01/  # Second cluster of dataset files 
├── data_raw-cluster02/  # Third cluster of dataset files           
```

## Notice to Users
This dataset is part of ongoing research with pending publication. The complete documentation, methodology, and implementation details are intentionally limited at this time.*<br>

Full technical specifications, usage guidelines, and performance metrics will be made available following the publication of associated research.

```
@article{RAJ2026100884,
title = {CourtKeyNet: A novel octave-based architecture for precision badminton court detection with geometric constraints},
journal = {Machine Learning with Applications},
pages = {100884},
year = {2026},
issn = {2666-8270},
doi = {https://doi.org/10.1016/j.mlwa.2026.100884},
url = {https://www.sciencedirect.com/science/article/pii/S2666827026000496},
author = {Adithya N Raj and Prethija G.},
keywords = {Computer vision, Keypoint detection, Badminton court detection, Convolutional neural networks, Geometric constraints, Sports video analysis},
abstract = {Court detection is an important part of sports video analysis, match statistics generation and automated broadcasting systems. Current methodologies often rely on general object detection methods, lacking domain specific knowledge for the correct identification of court borders. In this work, a new deep learning architecture for badminton court detection, CourtKeyNet, was introduced. CourtKeyNet comprises several novel components, including (1) an Octave Feature Extractor for analyzing visual data with various frequency bands, (2) a Polar Transform Attention mechanism to boost the boundary detection capability, (3) a Keypoint Localization module with a hybrid heatmap and regression-based approach to localize precise corners, (4) a Quadrilateral Constraint Module to achieve geometric consistency, (5) a novel Geometric Consistency Loss function. Extensive experiments show that CourtKeyNet has the best results that outperforms the general purpose keypoint detection methods in terms of mean keypoint localization accuracy and court detection Intersection over Union (IoU).}
}
```
*refer for more details :[click here](https://github.com/adithyanraj03/CourtKeyNet)

## Acknowledgements

We extend our sincere gratitude to the following entities whose contributions were invaluable to the creation of this dataset:

- **Roboflow Universe:** For providing a platform and resources that facilitate the sharing and accessibility of datasets within the computer vision community.
This combination dataset was compiled by curating and merging data from two open-source repositories on [Roboflow Universe](https://universe.roboflow.com/), both released under the [CC BY 4.0 license](https://creativecommons.org/licenses/by/4.0/). Special thanks to Roboflow Universe for providing a platform and resources that facilitate the sharing and accessibility of datasets within the computer vision community.

### Source Datasets

- **BadmintonC Dataset**  
  *Himani Jain (2023)*  
  [View on Roboflow Universe](https://universe.roboflow.com/himani-jain/badmintonc)

- **shuttlecock Dataset**  
  *AdwProj (2025)*  
  [View on Roboflow Universe](https://universe.roboflow.com/adwproj/shuttlecock-yu8ra)


## License Information
- MIT license applies to all content

## Future Updates
Additional documentation will be provided upon research publication. For questions regarding permitted usage, please contact the repository owner. adithynaraj03@gmail.com 
