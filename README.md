# 🧬 Protein Subcellular Localization Prediction

This repository contains a deep learning project designed to predict protein subcellular localization using neural networks (Dense Model, CNN, ResNet). The models are trained on protein sequences to classify them into 10 possible localization categories. Subcellular localization refers to the specific location or environment within a cell where a protein resides. Correctly identifying this is essential for understanding the protein's function and role in biological processes. 

## 🔄Installation

### Clone the repository

```bash
git clone git@github.com:zhukovanadezhda/subcellular-localization.git
cd subcellular-localization
```
### Setup the conda environment

Install [miniconda](https://docs.conda.io/en/latest/miniconda.html). Create the `deep-learning` conda environment:

```bash
conda env create -f environment.yml
```

### Load the environment

```bash
conda activate deep-learning
```

> 💡**Note:** To deactivate an active environment, use:
> ```bash
> conda deactivate
> ```


## 📄 References

Almagro Armenteros, J. J., Sønderby, C. K., Sønderby, S. K., Nielsen, H., & Winther, O. (2017). DeepLoc: prediction of protein subcellular localization using deep learning. *Bioinformatics (Oxford, England)*, 33(21), 3387–3395. https://doi.org/10.1093/bioinformatics/btx431
