# CSE425-Project
Brac University CSE425 Neural Network Project
By: Md. Nayeemul Hasan (ID:22101622)
Section : 2 (CSE425)

# Non-Deterministic Unsupervised Neural Network for Clustering
## CSE425: Neural Networks Course Project

This project implements and evaluates a deep Convolutional Variational Autoencoder (ConvVAE) for the task of unsupervised clustering on the MNIST dataset. The work follows a systematic approach, starting from a deterministic baseline and iteratively improving the model architecture and training procedure.

---

## Requirements

The project is implemented in Python 3. The following libraries are required to run the code:

* PyTorch
* torchvision
* scikit-learn
* pandas
* numpy
* matplotlib
* seaborn

You can install all required dependencies using pip:
```bash
pip install torch torchvision scikit-learn pandas numpy matplotlib seaborn
```
### Method 1: Running in Google Colab (Recommended)

1.  **Upload:** Upload the `Clustering_Notebook.ipynb` file to your Google Drive.
2.  **Open:** Open the notebook using Google Colaboratory.
3.  **Set Runtime:** Ensure the hardware accelerator is set to GPU for faster training. You can do this via the menu: `Runtime` -> `Change runtime type` -> `Hardware accelerator` -> `GPU`.
4.  **Run All:** Execute all cells in the notebook in order from top to bottom. A simple way to do this is `Runtime` -> `Run all`.

The notebook is self-contained and will perform all necessary steps: training the models, performing the clustering, calculating the final evaluation metrics, and generating all the visualizations for the report.


### Method 2: Running Locally

1.  **Setup Environment:** Make sure you have a local Python environment with all the libraries listed in the **Requirements** section installed.
2.  **Hardware:** While the code will run on a CPU, using a machine with a CUDA-enabled GPU is highly recommended to significantly reduce training time.
3.  **Execute:** Open the `Clustering_Notebook.ipynb` file in a local Jupyter Notebook or JupyterLab instance and run all the cells in order.


