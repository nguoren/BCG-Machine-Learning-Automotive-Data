# Machine Learning Automotive Data

<p align="center"><img src="https://i.imgur.com/MCpInIE.jpg"></p>

## Project Introduction
- Use Linear Regression to predict the price of automotives
- LINK: https://github.com/nguoren/BCG-Machine-Learning-Automotive-Price-Prediction/blob/main/DigitalBCG%20Academy%20-%20Machine%20Learning%20-%20Linear%20Regression%20-%20Automotive%20Price%20Prediction.ipynb

## Introduction to Automotive Data Set
- DataFrame consists of 205 rows and 26 columns
- There are 10 categorical variables and 16 numerical variables
- There are 21 different makes of automotives in the dataset
- Automotives can be fueled by either gas or diesel
- Aspiration of an automotive is either standard or turbo
- There are two and four doors automotives
- Body style of an automotive can be sedan, hatchback, wagon, hardtop or convertible
- There are front-wheel-drive (fwd), 4-wheel-drive (4wd) and rear-wheel-drive (rwd)
- Engine location can be front or back
- There are ohc, ohcf, ohcv, l and dohc engine types
- There can be 3, 4, 5, 6, 8 or 12 number of cylinders
- There are 7 types of fuel systems

## Insights Gathered
1. Mean of diesel automotives are pricier than gas
2. Mean of turbo automotives are pricier than standard
3. Mean of four doors automotives are pricier than two doors
4. Mean of hardtop and convertible are the priciest while hatchback has the lowest mean price
5. Mean of rear-wheel-drive is pricier than front-wheel and 4-wheel
6. Mean of ohcv engine type is the priciest
7. Mean of eight and twelve number of cylinders are the priciest
8. Mean of mpfi, mfi and spfi fuel system are the priciest

## Linear Regression Model
- Features selected: <br>
  i) fuel_type <br>
  ii) aspiration <br>
  iii) body_style <br>
  iv) drive_wheels <br>
  v) engine_type <br>
  vi) num_of_cylinders <br>
  vii) fuel_system <br>
  viii) curb_weight <br>
  ix) engine_size <br>
  j) highway_mpg <br>

- Model Evaluation: <br>
  - Mean Square Error      = 0.033569793443127736
  - Root Mean Square Error = 0.18322061413260174
  - Mean Absolute Error    = 0.14102940838438013
  - Median Absolute Error  = 0.10950882890471547
  - R^2                    = 0.8382910829815796
  - Adjusted R^2           = 0.7135442041387982
  - ROC_AUC                = 0.9478458049886622
