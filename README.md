# Credit Risk Assessment using Bayesian Networks  

This project implements a **Bayesian Network model** for credit risk assessment, leveraging a dataset with 27 key financial indicators to classify credit approval flags and prioritize applicants.  

## Key Features  
- **Structure Learning**: Applied the Big Brave algorithm, optimized with Hill Climbing and k2 scoring, for effective structure discovery.  
- **Parameter Estimation**: Utilized Maximum Likelihood Estimation (MLE) to compute conditional probabilities accurately.  
- **Performance**: Achieved **95.53% accuracy**, outperforming traditional machine learning models like SVM and Decision Tree.  
- **Data Preprocessing**: Included techniques such as normalization, correlation analysis, and quartile categorization to enhance data quality.  

## Results  
- Bayesian Network: 28 nodes and 63 edges, representing relationships among financial indicators.  
- Superior accuracy and performance compared to alternative models.  

| Method       | Accuracy | F1 Score | Precision | Recall |  
|--------------|----------|----------|-----------|--------|  
| Big Brave    | 95.53%   | 95.50%   | 95.50%    | 95.53% |  
| SVM          | 82.01%   | 81.75%   | 81.61%    | 82.01% |  
| HC           | 80.68%   | 80.44%   | 80.25%    | 80.68% |  
| GES          | 80.51%   | 80.13%   | 79.85%    | 80.51% |  
| Decision Tree| 78.11%   | 77.95%   | 77.84%    | 78.11% |  
| PC           | 76.44%   | 71.60%   | 68.66%    | 76.44% |

### Bayesian Network
![Bayesian_Network](https://github.com/user-attachments/assets/7cfc73e3-e747-4713-b1a2-f321dfa01ff6)


## Contributions  
This model extends existing approaches by:  
- Increasing model accuracy to 95.53% through advanced structure learning.  
- Enhancing interpretability and scalability for large datasets.  
![Bayesian_Network](https://github.com/user-attachments/assets/e9bb0b26-0f60-4b07-822c-27922f07393d)
