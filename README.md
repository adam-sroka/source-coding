# Source Coding

This repository contains the source code, data and evaluation of i.i.d., contextual and adaptive source coding techniques.

## Structure

The modules containing the implementations of the algorithms are in the main directory of the repository, these are the files:
- `adarith.py`
- `arithmetic.py`
- `camzip.py`
- `camunzip.py`
- `conarith.py`
- `trees.py`
- `vl_codes.py`

The raw and compressed data is in the `data` directory. Files used are the `hamlet.txt` file and multiple others from the [The Canterbury Corpus](https://corpus.canterbury.ac.nz/) 

Demonstration jupyter notebooks are in the main directory and are suffixed by `demo.ipynb`, these are:
- `ftr_handout_demo.ipynb` — the modified FTR handout
- `iid_coding_demo.ipynb` — demonstration of iid coding techniques
- `contextual_coding_demo.ipynb` — demonstration of contextual techniques

## Acknowledgements

Majority of the source code comes from modified implementations of code from [Sayir, 2018](http://www2.eng.cam.ac.uk/~js851/) and [Jones, 2018](https://ifthehuefits.github.io/about/).
