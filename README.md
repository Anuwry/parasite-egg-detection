# Parasite Egg Detection and Classification

YOLO-based parasite-image prediction with confidence and bounding-box size postprocessing.

## Project context

Super AI Engineering Season 6, 2026. Individual competition project.

## Approach

YOLO detection experiments with confidence and bounding-box area filtering for parasite-type or no-parasite predictions.

## Competition result

Competition **F1 score: 0.21511**. The averaging convention is not asserted.

Leaderboard results are from the project author's competition records, not newly generated benchmark results.

## Source files

- notebooks/parasite_yolo_experiments.ipynb

## Setup and use

1. Create a Python environment compatible with the historical notebook and selected model.
2. Install relevant dependencies from requirements.txt. GPU frameworks and Unsloth may require platform-specific CUDA instructions.
3. Provide authorized images, labels and competition directory layout. Dataset images and model weights are excluded.
4. Start JupyterLab and run the selected notebook in order. Review experiment branches before a full training run.

    python -m venv .venv
    python -m pip install -r requirements.txt
    python -m jupyterlab

## Archive preparation

- Notebook outputs and execution metadata were cleared.
- Hardcoded credentials found in selected source were replaced with environment lookups.
- Datasets, personal records, submissions, model weights and local environments are excluded.
- Source was statically checked; training and external API calls were not rerun.

## Limitations

Several experimental branches are retained. YOLOv8m training is present; no saved checkpoint is claimed as the verified final submission. Competition research, not a clinically validated diagnostic system.
