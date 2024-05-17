# CS6787 Final Project

## Overview
This repository contains the code developed for the CS6787 Final Project, focusing on audio processing and model training. The project involves preprocessing audio files by mixing them and implementing three distinct models for further processing or analysis.

## Project Structure

### Audio Preprocessing
The `preprocessing` directory contains scripts used for mixing audio files. These scripts are designed to combine multiple audio sources into a single mixed audio file, which can be used as input for the subsequent modeling stages.

### Models
The repository includes implementation code for three different models, each located in their own respective directory:
- `model1`: Contains the implementation of the first model, including training and evaluation scripts.
- `model2`: Contains the implementation of the second model, with its specific requirements and usage instructions.
- `model3`: Houses the third model's code, detailing its architecture and functionalities.

## Getting Started

### Prerequisites
Before running the scripts, ensure you have the following installed:
- Python 3.8 or higher
- Required Python libraries: `numpy`, `torch`, `librosa` (Install using `pip install -r requirements.txt`)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/LawrenceTLin/CS6787FinalProject.git


Usage
To run the preprocessing scripts, navigate to the preprocessing folder and execute the following:
python preprocess.py --input_dir=path/to/input --output_dir=path/to/output


**Authors**
Lawrence T. Lin, Justin Tahmassepbur
