# Bachelor Thesis (학사졸업논문)

- Title (제목)
    - Reconstruction of Coronal Magnetic Fields Using Physics-Informed Neural Networks
- Supervisor (지도교수)
    - Yong-Jae Moon (문용재)
- Author (저자)
    - Mingyu Jeon (전민규)
- Affiliation (소속)
    - Department of Astronomy and Space Science, Kyung Hee University, Yongin, Korea (경희대학교 우주과학과)
- Research period (연구기간)
    - 2023/02 - 2023/06

# Resources

- NF2 code
    - https://github.com/RobertJaro/NF2
- Thesis Template
    - https://www.overleaf.com/latex/templates/bachelors-thesis-template/pwyzpzxfhkpt

# Code

## Environment

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

## Run

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

## Result

- `results/output/plot` -> `Thesis/img`
- `results/eval/img` -> `Thesis/graph`

# Thesis, Presentation

## Environment

- Ubuntu 22.04 
- [texlive](https://packages.ubuntu.com/jammy/texlive-full)
    ```
    sudo apt install texlive-full
    ```
- [VS Code](https://code.visualstudio.com) + [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)

## Build

- Build `Thesis/main.tex` -> `Thesis.pdf`
- Build `Presentation/TeX/main.tex` -> `Presentation/20230602_LabMeeting_MingyuJeon.pdf`

## Compress PDF
- [PDF24 Tools](https://www.pdf24.org)