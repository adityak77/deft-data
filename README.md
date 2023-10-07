# Dataset for "DEFT: Dexterous Fine-Tuning for Real-World Hand Policies"

This repository contains instructions to download the pre-processed data (from EK-100 and HOI4D datasets) used for the grasp affordance model training in "DEFT: Dexterous Fine-Tuning for Real-World Hand Policies." This data is modified from [Epic-Kitchens](https://epic-kitchens.github.io/) and [HOI4D](https://hoi4d.github.io/) and pre-processed with the labels necessary for training.

# Instructions

Download data from [here](https://drive.google.com/drive/folders/1bm7RVFpEZ7sELH56crHhQThkrgjMn0wo?usp=sharing). 

Alternatively, download directly to disk using `gdown`:

```
pip install gdown
gdown --folder 1bm7RVFpEZ7sELH56crHhQThkrgjMn0wo
```

Unzip all data:

```
tar -xf deft-data/*.tar.gz -C deft-data
rm deft-data/*.tar.gz
```

# Attribution

This data is modified from the [Epic-Kitchens 100](https://epic-kitchens.github.io/) and [HOI4D](https://hoi4d.github.io/) datasets. We used a subset of the images from the videos recorded those datasets, detected the affordances, and provided labels for model training. Both datasets are licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).

# License

This dataset is licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).

# BibTeX

When using this dataset, please reference:

```
@article{kannan2023deft,
         title={DEFT: Dexterous Fine-Tuning for Real-World Hand Policies},
         author={Kannan, Aditya, and Shaw, Kenneth and Bahl, Shikhar, and Mannam, Pragna and Pathak, Deepak},
         journal={Conference on Robot Learning (CoRL)},
         year={2023}}
```
