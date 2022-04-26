## Epileptic Seizure Detection using EEG Signals

This repositories contains a series of notebooks for the application of machine learning classifiers on the Temple University Hospital (TUH) EEG dataset.

The dataset is publicly available [here](https://isip.piconepress.com/projects/tuh_eeg/html/downloads.shtml).

### Library Usage
* [MNE](https://mne.tools/stable/index.html#)
* [MNE-Features](https://mne.tools/mne-features/api.html)
* [Numpy](https://numpy.org/)
* [Matplotlib](https://matplotlib.org/)
* [Pandas](https://pandas.pydata.org/)
* [scikit-learn](https://scikit-learn.org/stable/index.html)
* [ast](https://docs.python.org/3/library/ast.html)

## Result
Sensitivity (or Recall), Specificity, Precision, Accuracy, and F<sub>1</sub> Score reported on six machine learning classifiers

Models | Sensitivity (or Recall)| Specificity | Precision | Accuracy | F<sub>1</sub> Score
---|---|---|---|---|---
Logistic Regression | 93.39 | 91.16 | 93.30 | 92.43 | 0.9300
K-Nearest Neighbour | 93.05 | 88.85 | 92.00 | 91.28 | 0.9250
Decision Tree | 92.06 | 90.04 | 92.52 | 91.20 | 0.9250
Random Forest | 96.40 | 81.15 | 87.65 | 90.01 | 0.9183
Support Vector Machine | 93.64 | 91.37 | 93.67 | 92.70 | 0.9400
Linear Discriminant Analysis | 90.08 | 87.77 | 90.65 | 89.08 | 0.9050

## Citation
If you find this work useful, please cite

```
@INPROCEEDINGS{9756061,  
author={Khan, Irfan Mabood and Khan, Mohd Maaz and Farooq, Omar},  
booktitle={2022 5th International Conference on Computing and Informatics (ICCI)},   
title={Epileptic Seizure Detection using EEG Signals},   
year={2022},  
pages={111-117},  
doi={10.1109/ICCI54321.2022.9756061}}
}
```