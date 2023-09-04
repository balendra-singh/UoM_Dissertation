![license](https://img.shields.io/badge/License-MIT-green.svg)![python](https://img.shields.io/badge/python-3.10-blue)
# University Of Manchester MSc Data Science (CSDI Pathway) Dissertation Project
# Title - Classification of User Story For Software Development

## Installation
1. Upgrade python pip package manager. 
```bash
python3 -m pip install --user --upgrade pip
python3 -m pip --version
```
2. Create python virtual environment and activate install.
```bash
python3 -m venv uom_venv
.\uom_venv\Scripts\activate
```
3. Install required packages.
```bash
pip install -r requirements.txt
```

## Steps for classifying a given user-story dataset

1. The data should be contain two columns (text and label).
2. Run python notebooks as per the order specified in the prefix.
3. For hyperparameter tuning use the dataset_classification's second sections.
4. For benchmarking models use PyTorchBenchmark or TensorFlowBenchmark from [Hugging Face library.](https://huggingface.co/docs/transformers/benchmarks)

## Research Design Structure

![Research Design Structure](https://github.com/balendra-singh/UoM_Dissertation/blob/main/images/methodology.png)

## Results

| Model Name  | Runtime  | Epochs  | Learning Rate | Batch Size | Accuracy | Precision | Recall | F1-Score |
|-------------|----------|---------|---------------|------------|----------|-----------|--------|----------|
|             | **Model Training** | | | | **Model Evaluation** | | | |
|             | Runtime  | Epochs  | Learning Rate | Batch Size | Accuracy | Precision | Recall | F1-Score |
| ALBERT      | 591.02   | 16      | 2.19e-05      | 16         | 0.7371   | 0.7876    | 0.6649 | 0.7051   |
| DistilBERT  | **473.73** | 13  | 4.71e-05      | 32         | 0.7482   | 0.7827    | 0.7509 | 0.7481   |
| RoBERTa     | 578.64   | **11** | 4.89e-05      | 16         | **0.7998** | **0.8013** | 0.7533 | 0.7501   |
| BERT        | 971.01   | 18      | 2e-05         | 8          | 0.7666   | 0.7359    | **0.7618** | **0.7627** |
| XLNet       | 1187.75  | 22      | 1.3e-5        | 4          | 0.7409   | 0.7043    | 0.6791 | 0.6879   |
| GPT-2       | 2119.92  | 17      | 2e-5          | 2          | 0.6997   | 0.6672    | 0.6305 | 0.6427   |
| BERT4RE     | 703.60   | 21      | 3.97e-5       | 16         | 0.6736   | 0.7135    | 0.6279 | 0.6587   |


## BibTeX entry and citation info
```bibtxt
@inproceedings{sentinel2023,
  author    = {Balendra Singh},
  title     = {Classification of User Stories For Software Development},
  year      = {2023},
  url       = {https://github.com/balendra-singh/UoM_Dissertation},
}
```
