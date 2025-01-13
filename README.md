# Sound Analysis Project

## Project Description
This project leverages machine learning techniques to analyze sound files. Specifically, the focus is on using audio features such as Mel-Frequency Cepstral Coefficients (MFCC) to classify different sound clips. The workflow involves feature extraction, data preprocessing, training machine learning models, and evaluating their performance.

## Installation

### Step 1: Clone the Repository
Clone the repository to your local machine:


git clone https://github.com/zenithbhatt/sound-analysis.git
cd sound-analysis




Usage

Step 1: Extract Features (MFCC)
The first step is to extract features from the sound clips. You can use the extract_mfcc.py script to extract Mel-Frequency Cepstral Coefficients (MFCC) from the audio files:

python scripts/extract_mfcc.py


Step 2: Train a Classification Model
To train a machine learning model using the extracted MFCC features, use the train_model.py script:

python scripts/train_model.py


Step 3: Evaluate the Model
After training, evaluate the model using the following script:

python scripts/evaluate_model.py




Project Structure
.
├── en/                    # Raw or pre-processed data files
├── main.ipynb/            # Jupyter notebooks for exploration
├── venv/                  # Python virtual environment
├── .gitignore             # Git ignore file
├── README.md              # Project documentation
├── pca_transformer.pkl    # Serialized model file
└── requirements.txt       # List of dependencies


Acknowledgments
The dataset used for this project is the Common Voice dataset.
Libraries used include librosa for audio processing, scikit-learn for machine learning, and imbalanced-learn for data balancing.