
# Adaptive Multi-Scale Attention Deep Neural Network for Tabular Data  (AKA Excited Attention)

This repository contains the implementation and analysis of an interpretable Adaptive Multi-Scale Attention Deep Neural Network (Excited Attention) for tabular data. The proposed architecture aims to address the performance limitations of deep learning techniques when applied to structured tabular data, while providing multiple levels of explainability.

 **Abstract**

Deep learning (DL) has proven to be a valuable tool for analyzing signals such as sounds and images, thanks to its capabilities of automatically extracting relevant patterns and its end-to-end training properties. However, when applied to tabular structured data, DL has exhibited some performance limitations compared to shallow learning techniques. This work presents a novel technique for tabular data called Adaptive Multi-Scale Attention deep neural network architecture (also named Excited Attention). By exploiting parallel multilevel feature weighting, the Adaptive Multi-Scale Attention is able to successfully learn the feature attention and thus achieve high levels of F1 score on seven different classification tasks (on small, medium, large, and very large datasets) and low mean absolute errors on four regression tasks of different sizes. In addition, Adaptive Multi-Scale Attention provides four levels of explainability (i.e., a comprehension of its learning process and therefore of its outcomes):

- Calculates attention weights to determine which layers are most important for given classes.
- Shows each feature's attention across all instances. 
- Understands learned feature attention for each class to explore feature attention and behavior for specific classes.
- Finds non-linear correlations between co-behaving features to reduce dataset dimensionality and improve interpretability.

These interpretability levels, in turn, allow for employing the Adaptive Multi-Scale Attention as a useful tool for feature ranking and feature selection.


# Cite:
Dentamaro, V., Giglio, P., Impedovo, D., Pirlo, G., & Di Ciano, M. (2024). An interpretable adaptive multiscale attention deep neural network for tabular data. IEEE Transactions on Neural Networks and Learning Systems, 1–15. https://doi.org/10.1109/TNNLS.2024.3392355

