# QuantumTSTransformer
This repository shows Quantum Time-Series Transformer for resting-state functional MRI analysis by Park et al. (2025) [1]. The Quantum Time-Series Transformer is a quantum machine learning algorithm for analyzing time-series data. In particular, we use the model to train resting-state fMRI data from UK Biobank and Adolescent Brain Cognitive Development Study.

Here, we developed the algorithm based on Quixer [2], a language model quantum transformer algorithm that uses linear combination of unitaries and quantum singular vector transform to realize attention mechanisms of classical transformers. As language transformers are known to handle long sequence information effectively, our Time-Series Quantum Transformer which is a modified version of the Quixer model to handle time-series data can also effectively process long sequences of spatio-temporal information.

Quantum transformers have potential for improved performance, parameter efficiency, and sample size efficiency. That is, it can exhibit relatively good performance with smaller number of trainable parameters and training sample size than its classical counterparts.


## References
[1] Park, J. J., Seo, J., Bae, S., Chen, S. Y.-C., Tseng, H.-H., Cha, J., & Yoo, S. (2025, Aug 31 - Sep 5). Resting-state fMRI Analysis using Quantum Time-series Transformer. _2025 IEEE International Conference on Quantum Computing and Engineering (QCE)_. https://doi.org/10.48550/arXiv.2509.00711

[2] Khatri, N., Matos, G., Coopmans, L., & Clark, S. (2024). Quixer: A Quantum Transformer Model. _arXiv preprint_. DOI:arXiv:2406.04305 
