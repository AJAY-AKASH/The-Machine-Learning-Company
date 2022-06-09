Problem definition :
The principal objective of this project is to assess the general significance of honey bee species arrangement and climate factors in managing wild blueberry agroecosystems in order to predict the yield of blueberry production. In particular, it will try to uncover what honey bee species structure and climate affect the yield and to foresee ideal honey bee species arrangement and climate conditions that accomplish the best yield. The requirement for this project arose as the production of blueberries required unique cross-pollination of bees with a proper environment.

How the data is coming around???
The data is given from Machine Learning company. The dataset can be found in /Dataset folder.

The dataset of 777 records with 18 different features like clonesize(the avg blueberry clone size in the field), honeybee(honeybee density in the field), bumbles(bumblebee density), fruitset(process in which flowers become fruit and potential fruit size is determined), fruitmass, seeds etc.

Yield Prediction Using Machine Learning
First the data is extracted using kaggle dataset. After some EDA and data cleaning and preprocessing, the feature selection is done. Using those features linear regression and XGBoost models are applied.

The code can be found in /Code folder.

The public URL for the code can be found here

State: Fruitmass, Seeds
Action: Fruitset
Agent: Algorithm
Environment: Whole table which is our environment
Rewards: Maximizing the yield performing different actions on states
