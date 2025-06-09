# 🪨 Sedimentary Rock Classification with Small Datasets

This project demonstrates how high-accuracy classification of sedimentary rocks can be achieved using a **small, expert-curated dataset** and a **fine-tuned ResNet-34** model. The model focuses on classifying three major types of sedimentary rocks—**sandstone**, **conglomerate**, and **shale**—based on their macroscopic features observed in field photos.

## 📁 Project Structure

- `Sedimentary_Rock_Classification.ipynb`: Step-by-step Jupyter notebook for training and evaluation.
- `DLCV Final/`: Folder containing training and validation images.
- `README.md`: Project description and usage instructions.

> 📷 All rock images are cropped from real field photos, manually selected to highlight clear geological features.

# 🚀 Getting Started
Download this repository and the linked DLCV Final/ folder. https://drive.google.com/drive/folders/10mhBLLlQrdJEIpKuGI_YKggWqQTBe502?usp=sharing

Place the Sedimentary_Rock_Classification.ipynb notebook inside the dataset folder (same level as class subfolders).

Open the notebook with Jupyter and follow the instructions step by step to:

Load and visualize the dataset

Fine-tune the pretrained ResNet-34 model

Evaluate the results

## 🎯 Results
With fewer than 30 images per class, the model achieves 100% accuracy on the validation set, demonstrating the power of feature-guided sample selection and transfer learning.

## 🧭 Future Work
This model can be extended to a two-stage classification system:

First, distinguish between sedimentary, igneous, and metamorphic rocks.

Then, perform fine-grained classification within each category.

## 📬 Contact
For questions or suggestions, feel free to open an issue or contact the project maintainer.



## 🔧 Requirements

- Python **3.12**
- Jupyter Notebook
- Required Python packages:
  - `torch`, `torchvision`
  - `matplotlib`, `numpy`
  - `scikit-learn`
  - `tqdm` (optional, for progress bars)

You can install the dependencies via pip:

```bash
pip install torch torchvision matplotlib numpy scikit-learn tqdm

