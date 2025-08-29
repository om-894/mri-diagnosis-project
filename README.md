
# MRI Diagnosis Project

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-1.10%2B-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## Overview

Built a deep learning system to automate the diagnosis and classification of neurological conditions from MRI scans. Used convolutional neural networks (CNNs) in PyTorch to support early detection of brain abnormalities and compared performance against traditional machine learning methods such as linear regression and random forests.

## Key Features

- Preprocessing pipeline for MRI scan normalisation and augmentation
- Custom PyTorch models optimized for 3D medical imaging
- Interactive Jupyter notebooks for visualisation and analysis
- Comprehensive evaluation metrics

## Technology Stack

- **Framework**: PyTorch
- **Data Processing**: NumPy, Pandas, SimpleITK
- **Visualization**: Matplotlib, Seaborn
- **Development**: Jupyter, Git

## Project Structure

```
mri-diagnosis-project/
├── data/                  # Data directory (not included in repo)
│   ├── Testing/           # MRI preprocessing utilities
│   ├── Training/          # Training scripts and utilities
├── notebooks/             # Jupyter notebooks for exploration and visualization
└── README.md              # Project documentation
```

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/mri-diagnosis-project.git
cd mri-diagnosis-project

# Create and activate virtual environment (optional)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Results

Achieved 97.18% test accuracy with my second CNN, slightly higher than my first, smaller model at 96.41%. Both outperformed traditional methods, with random forest and linear regression reaching 93.44% and 90.01%, respectively.


## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

*Note: This project is for research and educational purposes only and should not be used for clinical diagnosis without proper validation and regulatory approval.*
