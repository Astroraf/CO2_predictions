# CO2_predictions 

## A Time Series Study Using Weekly CO2 Measurements
Authors: [Jiji Craynock](https://github.com/DataOnATangent) & [Rafael Ferreira](https://github.com/Astroraf)

<p align="center">
<img src="https://visme.co/blog/wp-content/uploads/climate-change-facts-header-wide.gif"> 
</p>


## <span style="color: deepskyblue;">Overview </span>
By now most of us realize that rising CO2 levels are a problem. Scientist warn that if we do not manage to maintain C02 levels below 450 ppm we will be unable to stabilizing the average global temperature at a 2°C increase over the pre-industrial period. Sceintist have declared that 2°C of global warming would have disastrous consequences and could cause major dislocations for civilization. For our project we use weekly CO2 measurement data from NOOA to predict future CO2 levels. We used <span style="color: tomato;"> THE MODEL WE CHOSE to predict that by over the course of TIME PREDICTED FOR CO2 level will rise to AMOUNT IT WILL RISE TO. This should impress upon everyone the importance to taking our conservation seriously and increasing our efforts to stop and ideally reverse global warming. </span>

[Source](https://sustainabilityadvantage.com/2014/01/07/co2-why-450-ppm-is-dangerous-and-350-ppm-is-safe/) 

<p align="center">
  <img width="560" height="400" src="http://nerdist.com/wp-content/uploads/2014/11/NASA-CO2.gif">
</p>


## Approach

### Data and model Preparation in 4 steps:

1. **Cleaning and Preprocessing:** Handled all missing information, dropped unneeded/unusable columns, simplified categorical features by grouping similar groups together and removing attitudes from responses. The notebook containing this process with explanations on how each feature was treated can be found in the data_exploration folder. 

2. **Exploratory Data Analysis:** Features were manipulated and used to create a myriad of visuals in order to better understand the distribution of the observations and possible relationships.

3. **Modeling:** Tested several classification models to find the best option for the dataset.  

3. **Evaluation:** Evaluated the models tested for best result and made determinations about findings.  

### Models tested:

* ARMA
* ARIMA
* SARIMAX

## Findings

TBD  

<p align="center"><img width="400" height="300" src="/images/Corr.png" alt="correlation_chart"></p>





## Conclusion

TBD

## Next Steps

TBD

## Repository Structure
    
    ├── data_exploration                  Preproccessing & EDA Notebooks, and Relevant Data 
    ├── final_notebook                    Final notebook containing final model
    ├── images                            Images
    ├── README.md                         ReadMe
    └── presentation_deck                 Contains the presentation deck associated with this project