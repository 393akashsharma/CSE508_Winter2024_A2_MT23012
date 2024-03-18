# Multimodal Retrieval System
### This repository contains the implementation of a Multimodal Retrieval System developed for the CSE508 Information Retrieval Winter 2024 Assignment-2 by Akash Kumar (MT23012).

## Introduction
This system aims to efficiently retrieve similar images and reviews based on a given query, utilizing both text and image inputs.

## Problem Statement
The assignment required the development of a Multimodal Retrieval System using a dataset consisting of image URLs and corresponding text reviews for a given product.

## Approach
Data Preprocessing: Text and image preprocessing steps were implemented.
Text Feature Extraction and TF-IDF Calculation: TF-IDF scores were calculated for text reviews.
Cosine Similarity Calculation: Cosine similarity between image feature vectors and TF-IDF vectors was computed.
Challenges
Challenges include semantic gap, scalability, subjectivity, data quality, interpretability, feature representation, consistency in preprocessing, and robustness.

## Results and Analysis
The system computed cosine similarity between image and text features, revealing insights into correlations between visual content and textual descriptions.

## Conclusion
The study demonstrated the efficacy of leveraging both visual and textual features for content-based similarity analysis. The combined approach offers promising avenues for enhancing recommendation systems and image retrieval algorithms.

## Repository Structure
data/: Contains dataset files.
src/: Contains source code files.
## Usage
Refer to the source code files in the src/ directory for instructions on using the Multimodal Retrieval System.

## Dependencies
Python 3.x
NumPy
NLTK
BeautifulSoup
scikit-learn
## License
This project is licensed under the MIT License .
