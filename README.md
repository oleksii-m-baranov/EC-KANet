# EC-KANet
Ensemble Classifier with Kolmogorov-Arnold Layer on a Second Stage

## Install

Tested on Conda 24.7.1

1. Install [Conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html).
2. Prepare Conda environment

```bash
conda env create -n ec-kanet python=3.10
conda activate ec-kanet
pip install tensorflow[and-cuda] matplotlib==3.7.1 numpy
```

or 

```bash
conda env create -n ec-kanet -f environment.yml
```

## Data
All input data are stored in `./resources/input-data/<nn_type>` 

## Run
1. Start jupyter notebook server
2. Open jupyter notebook `ec-kanet.ipynb`
3. Specify target NNs in row
```python
nn_types = ['cct', 'eat', 'fnet', 'conv', 'gmlp', 'mlp_mixer', 'swin_trans']  # specify NNs
```
4. Run all cells

## Reference

## License
