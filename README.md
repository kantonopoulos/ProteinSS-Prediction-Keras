# Protein Secondary Structure Prediction with Neural Networks
*Individual Assignment - Bioinformatics Course*

## Overview
This repository contains the code, data and report for a project conducted as part of a master's bioinformatics course. The project aimed to enhance protein secondary structure prediction using neural networks. The code is implemented in Python and executed in Jupyter Notebook.

## Project Description
The project utilized neural networks to predict protein secondary structures from amino acid sequences. It incorporated multiple sequence alignment data and employed a sliding-window approach to improve prediction accuracy. Various techniques, including dropout and ensemble modeling, were explored to optimize model performance and mitigate overfitting.

## Repository Structure
- Jupyter Notebook: Contains the Python code for the project.
- Data: Includes datasets used for training, cross-validation, and testing the models. The data were sourced from Katarina Elez's GitHub repository at https://github.com/katarinaelez/protein-ss-pred.
- Results: Contains visualizations and metrics evaluating model performance.
- Documentation: Additional documentation and resources related to the project.

## Usage
To run the code, ensure you have Python installed along with necessary libraries like NumPy, Pandas, Matplotlib, Seaborn, TensorFlow, Keras, and scikit-learn. Clone the repository and execute the Jupyter Notebook files in the 'Notebooks' directory.

## Performance
<table>
    <thead>
        <tr>
            <th></th>
            <th colspan=3>Ensemble Fully Connected Neural Network</th>
        </tr>
    </thead>
    <tbody align="right">
        <tr align="center">
            <td></td>
            <td>Class</td>
            <td>Blind test</td>
        </tr>
        <tr>
            <td>Sensitivity</td>
            <td>Helix</td>
            <td>0.7415±0.0147</td>
        </tr>
        <tr>
            <td>y</td>
            <td>Sheet</td>
            <td>0.6436±0.0121</td>
        </tr>
        <tr>
            <td></td>
            <td>Coil</td>
            <td>0.8373±0.0137</td>
        </tr>
        <tr>
            <td>Specificity</td>
            <td>Helix</td>
            <td>0.9209±0.0147</td>
        </tr>
        <tr>
            <td>Specificity</td>
            <td>Sheet</td>
            <td>0.9451±0.0038</td>
        </tr>
        <tr>
            <td>Specificity</td>
            <td>Coil</td>
            <td>0.7513±0.0134</td>
        </tr>
        <tr>
            <td>Accuracy</td>
            <td>Helix</td>
            <td>0.8511±0.0013</td>
        </tr>
        <tr>
            <td>Accuracy</td>
            <td>Sheet</td>
            <td>0.8724±0.0009</td>
        </tr>
        <tr>
            <td>Accuracy</td>
            <td>Coil</td>
            <td>0.7831±0.0035</td>
        </tr>
    </tbody>
</table>
