# Crypto Clustering  
This project aims to analyze and cluster cryptocurrencies based on their price changes using K-Means clustering and Principal Component Analysis (PCA).

## Files
- `Crypto_Clustering_draft.ipynb`: Jupyter Notebook containing the Python code for the project.
- `crypto_market_data.csv`: Dataset with cryptocurrency market data.
- `Images/`: Folder for storing images, charts, or any visual output generated during analysis.

## Results

- Elbow curve for the original data vs PCA data.  
![image](https://github.com/Glowary/CryptoClustering/assets/141696007/a7220b0b-8ea0-4de5-b6a8-02d2a634923b)
![image](https://github.com/Glowary/CryptoClustering/assets/141696007/dcaf9ae8-b728-4fba-9150-dba131ec11d2)

- Scatter plot of cryptocurrency clusters based on the original data vs PCA data
![image](https://github.com/Glowary/CryptoClustering/assets/141696007/3e1ccf04-d06f-4a76-a7bc-6890ecd09f66)
![image](https://github.com/Glowary/CryptoClustering/assets/141696007/6f9e3111-01d8-4492-ae73-3a750ad23ef5)  

## Conclusion
PCA data reduces the number of features that impacted the cluster analysis results. The elbow plots showed that original and PCA data had an optimal k-value of 4. However, the inertia values differed significantly between the original and PCA versions, with PCA having a lower inertia (49.7 compared to 79). The PCA data resulted in tighter clusters, suggesting that reducing the number of features results in more compact clusters.
