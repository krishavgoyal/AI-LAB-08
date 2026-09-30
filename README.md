# Artificial Intelligence (CS F407) - Laboratory Submissions

**Name:** Krishav Goyal  
**ID:** 2024A7PS0855G

This repository contains my completed laboratory assignments for the Artificial Intelligence course (CS F407). Each module corresponds to a specific lab topic and includes the fully executed Jupyter Notebook, a detailed markdown report, and the reference lab handout.

## Repository Overview

| Laboratory | Description | Deliverables |
|:---|:---|:---|
| `Agents_Lab` | Implementing goal-based agents | Notebook, Report, Handout |
| `Search_Lab` | Exploration of Search Algorithms and A* | Notebook, Report, Handout |
| `Logic_Lab` | Logical reasoning and Prolog planning | Notebook, Report, `planner.pl`, Handout |
| `BN_Lab` | Bayesian Networks & language modeling | Notebook, Report, Handout |
| `Neural_Models` | Neural networks, backpropagation & layers | Notebook, Report, Handout |
| `Transformers_Lab` | Pre-trained Transformer architectures | Notebook, Report |

## Setup & Execution

To reproduce the environments and run the notebooks locally, you can use the following setup process:

```bash
# Create and activate a virtual environment
python -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Lab
jupyter lab
```

**Note:** All notebooks are provided in an executed state with cached outputs. Random seeds have been explicitly set to ensure reproducibility of the metrics discussed in the reports. 

- The `Logic_Lab` requires `swi-prolog` to be installed on your system.
- The `Transformers_Lab` will download necessary model weights (approx. 1GB) during its initial run.

## Methodology

Throughout these labs, I adopted a structured problem-solving approach:
1. **Analyze** the problem statement and requirements.
2. **Design** the algorithm or model structure.
3. **Implement** the solution in Python/Prolog.
4. **Evaluate** the empirical performance and verify edge cases.

Rather than just answering conceptual questions with text, I prioritized implementing the logic to empirically demonstrate the answers (e.g., measuring state expansions in Search, or measuring perplexity in Bayesian Networks). Each corresponding `REPORT.md` details these findings and explicitly mentions design choices.
