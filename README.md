# Quantum Fingerprint Matching using PennyLane

This project implements a hybrid classical–quantum fingerprint matching system.
Classical image preprocessing and SIFT feature extraction are combined with
quantum similarity estimation using a swap test implemented in PennyLane.

## Workflow
- Fingerprint preprocessing using OpenCV
- Feature extraction using SIFT
- Quantum amplitude encoding of features
- Quantum swap test for similarity measurement

## Tools Used
- Python
- OpenCV
- PennyLane
- NumPy
- Matplotlib

## How to Run
1. Clone the repository
2. Install dependencies:
   pip install -r requirements.txt
3. Open the notebook in Jupyter:
   jupyter notebook notebook/fingerprint_quantum.ipynb

## Note
The fingerprint dataset is not included due to size and licensing restrictions.
Users can plug in their own fingerprint images.
