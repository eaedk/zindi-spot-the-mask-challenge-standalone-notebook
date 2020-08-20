# zindi-spot-the-mask-challenge-standalone-notebook

Standalone code to show how to participated in this zindi challenge using TF.Keras on Google Colab. [Read more here.](https://zindi.africa/competitions/zindiweekendz-learning-spot-the-mask-challenge/)


## Path update
-   You have to update ` PATH ` ( path place where the challenge repository will be created ) in notebook ` 1-BUILD_REPOSITORY_STRUCTURE.ipynb `.

-   You have to update ` REPO_PATH ` ( path to go to the created repository of mask challenge repository ) in notebooks ` 2-dataset_structuring.ipynb ` and ` 4-keras_starter-spot_the_mask.ipynb `.


## Instructions to RUN 

### 1- Instruction about folder structure
-    Run the notebook ` 1-BUILD_REPOSITORY_STRUCTURE.ipynb ` to create the challenge repository and its sub-folders.

-   Move all notebooks in the created challenge repository to its sub-folder ` NOTEBOOKS `.


### 2- Instruction about the dataset

-   Download challenge dataset on [ZINDI web site](https://zindi.africa/competitions/zindiweekendz-learning-spot-the-mask-challenge/data) and put each file in corresponding sub-folder of the ` DATASET ` folder in regard of file type.


### 3- Instruction about dataset structuring
- Run the notebook ` 2-dataset_structuring.ipynb ` to unzip and process the dataset.

### 4- Instruction about starter notebook
- Run the notebook ` 4-keras_starter-spot_the_mask.ipynb ` to create your first submission file ( which will be saved in the challenge repository to its sub-folder ` SUBMISSIONS ` ) and make your first submit on [ZINDI](https://zindi.africa/competitions/zindiweekendz-learning-spot-the-mask-challenge/submit). After that, play around model architecture, augmentation parameters of ImageDataGenerator and any other tips you want to improve in ranking on the [leaderboard](https://zindi.africa/competitions/zindiweekendz-learning-spot-the-mask-challenge/leaderboard).
