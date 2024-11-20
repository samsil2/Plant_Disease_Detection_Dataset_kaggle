# Plant Disease Detection Dataset (Kaggle)

This repository contains resources and datasets for detecting plant diseases using machine learning and deep learning techniques. The dataset has been sourced from [Kaggle]([https://www.kaggle.com](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)), and this repository includes a Jupyter Notebook to streamline the workflow for training, evaluating, and visualizing plant disease detection models.

---

## 📂 Dataset Overview

The dataset consists of images of various plants and their corresponding diseases. Each image is labeled with the plant species and the specific disease affecting it. The dataset is organized into directories representing classes.

- **Categories**: Includes healthy and diseased plant samples.
- **Format**: Images are in `.jpg` format.
- **Structure**: Found 70295 files belonging to 38 classes for training. Found 17572 files belonging to 38 classes.
- dataset/ ├── train/ │ ├── class_1/ │ ├── class_2/ │ └── ... dataset/ ├── valid/ │ ├── class_1/ │ ├── class_2/ └── ...
- test/ │ ├── class_1/ │ ├── class_2/ │ └── ...


---

## 🛠️ Requirements

To work with this repository, you need the following:

- Python 3.8+
- Jupyter Notebook
- Required Libraries:
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

Install dependencies with:

```bash
pip install -r requirements.txt
```

🚀 Usage
1. Clone the Repository
   ```bash
   git clone https://github.com/samsil2/Plant_Disease_Detection_Dataset_kaggle.git
   cd Plant_Disease_Detection_Dataset_kaggle
   ```
2. Download the Dataset
Ensure you have downloaded the dataset from Kaggle and placed it in the dataset/ directory, structured as mentioned above or Plant_Disease_Detection_Dataset_kaggle directory dataset and test directory are included.

3. Open the Jupyter Notebook
Start Jupyter Notebook and open the notebook file for this project:
```bash
train and validation.ipynb
prediction.ipynb

```

4. Run the Cells
Follow the steps in the notebook:

- Preprocess the dataset.
- Train the plant disease detection model.
- Evaluate the model.
- Visualize predictions.

📊 Results
The model achieves the following performance on the dataset: <br>
<img src="https://raw.githubusercontent.com/samsil2/Plant_Disease_Detection_Dataset_kaggle/master/accuracy.png" width="700" height="500">

🤝 Acknowledgements <br>
- Dataset provided by Kaggle. <br>
- This version is tailored for Jupyter Notebook users and provides clear guidance for working with the project.





