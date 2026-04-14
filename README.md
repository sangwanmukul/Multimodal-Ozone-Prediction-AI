# Multimodal AI for Ozone Layer Depletion Prediction

## Overview
This project implements a **Multimodal AI-based system** to predict ozone layer depletion using multiple data sources:

- Satellite Images (Vision Transformers - ViT)
- IoT Sensor Data (Time-Series Transformers - TFT)
- Atmospheric Chemistry (Graph Neural Networks - GNN)

## Problem
Traditional models rely on single-source data and fail to capture real-time and spatiotemporal dependencies in ozone prediction.

## Solution
We developed a hybrid AI system combining:
- ViT for spatial image understanding
- TFT for temporal forecasting
- GNN for chemical interaction modeling

## 🧠 Models Used
- GCN (Graph Convolutional Network)
- GAT (Graph Attention Network)
- GraphSAGE
- Spatiotemporal GNN (ST-GNN)

## Results
| Model | RMSE | MAE |
|------|------|------|
| GCN | 0.92 | 0.64 |
| GAT | 0.89 | 0.61 |
| GraphSAGE | 0.87 | 0.59 |
| ST-GNN | **0.79** | **0.52** |

Best Model: **ST-GNN (captures spatial + temporal patterns)**

## Features
- Real-time prediction using Apache Kafka + Spark
- Multimodal data fusion
- Self-supervised learning for improved accuracy
- Scalable AI pipeline

## Tech Stack
- Python
- PyTorch Geometric
- Apache Spark
- Kafka
- NumPy, Pandas

## Project Structure
├── notebooks/
├── data/
├── docs/
├── models/
├── src/


## How to Run
```bash
git clone https://github.com/sangwanmukul/Multimodal-Ozone-Prediction-AI
cd Multimodal-Ozone-Prediction-AI
pip install -r requirements.txt
jupyter notebook

## Author
**Mukul Sangwan**
AI Engineer | ML Researcher
