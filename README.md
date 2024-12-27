# AI-Recycling-Classifier

##Code Setup
recycling-classifier/
├── data/
│   ├── recycling/       # Images of recycling items
│   ├── garbage/         # Images of garbage items
├── models/              # For saving trained models
├── notebooks/           # Jupyter notebooks for experiments
├── src/                 # Source code
│   ├── __init__.py
│   ├── preprocess.py    # Preprocessing logic
│   ├── train.py         # Model training script
│   ├── evaluate.py      # Model evaluation script
├── requirements.txt     # Python dependencies
├── app.py               # Flask API for image classification
├── README.md            # Project documentation


## Dataset
1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/alistairking/recyclable-and-household-waste-classification).
2. Place the extracted folder in `data/images/`.
3. Run `src/preprocess.py` to preprocess the data and generate `.npy` files.

Alistair King, www.kaggle.com/datasets/alistairking/recyclable-and-household-waste-classification
