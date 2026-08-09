## Installation
```bash
git clone https://github.com/your-username/rainfall-landslide-prediction-ml.git
cd rainfall-landslide-prediction-ml
pip install -r requirements.txt
```

## Usage
```bash
# Preprocess data
python src/preprocessing.py

# Train ML models
python src/train_ml.py

# Train DL models
python src/train_dl.py

# Evaluate models
python src/evaluate.py
```

## Models Used
| Model         | Type | Notes                          |
|---------------|------|---------------------------------|
| Logistic      | ML   | Baseline model                  |
|  Regression   |      |                                 |
| XGBoost       | ML   | Gradient boosting               |
| SVM           | ML   | Kernel-based classifier         |
| CNN           | DL   | Fully connected network         |
| (CNN+RF)      | DL   | Sequential rainfall pattern     |

## Results
Summarize key results here, e.g. best-performing model and metrics,
along with any relevant plots (confusion matrix, ROC curve, susceptibility map)

## Tech Stack
- Python
- Scikit-learn
- TensorFlow / PyTorch
- Pandas, NumPy
- Matplotlib, Seaborn

## Future Work
- Incorporate real-time rainfall data via API
- Deploy as a web-based early-warning dashboard
- Add satellite imagery-based CNN models

## Contributing
Contributions are welcome. Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
Harshvardhan Singh — harshvardhansinghh31@gmail.com
