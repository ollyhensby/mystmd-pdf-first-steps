# Mystmd PDF First Steps

## Installation

1. Firstly we need to install the required LateX packages

```bash
sudo apt-get install texlive-latex-recommended texlive-xetex latexmk texlive-science texlive-fonts-extra texlive-bibtex-extra biber
```

2. Create conda environment

```bash
mamba create -n mystmd-dev
conda activate mystmd-dev
```

3. Install nodejs

```bash
mamba install nodejs
```

4. Install mystmd

```bash
npm install -g mystmd
```

## Build

Run

```bash
myst build
```

