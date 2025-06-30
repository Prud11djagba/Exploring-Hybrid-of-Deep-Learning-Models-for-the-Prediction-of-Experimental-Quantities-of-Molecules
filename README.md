# Exploring-Hybrid-of-Deep-Learning-Models-for-the-Prediction-of-Experimental-Quantities-of-Molecules
The prediction of experimental molecular properties is a critical task in computational chemistry, enabling faster and more accurate assessments of molecular behavior without the need for costly laboratory experiments. Deep learning has emerged as a state-of-the-art approach across various domains, including cheminformatics, due to its capacity to learn complex, nonlinear patterns. Recent research has shown that hybrid architectures combining different deep learning  can significantly enhance model performance. In this study, we investigate a hybrid modeling framework that integrates Graph Neural Networks (GNNs) and Probabilistic Graphical Models (PGMs) for the prediction of key experimental molecular quantities, including $IC_{50}$, $\logP$, $\logD$, water solubility, hydration free energy, and retention time. The proposed models are trained and evaluated on multiple large-scale experimental datasets and compared against standard deep learning baselines, such as Long Short-Term Memory (LSTM) networks and transformer-based models such as ChemBERT. While prior work has focused on theoretical graph-based predictions of $IC_{50}$​ for limited datasets (e.g., Flavonoids), our study expands this scope to broader molecular libraries.




# Results

The plots and figures below provide a comprehensive visualization of model performance across the five experimental datasets using various deep learning architectures. These include training and validation the learning curves , predicted vs.\ actual scatter plots, and residual histograms for each model—PGM, GNN, PGM+GNN, LSTM, and ChemBERTa—applied to IC$_{50}$, log P, log D, water solubility, and hydration free energy. The loss curves demonstrate the convergence behavior of each model, with GNN and PGM+GNN showing more stable and lower final loss values than LSTM and ChemBERTa in most cases. Scatter plots reveal that ChemBERTa predictions align closely with actual values for log P but are more dispersed in tasks like IC$_{50}$ and log D, suggesting variability in generalization. Residual histograms show tighter error distributions for GNN-based models, especially the PGM+GNN hybrid, confirming their superior consistency. These visual diagnostics reinforce the numerical findings discussed in the paper and underscore the comparative strengths of hybrid graph-probabilistic approaches.




### IC_50
![image alt](https://github.com/Prud11djagba/Exploring-Hybrid-of-Deep-Learning-Models-for-the-Prediction-of-Experimental-Quantities-of-Molecules/blob/44286115da8018d9923c73244f732b505bda85e1/Figure%20PGM%2BGNN%20on%20IC50.png)


















