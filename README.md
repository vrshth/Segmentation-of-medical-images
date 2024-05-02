Retinal Fundus Image Segmentation Project
Introduction
This project develops a segmentation model for retinal fundus images, which segments images into vessels and background. The aim is to aid medical professionals in diagnosing and planning treatments by providing clear, segmented visualizations of retinal vessels.

Prerequisites
Before you begin, ensure you have the following installed:

Python 3.8 or later
TensorFlow 2.x
NumPy
Matplotlib
OpenCV
Installation
To set up the project environment, follow these steps:

Dataset
This project uses the DRIVE dataset, which contains retinal images with corresponding manually annotated masks. Ensure you download this dataset from DRIVE Dataset and place it in the data/ directory within the project folder.


Results
Sample Image
The results section includes a sample retinal fundus image along with its true and predicted masks, demonstrating the model's effectiveness in accurately delineating retinal vessels.

Predicted Masks
We also display multiple images with their predicted masks, adjusted for brightness to enhance visibility. These results affirm the model's capability in precise vessel segmentation across different conditions.

Conclusion
The project has successfully developed a segmentation model for retinal fundus images, showing promising results in vessel identification which is crucial for medical diagnostics and planning.
