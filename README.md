# Federated Learning in Image Classification Models
MDS 2024 Capstone Project Report 
<center>
<div style="text-align: center;">
    <img src="https://repository-images.githubusercontent.com/241095326/04ad19b5-b049-4d07-8555-60699f80f0d8" alt="Federated Learning Diagram" width="500"/>
</div>
</center>

## Project Overview
This repository includes the presentation and report for the project done during the MDS Capstone Project 2024. We developed a federated learning solution for image classification using the _Flower_ framework. The project utilizes an open-source [Osteosarcoma dataset](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=52756935), which contains 1,144 images categorized into three classes i.e. non-tumor, necrotic tumor, and viable tumor. Our goal for the project was to advance decentralized training methods for machine learning models, specifically targeting bone cancer detection. By employing federated learning techniques, we aimed to enhance data privacy, minimize communication overhead, and improve the efficiency of training models distributed across multiple institutions.


## Project Features

- Implementation of federated learning using the Flower framework.
- Supports multiple data partitioning techniques: IID (PyTorch `random_split`) and Non-IID (Dirichlet distribution).
- Includes various aggregation strategies such as FedAvg, FedProx, FedAvgM, and FedTrimmedAvg.
- Configurable through a single YAML file for ease of experimentation.
- Pre-configured to work with the Osteosarcoma dataset.
