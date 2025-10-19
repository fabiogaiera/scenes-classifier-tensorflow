# Scenes Classifier with TensorFlow

## Model training

1. Execute python notebooks in notebooks directory 

## API deployment that serves the model

1. python -m venv .venv

2. source `.venv/bin/activate (Linux & MacOS)` or `.venv\Scripts\activate (Windows)`

3. pip install tensorflow 

4. pip install fastapi[all]

5. pip install pillow

6. Create main.py file (main.py file already created in repository)

7. uvicorn main:app --reload

8. Web application published in http://localhost:8000
