# msc-thesis-aims-sa
Master Thesis, Msc Mathematics, AI for Science, **African Institute for Mathematical Sciences**, South Africa. 
Fully Funded through **Google DeepMind Scholarship 2025-26**.

Master thesis Title : “Counterfactual Invariance via Conditional Mean Embeddings: Robustness to Domain Generalisation for Tabular Data”.(2026)

Author: Michael Fitiavana RANDRIAMIFIDY

Supervisor: Dr. Krikamol Muandet

**Abstract**

Machine learning models learn distributions from finite observational data without knowledge of underlying causal relations, risking exploitation of spurious correlations rather than stable causal structures. 
The methods used in this project may be used to solve three types of problem on large tabular datasets under a unified framework of counterfactual invariance: spurious correlation reduction, domain generalisation, and individual fairness. 
We enforce invariance of model predictions to a designated counterfactual feature using the Hilbert-Schmidt Conditional Independence Criterion (HSCIC).
Our contribution operationalises this on tabular classification via a warm-start strategy that decouples task learning from invariance enforcement. This approach is computationally efficient, skipping kernel costs during warm-up while achieving counterfactual invariance comparable to that of joint training from a random initialisation.
We confirm in a classification task that HSCIC and the oracle counterfactual invariance certificate, Variance of Counterfactuals (VCF), decrease together as the trade-off parameter increases. Our experiments demonstrate that invariance can be learned without a catastrophic drop in performance. Furthermore, the Counterfactual Invariance Prediction approach successfully outperforms feature deletion in synthetic and real-world setting. Crucially, we identify a breakdown at high trade-off parameter values where the HSCIC continues to decrease while the oracle VCF increases; this discordance happens alongside a notable drop in performance. Finally, we confirm that learned invariance transfers out-of-domain without retraining; however, predictive robustness transfer is fully realised only in synthetic settings since we can control the intensity of the out-of-domain shift on synthetic data generated from known structural causal model. 
