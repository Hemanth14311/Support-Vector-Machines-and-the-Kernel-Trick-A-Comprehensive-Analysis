# Support Vector Machines and the Kernel Trick

This project demonstrates how Support Vector Machines (SVMs) behave on
linearly and non-linearly separable data, and how the kernel trick
(especially the RBF kernel) transforms SVMs into powerful non-linear
classifiers.

## Project Structure
.
├── svm_kernel_trick.ipynb   # Main Jupyter notebook  
├── requirements.txt         # Python dependencies  
└── README.md                # Project overview and run instructions  

## Installation
Install all required libraries:

```
pip install -r requirements.txt
```

## Running the Notebook
Launch Jupyter:

```
jupyter notebook
```

Open `svm_kernel_trick.ipynb` and run all cells from top to bottom.  
This notebook generates all figures used in the report, including:

- Moons and circles datasets  
- Linear SVM decision boundaries  
- RBF SVM decision boundaries  
- Gamma comparison plots  
- Confusion matrices for linear and RBF SVMs  

## Dataset Notes
All synthetic datasets are generated using scikit-learn utilities.  
The Breast Cancer dataset is loaded automatically from `sklearn.datasets`.

## Reproducibility
- Random seeds are fixed  
- Dependencies are pinned  
- Notebook runs sequentially without modification  
