

# Project Title: A Motif-Based Network Analysis of Transaction Data from Ekko : To Understand Consumer Behavior and their Carbon Emissions

## Overview

This project analyzes consumer transaction patterns to investigate their relationship with carbon emissions using network analysis techniques. By leveraging a unique dataset from Ekko, which tracks CO2 emissions for individual transactions, we construct and compare transaction networks for high and low carbon-emitting customers. The primary objective is to uncover spending patterns that contribute to carbon emissions and to identify strategies for promoting sustainable spending habits.

## Files

- **MotifAnalysis.ipynb**: This Jupyter Notebook contains the code for constructing transaction networks from the dataset and analyzing these networks to identify significant motifs associated with high and low carbon emissions.

- **PymFinderResultAnalysis.ipynb**: This Jupyter Notebook analyzes the results obtained from the motif detection tool, PymFinder. It includes methods for statistical analysis of motifs and evaluates their significance in relation to carbon emissions.

- **S2603217.pdf**: This document provides a detailed description of the project, including the research aims, objectives, methodology, and key findings. It serves as the formal documentation of the project and includes sections such as the literature review, methodology, and results discussion.

## Requirements

To run the code files, ensure you have the following dependencies installed:

- Python 3.7 or higher
- Jupyter Notebook
- NetworkX
- Pandas
- Matplotlib
- PymFinder (for motif detection)


For PymFinder, follow the installation instructions provided in its official documentation.

## Usage

1. **Data Preprocessing**: Open `MotifAnalysis.ipynb`. This notebook handles data collection, preprocessing, and the construction of transaction networks. Ensure the dataset is properly loaded, and the paths are correctly specified.

2. **Network Analysis and Motif Detection**: Continue in `MotifAnalysis.ipynb` to perform network analysis. This includes generating graphs where nodes represent Merchant Category Codes (MCCs) and edges represent transitions between them.

3. **Motif Analysis**: After detecting motifs using PymFinder, open `PymFinderResultAnalysis.ipynb` to analyze the motif data. This notebook compares motif frequencies between high and low emission customer groups and evaluates their statistical significance.

4. **Results Interpretation**: Use the insights from `PymFinderResultAnalysis.ipynb` to understand the relationship between transaction motifs and carbon emissions. The results can guide further research or practical applications in promoting sustainable consumer behavior.

## Key Concepts

- **Network Motifs**: Recurring, significant subgraphs within the transaction networks that provide insights into consumer behavior patterns.
- **Carbon Emissions Analysis**: By associating carbon emissions data with transaction motifs, we can identify specific patterns contributing to higher environmental impacts.

## Acknowledgements

This project was supervised by Valerio Restocchi, with mentorship from Ogy Simeonov. Special thanks to Ekko for providing the dataset and to all contributors for their support.


## Contact

For any inquiries or further information, please contact Raga Sreehitha Paritala at [sreehithaparitala@gmail.com].
