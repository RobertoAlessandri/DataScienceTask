# DataScienceTask

## Table of Contents
- [Requirements](#requirements)
- [Project Overview](#project-overview)
- [Part 1: Gender Classification](#part-1-gender-classification)
- [Part 2: Speaker Classification](#part-2-speaker-classification)
- [Repository Structure](#repository-structure)
- [Contact](#contact)

## Requirements
- requirements1.txt for Part 1
- requirements2.txt for Part 2
- Having downloaded the LibriSpeech dataset into a "LibriSpeech_ASR_corpus" folder
- Having downloaded the wav2vec2.0 model
The necessity of two different virtual environments is due to the fact that after finishing Part 1, I discovered that to use the wav2vec model it was needed a lower version of Python.

## Project Overview
This project focuses on gender and speaker classification using audio data. The project is divided into two main parts.

### Part 1: Gender Classification
In the first part of the project, we perform gender classification using audio files. We leverage the [LibriSpeech](https://www.openslr.org/12/) dataset and extract MFCC features for the audio files. The steps include:
1. Download the LibriSpeech dataset (dev-clean and dev-other corpus).
2. Extraction of  MFCC features for audio files of the dataset.
3. Conduction of data analysis to gain insights, including feature distribution, outlier detection, and normalization techniques.
4. Training and evaluation gender classification models using various machine learning algorithms (Linear Regression, Support Vector Machine, FastForward Neurall Network, Convolutional Neural Network).

### Part 2: Speaker Classification
The second part of the project delves into speaker classification. We use the [wav2vec2.0 model](https://github.com/facebookresearch/fairseq/blob/main/examples/wav2vec/README.md) to [extract features](https://github.com/facebookresearch/fairseq/blob/main/examples/wav2vec/README.md#wav2vec) from audio signals and perform a speaker classification task. The steps include:
2. Download the wav2vec2.0 base model (No Finetuning) and apply it to extract features from audio files.
3. Two types of analysis:
   - Quantitative analysis using prediction models and objective metrics (precision, recall, accuracy).
   - Qualitative analysis using dimensionality reduction and clustering algorithms to visualize results.

## Repository Structure
The project is structured into 2 Jupyter Notebooks, 1 for each part.

## Contact
r.alessandri@outlook.com
