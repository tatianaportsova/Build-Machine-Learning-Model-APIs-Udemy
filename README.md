# Build-Machine-Learning-Model-APIs-Udemy
For the documentation, visit the course on Udemy.

    pip install -r requirements.txt
    pip install -r ml_api/requirements.txt
    python regression_model/train_pipeline.py
    pytest tests -W ignore::DeprecationWarning
    pytest ml_api/tests -W ignore::DeprecationWarning
