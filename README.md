```markdown
# End-to-End Machine Learning Pipeline with MLOps Tools

This project automates the machine learning lifecycle, from training to deployment and monitoring, using various MLOps tools.

## Overview
- **Objective**: Train a churn prediction model and deploy it as a web application.
- **Tools**: Cookiecutter, DVC, GitHub, MLFlow, Flask, Pytest.
- **Dataset**: Utilizes a churn dataset from Kaggle.

## Project Structure
- **Environment**: Conda environment with Python 3.7.
- **Project Structure**: Utilizes Cookiecutter's data science project template.
- **Data Management**: Version control with DVC for datasets.
- **Model Training**: Python scripts in the `src/models` folder.
- **Deployment**: Flask app deployed on Heroku.
- **Monitoring**: Model performance tracked with MLFlow and monitored using EvidentlyAI.

## Getting Started
1. Create Conda environment: `conda create -n churn_model python=3.7`.
2. Clone the repository: `git clone <repository_url>`.
3. Install dependencies: `pip install -r requirements.txt`.
4. Set up DVC: `dvc init`.
5. Track dataset: `dvc add train.csv`.
6. Train model: `python src/models/train_model.py`.
7. Deploy app: `heroku create` and `git push heroku main`.

## Usage
- Train Model: `python src/models/train_model.py`.
- Deploy App: `heroku create` and `git push heroku main`.
- Monitor Model: Utilize MLFlow dashboard and EvidentlyAI for monitoring.

## Contributors
- Shanaka Chathuranga

## License
This project is licensed under the MIT License.
```
