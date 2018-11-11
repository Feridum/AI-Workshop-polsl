# AI Workshop polsl

# Wymagania

* Anaconda/miniconda

## Dane

[CelebA](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)
[Pobieranie](https://drive.google.com/file/d/0B7EVK8r0v71pZjFTYXZWM3FlRnM/view?usp=sharing)

## Tworzenie środowiska do wywołania kodu poza colfax cluster

```bash
conda update conda
conda create -n aipolsl python=3.6
pip install -r requirements.txt
```

Teraz aktywację środowiska można przeprowadzić poprzez:
* `activate aipolsl` (windows)
* `source activate aipolsl` (linux/git bash)