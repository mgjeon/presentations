# Environment

- Ubuntu 22.04 
- CUDA 11.8
- Python 3.10
- [Mambaforge](https://github.com/conda-forge/miniforge#mambaforge)

```
mamba env create -f environment.yml 
```

```
mamba activate pinf
```

# Run

`results/run`
```
python 01_run.py --cfg config_run.json
```

`results/output`
```
python 02_output.py --cfg config_run.json
```

`results/eval`
```
python 03_eval.py --cfg config_run.json
```

## Results

- `results/output/plot` -> `Thesis/img`
- `results/eval/img` -> `Thesis/graph`