# deeplearning-project2

Project 2: Deep Learning — notebooks and supporting files for CS672.

Contents
- Several Jupyter notebooks that implement preprocessing, training, and evaluation.
- `requirements.lock.txt` lists pinned Python deps.
- `project2_cache/` and `tensorboard_logs/` are kept locally and are excluded from the repo.

Quick start
1. Create a virtual environment and install dependencies:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.lock.txt
```

2. Ensure Git LFS is installed and fetch LFS-tracked files (models/datasets):

```powershell
git lfs install
git lfs pull
```

3. Run Jupyter and open the notebooks:

```powershell
jupyter notebook
```

Notes
- Large model files (e.g. `*.npy`, `*.pt`, `*.ckpt`) are tracked with Git LFS; collaborators should run `git lfs install` and `git lfs pull` after cloning.
- Some large CSVs and caches are intentionally excluded from the repository to keep the repo small. If you need the CSVs, copy them into the repo locally or request them separately.

Repository: https://github.com/haggaik/deeplearning-project2
