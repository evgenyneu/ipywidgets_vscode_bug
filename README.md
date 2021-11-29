# Demo: Jupyter widget is not working in VSCode

## Install

### Install Python 3.9.5 with [ASDF](https://asdf-vm.com)

```
asdf install
```

### Create Python environment

```
python -m venv .venv
```

Activate environment:

```
 . .venv/bin/activate
 ```


### Install Python libraries

```
pip install -r requirements.txt
```


## How to reproduce the bug


* Run `jupyter-lab` and open [widget.ipynb](widget.ipynb).

* Move the slider, the number is printed out and it is changing as you move the slider.

* Now click on `windet.ipynb` in VSCode and run the notebook there.

* As you move the slider, the number is only printed out once and is not changing.