# Evolutionary-Universal-Perturbation-Attack
Evolutionary Universal Perturbation Attack

The effectiveness of Universal Perturbation Attacks (UPA) in undermining the robustness of Deep Convolutional Neural Networks (DCNN) classifiers has emerged as a substantial threat, particularly in critical domains such as autonomous vehicles, clinical diagnosis, and face recognition. To counteract these attacks, there is a growing interest in employing UPA for adversarial training of deep convolutional networks.

Despite the proven success of evolutionary algorithms in solving complex non-convex problems, the exploration of evolutionary techniques and strategies specifically tailored for UPA has been limited in the literature. This study focuses on the innovative NSGA-II evolutionary framework implemented by an Integer Coded Genetic Algorithm to evolve UPA.

The evolutionary UPA is meticulously structured, analyzed, and compared under two evolutionary optimization frameworks: (i) constrained single-objective evolutionary UPA and (ii) Pareto double-objective evolutionary UPA. The methodology's efficiency is evaluated on the GoogleNet convolutional Neural Network, using the Imagenet dataset.

The results reveal that, under identical experimental conditions, the constrained single-objective technique outperforms the Pareto double-objective approach. It successfully breaches a deep network, leading to a noteworthy reduction in the average detection score to $0.446429$. This observation underscores the significance of prioritizing the constraint of noise invisibility over the conflicting objective of minimizing noise power. The study sheds light on the intricate dynamics of evolutionary UPA and its potential implications for enhancing the resilience of deep learning models in the face of adversarial attacks.

Guideline: 
EUPA.m is the main file. 
The database of Image Net has been provided too. 
