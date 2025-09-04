# brain-tumor-mri-classification
Brain MRI tumor classification using EfficientNet and Grad-CAM visualization.

🧠 Brain Tumor Classification from MRI using EfficientNet

This project uses transfer learning with EfficientNetB0 to classify brain MRI scans into four categories:

Glioma tumor

Meningioma tumor

Pituitary tumor

No tumor

⚠️ Disclaimer: This project is for educational and research purposes only and must not be used for medical decision-making.

📁 Dataset

The dataset used in this project is the Brain Tumor MRI Dataset
 by Masoud Nickparvar, hosted on Kaggle.

It contains MRI images organized into four folders corresponding to:

Glioma tumor

Meningioma tumor

Pituitary tumor

No tumor

To download it automatically, you will need a Kaggle API key (kaggle.json). Instructions are included in the notebook.

📂 Repository Structure
brain-tumor-classification/
│
├── brain_tumor_classification.ipynb   # Main Jupyter/Colab notebook <br>
├── requirements.txt                    # Dependencies (pip) <br>
├── environment.yml                     # Dependencies (conda)  <br>
├── .gitignore                          # Ignore large/unnecessary files  <br>
└── README.md                           # Project documentation  <br>

🚀 Getting Started
Option 1: Run in Google Colab

Open the notebook in Colab:


Upload your Kaggle API key (kaggle.json) to download the dataset.

Run all cells.

Option 2: Run Locally (pip)
# Clone repo
git clone https://github.com/Jenimon1011/brain-tumor-mri-classification.git
cd brain-tumor-classification

# Install dependencies
pip install -r requirements.txt

# Start Jupyter
jupyter notebook brain_tumor_classification.ipynb

Option 3: Run Locally (conda)
# Create environment
conda env create -f environment.yml
conda activate brain-tumor-classification

# Start Jupyter
jupyter notebook brain_tumor_classification.ipynb

📊 Results

Test accuracy: ~XX%

Evaluation metrics: Precision, Recall, F1-score per class (see notebook).

Confusion matrix: Shows classification distribution.

Grad-CAM visualizations: Highlights MRI regions influencing predictions.

(Add an image of your confusion matrix or Grad-CAM here!)

🔧 Built With

[TensorFlow/Keras](https://www.tensorflow.org/guide/keras)

[NumPy](https://numpy.org)

[Matplotlib](https://matplotlib.org/?utm_source=chatgpt.com)

[scikit-learn](https://scikit-learn.org)

[OpenCV](https://opencv.org)

✍️ Author

Your Name (@your-username)

⚠️ License & Disclaimer

This project is licensed under the MIT License.
Not for clinical use. Research/educational purposes only.
