# Anime Face GAN Project

This repository contains two Jupyter notebooks for training and inference of a Conditional GAN (CGAN) model to generate anime faces. The project is designed to work with pre-trained model weights that can be downloaded from Google Drive.

## Notebooks

### 1. `CGAN_Anime.ipynb`
This notebook is used for training the CGAN model on an anime face dataset. It covers:
- Data loading and preprocessing
- Model architecture definition
- Training loop with loss tracking
- Saving the trained model weights

### 2. `inference.ipynb`
This notebook is used for generating anime faces using the pre-trained model weights. It covers:
- Loading the pre-trained generator and discriminator models
- Generating and saving anime face images
- Logging generated images to Weights & Biases (W&B)

## Pre-trained Model Weights

The pre-trained model weights can be downloaded from the following Google Drive link:

[Download Pre-trained Weights](https://drive.google.com/drive/folders/1iKadakU1esGfcOEu1d9LS1GYKlg7LqdH?usp=sharing)

### Instructions
1. Download the `generator_final.pth` and `discriminator_final.pth` files from the Google Drive link.
2. Place these files in the root directory of your project.

## Running the Notebooks

### Training the Model
1. Open `CGAN_Anime.ipynb` in Jupyter Notebook or JupyterLab.
2. Run all cells to train the model.
3. The model weights will be saved as `generator_final.pth` and `discriminator_final.pth`.

### Running Inference
1. Ensure that the pre-trained weights (`generator_final.pth` and `discriminator_final.pth`) are in the project directory.
2. Open `inference.ipynb` in Jupyter Notebook or JupyterLab.
3. Run all cells to generate anime faces using the pre-trained model.
4. Generated images will be saved in the `inferimages` directory and logged to W&B.

## Dependencies

Install the required packages by running:

```bash
pip install -r requirements.txt
