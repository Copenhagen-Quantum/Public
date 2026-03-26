# Copenhagen Quantum — Public Explainers

Interactive visual explainers for quantum computing applications in financial services. Each file is a self-contained voiced presentation with Canvas visualisations, KaTeX math rendering, and Web Speech API narration.

**Live site:** [copenhagen-quantum.github.io/Public](https://copenhagen-quantum.github.io/Public/)

## Explainers

### Portfolio Optimisation

| Explainer | Description |
|-----------|-------------|
| [Markowitz to QPU](markowitz_to_qpu_voiced.html) | From classical portfolio theory through QUBO, simulated annealing, SQA, to D-Wave hardware |
| [SQA Visualisation](sqa_visualization.html) | Interactive simulated quantum annealing demo (Three.js) |

### Quantum Anomaly Detection (Fraud)

| Explainer | Description |
|-----------|-------------|
| [QAD Introduction](qad_voiced.html) | 18-scene introduction to the QAD framework |
| [QAD Deep-Dive](qad_implementation_voiced.html) | 34-scene implementation walkthrough: ZZ kernel, autoencoder, QAOA, n*(ρ) theorem |

### Quantum Credit Scoring

| Explainer | Description |
|-----------|-------------|
| [Credit Scoring Explainer](quantum_credit_explainer.html) | 15-scene quantum credit scoring pipeline |
| [3D Customer Clusters](quantum_credit_3d.html) | Interactive 3D cluster visualisation (Three.js) |
| [Credit Transitions](quantum_credit_transition.html) | 3D particle transition visualisation (Three.js) |

## Technology

- HTML5 Canvas 2D / Three.js for 3D visualisations
- KaTeX for mathematical notation
- Web Speech API with UK English narration
- No build step — open any `.html` file directly in a modern browser
