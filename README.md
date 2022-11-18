
![image1](./images/Kings1.jpg)

# Pump-it-Up-Data-Mining-the-Water-Table

**Authors**: Jonathan McCaffrey, Ziyuan Wang, Stefano Caruso

## Overview

For this project we are going to analyze by using data from Taarifa and the Tanzanian Ministry of Water. This dataset contained a huge amount of information about different features for water well with different condition(Functional, Functional needs to be repaired, non-functional).We set our stakeholders as Government of Tanzania looking to find patterns in non-functional wells to influence how new wells are built. Our job would be identify and predict which pumps are functional, and which don't work at all. First, we looked at dataset and figure out what type of information we would obtain from each column. Then we identified features that seemed to be more reasonable to affect the well condition. We got rid of those columns that not usaful in our analysis and did some cleaning for the data we had and got ready for modeling. Then it's about modeling: We built some baseline models with default hyperparameters on different classifier. Then we tried different hyperparameters to get the best model with best data accurancy, recall, f1 score, which means have a better chance to identify if the well would be functional or non-functional in the future.

Accuracy for our final model 21% higher than Baseline dummy model.The percentage of correct prediction for both functional and non-functional were both descent. GPS height, Age and dry water quantity are the most important features to cause a well to be non-functional.


## Business Problem

Tanzania, as a developing country, struggles with providing clean water to its population of over 57,000,000. There are many water points already established in the country, but some are in need of repair while others have failed altogether. Our target was to provide Tanzanian Ministry of Water, some local water companies and Tanzania govenment an accurate classifier to predict if the water well would be functional or non-functional. Another target would be let them know the most possible reason that would cause a water well to be non-functional. By implementing our model, there would a higher chance that each water point could run successfully and save more money for well construction and future repairment.


## Data

Three Datasets in total.
Testing and training data are both with 40 columns which would be used in this Analysis. 
The third dataset would be about the condition for each well.



## Methods

We drop columns that will not likely to affect the well condition. And start to build models and keep refining models until the model shouws good recall snd score.

## Results
![graph1](./images/Result1.jpg)

Clear linear relationship between Price and Living area.


![graph2](./images/Result2.jpg)

Average grade is our baseline grade. Higher grade is associated with higher sale price. 

![graph3](./images/Result3.png)

Average condition is our baseline grade. Higher condition is associated with higher sale price.

## Limitation

For limitation part, there are three major limitations for this project. First is about the time, it just took forever to run some of the model. Secondly, it’s about the incomplete data, there were bunch of null values throughout the entire dataset, and we drop columns with Hugh number of nulls. Finally, according to our research, there are some other features could affect a well more for example the well depth or well maintenance, which not included in dataset.

## Conclusions

For the conclusion, clean water had become one of the biggest problems in Tanzania, and it’s really necessary to build efficient water points for all type of purposes. Our final model will provide an accurate classifier to predict if the water well would be functional or non-functional. Also find out the most possible reason that would cause a water well to be non-functional. By implementing our model with professional water institution, there would a higher chance that each water point could run without any issues and save more money for well construction or future repairment and maintenance.

## Next steps

For our next steps, we will try to contact other local water department for more well information and then refine our data. Also we want to contact more foundations like non government organization or maybe International Water Management Institute and show them what we can do with our model. And find a way together to help more African people.


## For More Information

Please review our full analysis in [our Jupyter Notebook](./Pump-it-Up-Data-Mining-the-Water-Table_Final_Notebook.ipynb) or our [presentation](./Pump-it-Up-Data-Mining-the-Water-Table_Presentation).

For any additional questions, please contact **Ziyuan Wang & zywang1994@gmail.com, Jonathan McCaffrey & jonmcjon@hotmail.com, Stefano Caruso & dog112618@gmail.com**

## Repository Structure

```
├── README.md                                                     <- The top-level README for reviewers of this project
├── Pump-it-Up-Data-Mining-the-Water-Table_Final_Notebook.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── Pump-it-Up-Data-Mining-the-Water-Table_Presentation.pdf       <- PDF version of project presentation
└── images                                                        <- images folder used for project
└── data                                                          <- data folder used for this project
```
