# Dataset for "DEFT: Dexterous Fine-Tuning for Real-World Hand Policies"

This repository contains instructions to download the pre-processed data (from Ego4D, EK-100, and HOI4D datasets) used for the grasp affordance model training in "DEFT: Dexterous Fine-Tuning for Real-World Hand Policies." This data is modified from [Ego4D](https://ego4d-data.org/), [Epic-Kitchens](https://epic-kitchens.github.io/), and [HOI4D](https://hoi4d.github.io/) and pre-processed with the labels necessary for training.

# Instructions

Download data from [here](https://drive.google.com/drive/folders/1E8RqVa8RDRlNJGX0FDt5aWV48ndo-XFJ?usp=sharing)). 

Alternatively, download directly to disk using `gdown`:

```
pip install gdown
gdown --folder 1E8RqVa8RDRlNJGX0FDt5aWV48ndo-XFJ
```

Unzip all data:

```
tar -xf deft-data-all/*.tar.gz -C deft-data-all
rm deft-data-all/*.tar.gz
```

# Attribution

This data is modified from the [Ego4D](https://ego4d-data.org/), [Epic-Kitchens 100](https://epic-kitchens.github.io/), and [HOI4D](https://hoi4d.github.io/) datasets. We used a subset of the images from the videos recorded those datasets, detected the affordances, and provided labels for model training. Both Epic Kitchena and HOI4D are licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/), and Ego4D's license is [here](https://ego4d-data.org/pdfs/Ego4D-Licenses-Draft.pdf).

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
