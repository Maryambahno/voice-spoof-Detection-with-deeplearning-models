# Deep-Learning-Based-Voice-Spoof-Detection

## Project Overview

This project implements and evaluates multiple deep learning architectures for voice spoof detection using the ASVspoof 2019 Logical Access (LA) dataset.

The primary objective is to distinguish between genuine and spoofed speech samples using neural network-based classification models.

The implemented models include:

* Convolutional Neural Network (CNN)
* Long Short-Term Memory (LSTM)
* Gated Recurrent Unit (GRU)
* Bidirectional GRU (BiGRU)

A comparative analysis is performed using both classification and threshold-independent evaluation metrics.

---

## Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Equal Error Rate (EER)
* Minimum normalized tandem Detection Cost Function (min-tDCF)

These metrics allow both performance comparison and robustness evaluation.

---

## Dataset

This project uses the publicly available:

**ASVspoof 2019 Logical Access (LA) Dataset**

Dataset URL:
[https://datashare.ed.ac.uk/handle/10283/3336](https://datashare.ed.ac.uk/handle/10283/3336)

Note: The dataset is not included in this repository due to its large size. Please download it from the official source and place it in the appropriate directory before running the code.

---

## Requirements

Python 3.9+

Required libraries:

* json
* numpy
* pandas
* tensorflow 
* scikit-learn
* matplotlib
* librosa

Install dependencies using:

```
pip install -r requirements.txt
```

---

## How to Run

1. Download the ASVspoof 2019 LA dataset.
2. Update the dataset path in the configuration file.
3. Run the desired model script

## Results Summary

The GRU model achieved the lowest EER and strongest robustness among all models. LSTM achieved the highest overall classification performance in terms of accuracy and F1-score, while BiGRU and CNN also produced competitive and stable results.


The detailed performance analysis is available in the thesis documentation.

---
