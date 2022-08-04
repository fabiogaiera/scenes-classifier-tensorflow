# Scenes Classifier with TensorFlow

## The code works with TensorFlow 2.8.0

## Model training

1. Execute python notebooks in notebooks directory 

## API deployment that serves the model

1. python -m venv .venv

2. source `.venv/bin/activate (Linux & MacOS)` or `.venv\Scripts\activate (Windows)`

3. pip install -r requirements.txt

4. Create main.py file (main.py file already created in repository)

5. uvicorn main:app --reload

6. Web application published in http://localhost:8000
