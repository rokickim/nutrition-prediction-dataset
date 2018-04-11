# Nutrition Prediction Dataset
This dataset is based on a web crawl of the online platform Allrecipes.com. The crawling of the platform was performed between 20 th and 24 th of July, 2015. focus in our work only on recipes published in the main dish category, containing valid, peer-reviewed nutritional information. Further, we require recipe images, information on preparation duration, as well as user feedback to be available, which is the case for 9,766 recipes.

The dataset consists of two parts:
* A Regression dataset (regression_data.csv): In addition to nutritional information, for each of the recipes we derived 547 features for modelling the five information cues ‘Image’, ‘Title’, ‘Ingredients’, ‘Directions’, ‘User Feedback’.

* A crowdsourcing dataset (study_data.csv): In addition we performed a crowdsourcing study to observe how (well) humans estimate healthiness and nutrition of online recipes. Workers were shown complete online recipes and were asked to estimate calories, as well as the macro-nutrients covered by the FSA front-of-package labeling system: fat, saturated fat, sugar and salt.

If you use this dataset in your research, please cite:
Markus Rokicki, Christoph Trattner, and Eelco Herder. "The Impact of Recipe Features, Social Cues and Demographics on Estimating the Healthiness of Online Recipes." ICWSM. 2018.

## License
This project is licensed under the CC-BY-4.0 License - see the LICENSE file for details.



