# Vertex AI End-to-End

An end-to-end machine learning example on Vertex AI (Google Cloud Platform), from raw data to deployment as an API endpoint.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Pipeline Overview](#pipeline-overview)
- [Deployment](#deployment)


## Introduction

This project demonstrates how to build and deploy a machine learning model using Vertex AI. It covers the entire workflow, from data ingestion to model training and deployment.

## Prerequisites

- Google Cloud account
- Vertex AI enabled in your Google Cloud project
- Python 3.x
- Required libraries (listed in `requirements.txt`)

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd vertex_ai_end_to_end
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Prepare your data and place it in the `data` directory.
2. Run the pipeline:
   ```bash
   python code/ml_pipeline.py
   ```

3. Follow the instructions in the Jupyter notebook `vertex_deploy.ipynb` for deployment.

## Pipeline Overview

The pipeline consists of several components:
- **Data Ingestion**: Fetches and preprocesses data.
- **Model Training**: Trains the model using the prepared dataset.
- **Model Evaluation**: Evaluates the model's performance.
- **Deployment**: Deploys the trained model to Vertex AI.

## Deployment

To deploy the model, follow the steps outlined in the `vertex_deploy.ipynb` notebook. Ensure that all necessary APIs are enabled in your Google Cloud project.
