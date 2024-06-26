<p align="center">
    <img src="https://github.com/TourID/Machine-Learning/assets/159881870/e6be832b-8bc3-4259-9508-7ea4ba7503b6" alt="tur2">
</p>

## Table Of Contents
- [Table Of Contents](#Table-Of-Contents)
- [Overview](#overview)
- [Feature](#feature)
- [Dataset](#dataset)
- [Contact The Developers](#contact-the-developers)

## Overview
In this project, the ML teams implemented algorithms for tourism place recommendations using Neural Collaborative Filtering. The steps we followed included collecting, cleaning, and balancing a public dataset from Kaggle. We then split the data into training, validation, and testing sets. Using Neural Collaborative Filtering, we built the model architecture, set up callbacks to stop training at the desired loss, and achieved a loss and MSE below 0.2. Finally, we applied our model using Keras for implementation.

## Feature
The neural collaborative filtering model combines user and place embeddings to capture both collaborative and content-based aspects of the data. These embeddings are concatenated and passed through several dense layers, which learn high-level representations of the interactions. This architecture leverages both user-place interactions and auxiliary information to enhance recommendation accuracy.
The model is trained using mean squared error (MSE) loss and the Adam optimizer, which optimizes its ability to predict user-place interactions. By using K-Fold Cross-Validation, the model's robustness and generalization are enhanced. This ensures consistent performance across different subsets of the data, preventing overfitting and improving the overall reliability of the recommendations.  iterating for 100 epochs with a batch size of 128. The trained model is then saved in .Keras format for future usage and deployment.

## Dataset
The public dataset we used can be found here (https://www.kaggle.com/datasets/aprabowo/indonesia-tourism-destination). In addition, we also added a new dataset that includes new users and new ratings to explore tourist destinations based on the place IDs that have ratings from the top 20 user IDs.

## Contact The Developers

| NAME | JOB | Contact
| ------ | ------ | ----- |
| Novi Dwi Fitriani  | ML Engineer | [![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/novidf/) [![GitHub](https://img.shields.io/badge/GitHub-black?style=flat-square&logo=github)](https://github.com/noviidwi) |
| Riska Septyani| ML Engineer |  [![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/riskaseptyani) [![GitHub](https://img.shields.io/badge/GitHub-black?style=flat-square&logo=github)](https://github.com/riskasptyani) |
| Deriansyah Aulia Muharram | ML Engineer  | [![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/deriansyah-aulia-muharram) [![GitHub](https://img.shields.io/badge/GitHub-black?style=flat-square&logo=github)](https://github.com/smerull) |


