# data-augmentation-demo

- Tutorial on _image_ augmentations for computer vision
- Tutorial on _image and text_ augmentations for ML

## Overview

Both tutorial notebooks use the [`albumentations`](https://albumentations.ai/)
package to do standard geometric, colorspace, kernel filter, and
random erasing (Cutout) transformations. Gives examples of image mixing
(Mixup and CutMix) augmentations, and combining multiple imate augmentations together.

The image-specific notebook, `img-augmentation-demo.ipynb`, concludes with examples of
techniques applied by top teams in the Kaggle [Recursion Cellular Image
Classification](https://www.kaggle.com/c/recursion-cellular-image-classification/)
Machine Learning competition.

The second tutorial notebook,`img-text-augmentation-demo.ipynb`, includes most of the former context on image augmentations, but also dives in text augmentations using the `nlpaug` package.

## Setup

To try out the notebooks, you can create a working `conda` enviroment from the provided environment file, and then activate it, and launch jupyter notebook:

```sh
$ conda create env -f environment.yml
$ conda activate augment
(augment) $ jupyter notebook
```

The notebook is intended to be rendered as slides using the RISE extension, which can be configured in the Jupyter Notebook Extensions UI.

## Presentations

This talk was originally created for a presention to the SLC Python Meetup on June 3, 2020.

A more concise version of the talk was presented at PluralsightLIVE 2020, and can be accessed on the [pslive-version](https://github.com/jesford/image-augmentation-demo/tree/pslive-version) branch.

The image and text augmentations tutorial was presented at the Women in Data Science Conference,  Salt Lake City chapter, in April 2022.
