# MLX Fine-Tuning Starter (Apple Silicon)

End-to-end LoRA fine-tuning on Apple hardware using **MLX-LM** — no CUDA.
Notebook includes: data prep → training → fuse/quantize → eval/ablation → repro script → freeze bundle.

## Requirements
- Apple Silicon (M-series)
- macOS 14+
- Conda or Python 3.11

## Setup
```bash
conda env create -f environment.yml
conda activate mlxtrain
jupyter lab
