# NeuroVoice — Imagined Speech Classification Using EEG

## Project Overview
NeuroVoice is a machine learning project that uses EEG signals to classify imagined speech into target classes.

## Dataset
- **Trials:** 720
- **Channels:** 8 per trial
- **Samples:** 1,000 per channel
- **Sampling Frequency:** 500 Hz
- **Duration:** 2 seconds per trial
- **Classes:** `play`, `Happy`, `under`, `ball`, `dog`, `cat`

## Technologies
Python, NumPy, Pandas, SciPy, Scikit-learn, Matplotlib, and Joblib.

## Workflow
1. Data loading and validation
2. Data splitting
3. EEG preprocessing
4. Feature extraction
5. Model training
6. Model evaluation
7. Class prediction

## Project Structure
- `data/` — Raw and processed EEG data
- `src/` — Python source code
- `models/` — Trained models
- `reports/` — Evaluation results


## Current Status
Data loading, splitting, and preprocessing have been completed. Feature extraction, model training, evaluation, and prediction are part of the remaining development workflow.

## Future Work
Improve classification performance, compare machine learning models, and investigate deep learning approaches.
