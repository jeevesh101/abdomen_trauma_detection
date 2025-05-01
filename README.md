🩻 Abdominal Trauma Detection – RSNA 2023
This project focuses on automating the detection of abdominal trauma using CT scan data, as part of the RSNA 2023 Abdominal Trauma Detection Challenge. We explore organ segmentation, injury classification, and model evaluation techniques to build a robust deep learning pipeline for medical imaging diagnostics.

📌 Project Objectives
Detect injuries in 11 abdominal organs (e.g., liver, spleen, kidneys) from CT scans.

Segment organs using metadata from DICOM files.

Train and evaluate deep learning models for trauma classification.

🧪 Methods Used
Data Processing:

Extracted relevant frames from DICOM files.

Normalized pixel data and resized images.

Modeling Techniques:

Used pre-trained CNNs (e.g., ResNet) for classification.

Applied multi-label classification for organ-level injury prediction.

Evaluation:

Custom loss functions and metrics for injury detection.

Visualized predictions and segmented regions.

📊 Results (Snapshot)
Injury detection accuracy: ~83% on validation.

Better performance with deeper CNNs using fine-tuning.

Notable challenge: Imbalanced data across organ classes.
📌 Dependencies
Python 3.8+

NumPy, Pandas, OpenCV

PyTorch or TensorFlow

Matplotlib, Seaborn

pydicom
