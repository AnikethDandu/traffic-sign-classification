# Traffic Sign Classification
[![forthebadge](http://forthebadge.com/images/badges/made-with-python.svg)](http://forthebadge.com)

A Python Convolutional Neural Network that classifies images of traffic signs

## Installation
In order to use this project, you will need to download the [dataset](https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign). You will also need to store the downloaded folder as a zip in Google Drive at My Drive/ColabNotebooks/Data

If you need to run a terminal command, preface the command with "!" and run it in a cell. For example
```bash
!pip install torch
```

## Usage
Google Colab
* Initialize a runtime
* Set the notebook to use the GPU by navigating to Runtime/Change Runtime Type/Hardware accelerator

Google Drive
* Connect the notebook with Google Drive under Files using the "Mount Drive" button
* Run the Google Drive cell

Run every cell in successive order. The project will train the model from scratch and print its loss after every epoch. The project will also evaluate the model and print various accuracies
