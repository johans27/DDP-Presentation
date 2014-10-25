Developing Data Products Project
================================
author: Johans
date: octubre 25 2014
transition: rotate

Objective
===

The objective of this presentation is to show all of the users an useful application which was built on shiny and predicts ozone in parts per billion using a dataset from R called "Airquality".

The Prediction Model
===

The predicted value based on two variables: Maximum daily temperature in degrees Fahrenheit (X1) and Average Wind speed in miles per hour (X2). The performed model has the form: Y = a + bX1 + cX2. This is an example of multiple regression.

The coefficients of the model give us the following:




```
(Intercept)        Temp        Wind 
 -71.033218    1.840179   -3.055491 
```

The user will have the ability to enter temperature and wind to get a estimation of ozone in the next link: https://johans27.shinyapps.io/DDProject_Ozone/


Relationship
===

![plot of chunk unnamed-chunk-3](DDProject_Presentation-figure/unnamed-chunk-3-1.png) 

***
As it can be seen, there is a strong relationship between Ozone and the 2 predictor variables. On the one hand, Ozone and Temperatue present a positive relationship. On the other hand, Ozone and Wind show us a negative association.


Using the application
===

- On the left side from the application, enter a value of 65 for Maximum Temperature in Fahrenheit
- Then, put a value of 5 for Average Wind in mph
- Your pediction would result 33.27 Ozone in ppb
- This application will allow you to enter several values to predict ozone
