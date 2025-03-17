# **Prices Predictor**

Welcome to the **Prices Predictor** repository! This project is a complete end-to-end solution for training machine learning models from scratch to deployment. It includes data analysis, model training, and a CI/CD pipeline for automated deployment.

## **Project Overview**

This repository covers the full lifecycle of an ML project:
- **Data Analysis** – Exploratory Data Analysis (EDA) notebooks.
- **Model Training** – Training ML models from scratch.
- **Evaluation** – Performance analysis and tuning.
- **Deployment** – End-to-end CI/CD pipeline for model deployment.

## **Project Structure**

```
prices_predictor/
│── data/
│   ├── raw/
│   ├── processed/
│
│── notebooks/
│   ├── eda.ipynb  # Data analysis & visualization
│   ├── model_training.ipynb  # Training ML models
│
│── src/
│   ├── data_preprocessing.py
│   ├── model.py
│   ├── train.py
│   ├── evaluate.py
│
│── deployment/
│   ├── docker/
│   ├── ci_cd_pipeline/
│
│── requirements.txt
│── README.md
│── .github/workflows/  # CI/CD workflows
```

## **Installation & Setup**

To get started, clone the repository:

```bash
git clone https://github.com/IQLynxAI/prices_predictor.git
cd prices_predictor
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## **Usage**

### **Run Data Analysis**
Use the Jupyter notebooks in the `notebooks/` directory to explore and preprocess data.

```bash
jupyter notebook notebooks/eda.ipynb
```

### **Train the Model**
Run the training script to train the model:

```bash
python src/train.py
```

### **Evaluate the Model**
To test model performance, run:

```bash
python src/evaluate.py
```

### **Deployment**
This repository includes a CI/CD pipeline for automated deployment. Modify the `.github/workflows/` files to configure your pipeline.

To build and run a Docker container locally:

```bash
docker build -t prices-predictor .
docker run -p 8000:8000 prices-predictor
```

## **Contributing**

We welcome contributions! If you would like to contribute, please fork this repository and submit a pull request with detailed changes.

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## **Contact**

For questions or feedback, feel free to reach out:

- **Name**: IQLynxAI
- **Email**: [contact@iqlynxai.com](mailto:contact@iqlynxai.com)
- **GitHub**: [IQLynxAI](https://github.com/IQLynxAI)
- **LinkedIn**: [IQLynxAI](https://www.linkedin.com/company/iqlynxai/)
- **Instagram**: [IQLynxAI](https://www.instagram.com/iqlynx.ai/)
