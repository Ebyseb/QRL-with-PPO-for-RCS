Quantum Circuit Curriculum Trainer
A reinforcement learning framework for optimizing quantum circuits under realistic noise using fidelity and cross-entropy benchmarking (XEB). Built with Qiskit, Gymnasium, and Stable-Baselines3.
🚀 Overview
This project trains a PPO agent to construct quantum circuits that maximize fidelity or XEB scores. It uses a curriculum of increasing complexity to guide learning across multiple stages.
🔬 Highlights
• 	✅ Fidelity & XEB metrics for circuit evaluation
• 	🧠 PPO agent from Stable-Baselines3
• 	🧪 Noisy simulation via Qiskit Aer + FakeJakartaV2
• 	🎯 Curriculum learning across 4 stages
• 	📊 Metric visualization with Matplotlib & Seaborn
pip install numpy gymnasium qiskit qiskit-aer qiskit-ibm-runtime stable-baselines3 matplotlib seaborn

Outputs
• 	Line plots of fidelity/XEB progression
• 	Heatmaps of fidelity and reward
• 	Best circuit printed at the end
• 	All saved in  disk
