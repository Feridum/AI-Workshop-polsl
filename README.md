# AI Workshop polsl

# Wymagania

* Anaconda/miniconda

## Dane

[CelebA](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)
[Pobieranie](https://drive.google.com/file/d/0B7EVK8r0v71pZjFTYXZWM3FlRnM/view?usp=sharing)

## Tworzenie środowiska ze zoptymalizowaną dystrybucją Pythona 3

```bash
conda update conda
conda create -n aipolsl python=3.6
```
Nie będzie to konieczne w wypadku korzystania z klastra Colfax/AI DevCloud.

W przypadku chęci skorzystania z w domu z powyższych implementacji wystarczy wpisać poniższe polecenie do wiersza poleceń:
`conda create -n aipolsl --file conda_env.txt`

Wszystkie wykorzystywane biblioteki są również zapisane w pliku `requirements.txt`.
Można je zainstalować w dowolnej dystrybucji pythona poprzez polecenie: `pip install -r requirements.txt`.

Teraz aktywację środowiska można przeprowadzić poprzez:
* `activate aipolsl` (windows)
* `source activate aipolsl` (linux/git bash)