# Predicting Meal Vegetarianism Using Convolutional Neural Networks

This repository contains three different approaches of identifying vegetarian ingredients in an image these can be found in three .ipynb files:
* binary_classifier.ipynb: binary classifier to predict vegetarianism directly
* multi_class_classifier.ipynb: multi class classifier to predict vegetarianism based on category in the Food101 dataset
* multilabel_classifier.ipynb: multi-label classifier to predict vegetarianism based on 

## Usage

* Download and unpack the two datasets under the datasets section 
* Run the ingredient_labeling notebook
* Run the dataset_generation notebook

## Datasets

The datasets Ingredients101 and Recipes5k were used to create and evaluate the models:
* [Ingredients 101](http://www.ub.edu/cvub/ingredients101/)
* [Recipes5k](http://www.ub.edu/cvub/recipes5k/)

## Citation

The following paper was used as reference to create the models:

```
Bolaños, Marc, Aina Ferrà, and Petia Radeva. 
"Food Ingredients Recognition through Multi-label Learning." 
In Proceedings of the 3rd International Workshop on Multimedia Assisted Dietary Management (ICIAPW) arXiv preprint arXiv:1707.08816 (2017).
```

