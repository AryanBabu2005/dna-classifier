# DNA Classifier using CGR and CNN 

This machine learning project classifies DNA sequences as **Human** or **Non-Human** using **Chaos Game Representation (CGR)** converted into images, and a **Convolutional Neural Network (CNN)** model for classification.

## Project Structure

project_dna_cgr/
├── dna_classifier.ipynb # Main Jupyter Notebook
├── /dataset # Contains DNA sequence data (optional)
├── /cgr_images # CGR image data used for training/testing
├── model.h5 # Trained CNN model (if included)
├── requirements.txt # Python dependencies
└── README.md # Project documentation


---

##  Dataset

The dataset consists of DNA sequences sourced from public databases such as **[NCBI](https://www.ncbi.nlm.nih.gov/)**. These sequences are converted to **CGR images** that represent the sequence's genomic structure.

---

##  Methodology

1. DNA sequences are converted to CGR images (Chaos Game Representation).
2. CGR images are labeled as Human or Non-Human.
3. A Convolutional Neural Network (CNN) is trained on these images.
4. The trained model predicts the class of new DNA sequences.

---

##  Libraries Used

- `TensorFlow` / `Keras`
- `NumPy`
- `Pandas`
- `Matplotlib`
- `scikit-learn`
- `OpenCV`
- `os`, `shutil`, `glob`

---

## 🚀 How to Run

### 1. Clone the repo:
```bash
git clone https://github.com/AryanBabu2005/dna-classifier.git
cd dna-classifier
2. Install dependencies:
pip install -r requirements.txt
3. Run the notebook:
jupyter notebook dna_classifier.ipynb

 Results
Model trained on 1000+ CGR images

Achieved test accuracy of ~99% 

 Acknowledgments
NCBI Genome Database

Tutorials and research papers on Chaos Game Representation

TensorFlow documentation
