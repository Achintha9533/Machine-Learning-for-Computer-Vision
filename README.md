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

## 📚 References

[1] Standardized Max Logits: Jung, S., Lee, J., Gwak, D., Choi, S., & Choo, J. (2021). Standardized Max Logits: A Simple yet Effective Approach for Identifying Unexpected Road Obstacles in Urban-Scene Segmentation. arXiv:2107.11264.

[2] DMLNet: Cen, J., Yun, P., Cai, J., Wang, M. Y., & Liu, M. (2021). Deep Metric Learning for Open World Semantic Segmentation. arXiv:2108.04562.

[3] StreetHazards & OOD Scaling: Hendrycks, D., Basart, S., Mazeika, M., Zou, A., Kwon, J., Mostajabi, M., Steinhardt, J., & Song, D. (2022). Scaling Out-of-Distribution Detection for Real-World Settings. arXiv:1911.11132.

[4] Residual Pattern Learning (RPL): Liu, Y., Ding, C., Tian, Y., Pang, G., Belagiannis, V., Carneiro, G., & Reid, I. (2023). Residual Pattern Learning for Pixel-wise Out-of-Distribution Detection in Semantic Segmentation. arXiv:2211.14512.

[5] Open-World Segmentation: Sodano, M., Magistri, F., Nunes, L., Behley, J., & Stachniss, C. (2024). Open-World Semantic Segmentation Including Class Similarity. arXiv:2403.07532.