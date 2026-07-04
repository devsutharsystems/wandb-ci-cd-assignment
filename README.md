# W&B CI/CD Assignment

This repository contains my implementation of the Weights & Biases CI/CD assignment.

## Project Structure

```
.
├── .github/
│   └── workflows/
│       └── exercise-wandb.yaml
├── client/
│   └── compare_runs.py
├── requirements.txt
└── README.md
```

## Features

- GitHub Actions workflow triggered by PR comments
- W&B API integration
- Automatic baseline run comparison
- Programmatic W&B report generation

## Usage

1. Create a pull request.
2. Comment:

```text
/wandb <run_id>
```

3. GitHub Actions generates a comparison report between the specified run and the baseline run.

## Technologies

- Python
- GitHub Actions
- Weights & Biases (W&B)