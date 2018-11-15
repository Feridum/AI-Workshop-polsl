# AI Workshop Politechnika Śląska

To repozytorium zawiera materiały użyte podczas części praktycznej warsztatów z wykorzystania AI i wizji komputerowej, a szczególnie w medycynie.  
  
## Zawartość repozytorium

* materials - obrazy wykorzystane do wizualizacji
* models - zapisane modele Keras umożliwiające wykorzystanie materiałów bez treningu SN
* notebooks:
    * ...-instrukcje.ipynb - notebooki z lukami do wypełnienia przez uczestników warsztatów
    * pozostałe - pełne notebooki bez luk, wraz z wynikami
* requirements.txt - plik tekstowy z wymaganymi biblitekami

## Wymagania

* Anaconda/miniconda

## Dane

[CelebA - informacje](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)  
[CelebA - pobieranie](https://drive.google.com/file/d/0B7EVK8r0v71pZjFTYXZWM3FlRnM/view?usp=sharing)

## Tworzenie środowiska do wywołania kodu poza colfax cluster

```bash
conda update conda
conda create -n aipolsl python=3.6
pip install -r requirements.txt
```

Teraz aktywację środowiska można przeprowadzić poprzez:
* `activate aipolsl` (windows)
* `source activate aipolsl` (linux/git bash)
