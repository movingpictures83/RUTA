# RUTA
# Language: R
# Input: TXT (key, value pairs)
# Output: PREFIX
# Tested with: PluMA 1.1, R 4.0.0
# Dependency: ruta_1.1

Differential analysis using unsupervised neural networks (Charte et al, 2018)

The plugin accepts as input a TXT file with keyword, value pairs:
csvfile: Dataset
features: List of features (line by line)
categories: Sample categories (line by line)
variables: Number of variables to count

Data will be output to a CSV file, with each sample and its x-y coordinates.
A plot will also be produced in a PDF file using the PREFIX

