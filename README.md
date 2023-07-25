
![Logo](https://s3b.cashify.in/blog/wp-content/uploads/2018/05/mobile-phone-evolution.jpg)


# Mobile Price Range Prediction

In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is.

## Problem Statement

The goal of this problem is not to predict the actual price of a mobile phone, but rather to determine a price range that indicates how high the price could be. With your help, one can gain a better understanding of the market and set competitive prices for his products.
## Dataset

Battery_power - Total energy a battery can store in one time measured in mAh

Blue - Has bluetooth or not

Clock_speed - speed at which microprocessor executes instructions

Dual_sim - Has dual sim support or not

Fc - Front Camera mega pixels

Four_g - Has 4G or not

Int_memory - Internal Memory in Gigabytes

M_dep - Mobile Depth in cm

Mobile_wt - Weight of mobile phone

N_cores - Number of cores of processor

Pc - Primary Camera mega pixels

Px_height - Pixel Resolution Height

Px_width - Pixel Resolution Width

Ram - Random Access Memory in Mega

Touch_screen - Has touch screen or not

Wifi - Has wifi or not

Sc_h - Screen Height of mobile in cm

Sc_w - Screen Width of mobile in cm

Talk_time - longest time that a single battery charge will last when you are

Three_g - Has 3G or not

Wifi - Has wifi or not

Price_range - This is the target variable with value of 0(low cost), 1(medium cost)
## Requirements

To run this project, you will need to have the following packages installed:

    1. Python - Programming Language
    2. Numpy - Scientific computing library
    3. Pandas - Data manipulation library
    4. Matplotlib - Data visualization library
    5. Seaborn - Data visualization library
    6. Sklearn - Statistical modelling library
    7. XGBoost - Regression and Classification on large datasets library

    
## Conclusion


*   There are total number of four types of price range in mobile phones and all elements are almost same.
*   Half of the mobile phone categories has bluetooth and half dont.

*   As the battery power increases the price of the mobile also increases gradually.

*   Ram has continuous increase with price range while moving from Low cost to Very high cost

*   RAM, battery power, pixels played more significant role in deciding the price range of mobile phone.
*   When the cost of the phone is high the price of the mobile phone is also high.



*   In ML the most inaccurate model we have seen is KNN which gave an accuracy of 57%


*   Both decision tree and random forest gave almost same accuracy of 82% and 88%.

*   XG-Boost gave us the most accurate result in terms of accuracy of 98% and this model ca be used for price range analysis.