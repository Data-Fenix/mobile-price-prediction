# Mobile Price Prediction using Machine Learning
[<img target="_blank" src="https://github.com/Data-Fenix/mobile-price-prediction/blob/main/Images/mobile%20price.png">](https://github.com/Data-Fenix/mobile-price-prediction/blob/main/Images/mobile%20price.png)

## Table of Content

  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Technical Aspects](#technical-aspects)
  * [Installation](#installation)
  * [Run](#run)
  * [Results](#results)
  * [Directory Tree](#directory-tree)
  * [To Do](#to-do)
  * [Bug/Feature Requests](#bug/feature-requests)
  * [Technologies Used](#technologies-used)
  * [Contributing](#contributing)
  * [License](#license)
  * [Credits](#credits)

## Overview

In this project we are trying to predict the price of the mobile based on their features and the brand. We used a web-scraped dataset for this analysis and we applied many preprocessing techniques to preprocess this dataset. The dependent variable of this model is price and it’s continuous data. Therefore we used regression techniques to get the prediction and trained linear regression, elastic net regression, extra tree regressor, random forest regression and support vector regression models respectively. After that evaluated all the models and optimized the best model using random search cv and grid search cv methods. Finally, we saved the final model as a pickle file for future predictions. Let’s see how it’s done.

## Dataset

##### Independent Features
* Unnamed: 0 - Index column and this is an unnecessary column
* Brand me — Brand of the mobile phone and the model.
* Ratings — Consumer rating for the mobile phone
* RAM — RAM size of the mobile
* ROM — ROM (Internal Memory) size of the mobile
* Mobile_Size — Size of the mobile in inches
* Primary_Cam — Pixel size of the back camera
* Selfi_Cam — Pixel size of the front/selfi camera
* Battery_Power — Battery capacity of the mobilr in mAh

##### Dependent Features
* Price — Price of the mobile

## Motivation

I’m working under telecommunications industry and sometimes industry also sell some mobile phones as an agent. They always deal with the new products and their price changes differently. Therefore, they need to check whether this product is worth for this price or not. According to this requirement they need to build a model to predict the price of the mobile by providing some features to the model. So as a ML engineer I need to solve this issue.
Apart from that we all are using mobile phones and I also need to know the **price of a mobile before they are available in the shops**. So that we are able buy the best and the dream product according to our budget.

## Technical Aspects

1) Perform an EDA using Auto EDA library
2) Preprocessed the dataset using following techniques:
3) Fitted the models using below techniques
4) Checked the model performances and checked the overfitting issues as well
5) Optimized the best model using random search cv and gird search cv methods
6) Save the best performed model into a pickle file.
7) Compressed the final model as pkl version of the model, the file is almost 35 mb and GitHub does not allow that file size (max limit is 25mb).

## Installation

#### Requirements

1. Jupyter Enviornment
2. Python 3.5+
    
## Run
Clone this repository into your local machine and execute the mobile_price_prediction.ipynb
To Do
1) Need to deploy this job in AWS as a training pipeline.
2) Need to develop an AWS inference pipeline after deploying the training pipeline in AWS.

Don’t worry we will discuss these topics in the future and give you the complete guidance. Stay with us and follow us:


## Results
These are some interesting results.

Please click on this document. https://github.com/Data-Fenix/mobile-price-prediction/blob/main/Interesting%20findings%20from%20EDA.docx

## Directory Tree

```
├── data 
|     └── data.csv
├── EDA_report.html
├── README.md
├── mobile_price_prediction.html
├── mobile_price_prediction.ipynb
├── model.tar.gz
└── model_compress_code.ipynb
```

## To Do

Need to deploy this model in AWS platform.

Don't worry, we will discss above topics and many more in the future.

## Bug/Feature Requests
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/Data-Fenix/mobile-price-prediction/issues/new) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/Data-Fenix/mobile-price-prediction/issues/new). Please include sample queries and their corresponding results.

## Technologies Used
[<img target="_blank" src="https://venturebeat.com/wp-content/uploads/2021/02/SageMaker.jpg?fit=1292%2C664&strip=all" width=200>](https://venturebeat.com/wp-content/uploads/2021/02/SageMaker.jpg?fit=1292%2C664&strip=all)[<img target="_blank" src="https://logos-world.net/wp-content/uploads/2021/10/Python-Symbol.png" width = 200>](https://logos-world.net/wp-content/uploads/2021/10/Python-Symbol.png)

## Contributing

<p><b> ML Enginner </b> : Lahiru Dissanayake </p>
<p><b> Data Scientist </b>: Shashi Withanage </p>

## License

Copyright 2022 Lahiru Dissanayake and Shashi Withange

## Credits

1) https://medium.com/@Nivitus./mobile-price-prediction-using-machine-learning-fa9cab6fb242



