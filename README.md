# 🎵 Music Genre Classification

Note : This repository is one of the challenges made for the event "ForkThis" organized by the chapter Computer Society of India(CSI), VIT Vellore in the year 2025.
# 📌 Overview

This project focuses on automatic music genre classification using pre-extracted audio features. The main goal is to train machine learning models that can predict the genre of a track based on its numerical audio characteristics.

# 📂 Dataset Description

The dataset consists of two main CSV files:

tracks.csv – metadata for tracks. This file contains hierarchical column headers (two rows of headers). From this, only the track ID and the top-level genre label were extracted for use.

features.csv – numerical audio features for each track, with track IDs as indices.

A subset of the dataset was used, focusing only on tracks with a clearly defined top genre.

Dataset link : https://drive.google.com/drive/folders/1tnlfqa4KoZFVeQ-xMq9rHM3i6TJeRFqI?usp=sharing 

# ⚙️ Installation

## Clone the repository
```
git clone https://github.com/a-niveditha/MusicGenreClassification.git
```

## Navigate to the project directory
```
cd MusicGenreClassification
```

## Create a virtual environment (recommended)
```
python -m venv venv
```

## Activate the virtual environment
## On Windows:
```
#First run:
cd venv/Scripts

#Then:
./Activate.ps1
```

## On macOS and Linux:
```
#First run:
cd venv/bin

#Then:
source ./activate
```

## Install project dependencies from requirements.txt
```
pip install -r requirements.txt
```

