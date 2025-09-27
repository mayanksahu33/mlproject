## End to End Machine Learning Project

This repository contains an end-to-end machine learning project for predicting student performance. The project demonstrates the complete ML workflow, including data ingestion, preprocessing, model training, evaluation, and deployment using a web interface.

### Project Structure

```
mlproject/
├── app.py                  # Flask app for web interface
├── requirements.txt        # Python dependencies
├── setup.py                # Project setup
├── artifacts/              # Saved models, preprocessors, and datasets
├── src/                    # Source code
│   ├── components/         # Data ingestion, transformation, and model training modules
│   └── pipeline/           # Training and prediction pipelines
├── notebook/               # Jupyter notebooks for EDA and model training
├── templates/              # HTML templates for web app
└── README.md               # Project documentation
```

### Features
- Data ingestion and preprocessing
- Model training with CatBoost
- Model evaluation and metrics
- Web app for predictions
- Jupyter notebooks for EDA and experimentation

### Setup Instructions
1. **Clone the repository:**
	```bash
	git clone https://github.com/mayanksahu33/mlproject.git
	cd mlproject
	```
2. **Create a virtual environment (optional but recommended):**
	```bash
	python -m venv venv
	venv\Scripts\activate  # On Windows
	# source venv/bin/activate  # On Linux/Mac
	```
3. **Install dependencies:**
	```bash
	pip install -r requirements.txt
	```

### Usage
#### 1. Train the Model
Run the training pipeline to train and save the model:
```bash
python src/pipeline/train_pipeline.py
```

#### 2. Run the Web App
Start the Flask app to serve predictions:
```bash
python app.py
```
Then open your browser at [http://localhost:5000](http://localhost:5000)

#### 3. Explore Notebooks
Check the `notebook/` directory for EDA and model training experiments.

### Project Author
Maintained by [mayanksahu33](https://github.com/mayanksahu33)