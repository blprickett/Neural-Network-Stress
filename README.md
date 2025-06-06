# Neural-Network-Stress

## Applying the neural network to the Tesar and Smolenksy (2000) patterns:

To do this, you'll need two files:
* Seq2Seq.py
* Stress_Net_Tesar.ipynb
  
The Python notebook (ending in ".ipynb") are meant to be run in [Google Colab](https://colab.research.google.com/). To do this, you'll need to have a Google Drive account with a directory named "NN_Stress", which itself contains the "Input_Files" directory provided in this repo and an empty directory named "Output_Files". To upload the notebooks to your Google Drive, open a [Colab](https://colab.research.google.com/) tab, and click "File > Upload Notebook". 

The Seq2Seq.py script will also need to be uploaded to your Google Drive, but it should be located in the "My Drive" directory (i.e. the directory that appears automatically when you go to the URL "drive.google.com"). No need to worry about this script's dependencies--they should all be installed automatically on the machine your Colab notebook is running on.

## Learning Window-based Stress Patterns with the Neural Network:

To do this, you'll need two files:
* Seq2Seq.py
* Stress_Net_Windows.ipynb

This notebook works the same way and also requires the Seq2Seq.py file to be in your Google Drive.

## Agent-based Learning of Stress Patterns with Neural Networks:

To do this, you only need a single file, Stress-Net-Interactive-ExceptionLearning.ipynb. Within the first block of code in that notebook, you'll need to set the "my_dir" variable to a path showing where you want to save the model's output files (no input files needed for these simulations because the languages are produced randomly).
