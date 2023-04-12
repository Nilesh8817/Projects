# Insurance Claim Status Prediction

<p>Insurance companies take risks over customers. Risk management is a very important aspect of the insurance industry. Insurers consider every quantifiable factor to develop profiles of high and low insurance risks. Insurers collect vast amounts of information about policyholders and analyse the data.
As a Data scientist in an insurance company.</p>

This project entails creating a model that can predict for whether a customer can claim for Insurance or not.

## Dataset Description

A file consists of data corresponding to 50552 columns which are 50552 customers and of 12 Features (Columns). Following are the features of the dataset

   - Target: Claim Status (Claim)

   - Gender : 1 - Male, 0 - Female (Gender)

   - Name of agency (Agency)

   - Type of travel insurance agencies (Agency.Type)

   - Distribution channel of travel insurance agencies (Distribution.Channel)

   - Name of the travel insurance products (Product.Name)

   - Duration of travel (Duration)

   - Destination of travel (Destination)

   - Amount of sales of travel insurance policies (Net.Sales)

   - The commission received for travel insurance agency (Commission)

   - Age of insured (Age)

   - The identification record of every observation (ID)

 
Presentation file:<br>

[Travel Insurance claim](Travel_Insurance_Claim.ipynb)

________________________________________________________________________________________________________________________________________________________________

## EDA and Preprocessing

### Null values in %

<img src="Figures/Fig1.png">

<p> Dropped Gender and ID column </p>

## Analyze Categorical columns

<img src="Figures/Fig2.png">
<img src="Figures/Fig3.png">
<img src="Figures/Fig4.png">
<img src="Figures/Fig5.png">
<img src="Figures/Fig6.png">

<p> Dropped Dristribution channel (Highly imbalanced) and Destinations (Too many classes) </p>

## Analyze Numerical columns

<img src="Figures/Fig7.png">
<img src="Figures/Fig8.png">
<img src="Figures/Fig9.png">
<img src="Figures/Fig10.png">

<p> Replaced duration values < 0 with average duration of their respective destination </p>   

## Bivariate Analysis against the traget

   <img src="Figures/Fig11.png">
   <img src="Figures/Fig12.png">
   <img src="Figures/Fig13.png">
   <img src="Figures/Fig14.png">
   
## Baseline model

<p> Decision Tree Classifier</p>
<img src="Figures/Fig15.png">

<p> Random Forest</p>
<img src="Figures/Fig16.png">

## Final Model
<p> Handel Skweness </p>
<p> Standardization using StandardScaler </p>
<p> Since the target is highly imbalanced, used RandomOverSampler </p>

<img src="Figures/Fig17.png">
<img src="Figures/Fig18.png">
<img src="Figures/Fig19.png">
<img src="Figures/Fig20.png">
