# Machine Learning for Computer Vision

This repository contains a deep learning project focused on Out-of-Distribution (OOD) detection and classification using the StreetHazards dataset.

## 📂 Repository Structure
* **main.ipynb**: The primary Jupyter Notebook containing data preprocessing, model architecture (ResNet-based), training loops, and evaluation metrics.
* **ood_presentation_results.png**: A visualization of the model's performance on anomaly detection and segmentation.
* **.gitignore**: Configured to exclude the large `Data/` directory (containing over 10,000 images) to keep the repository lightweight.

## 🚀 Getting Started

### Prerequisites
You will need the following Python libraries:
* `torch`
* `torchvision`
* `numpy`
* `matplotlib`
* `PIL`

### Dataset
The project uses the **StreetHazards** dataset for anomaly segmentation. 
* The dataset should be placed in a folder named `Data/`.
* Due to its size, this folder is ignored by Git.

## 📊 Results
The model evaluates images to identify "hazards" or objects that fall outside of the standard training distribution. Visual results can be seen in `ood_presentation_results.png`.

## 🛠 Usage
1. Clone the repository.
2. Ensure the StreetHazards dataset is structured correctly in the `Data/` directory.
3. Open `main.ipynb` in VS Code or Jupyter Lab and run the cells sequentially.