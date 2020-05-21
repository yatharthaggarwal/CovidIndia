# Covid19 India

The following scripts shows India specific spread of Covid19 and how different states are handling the outbreak. All these scripts have been made with Python on Jupyter Notebook.

### 1. Choropleth Map of ROG Districts in India.ipynb

This script creates a choropleth map of India with its districts divided into Red, Green and Orange zones. 
The map has been made interactive, that means when someone hovers over the district, total number of Confirmed, Active, Recovered and 
Deceased cases pops up. The script uses:
#### India_Districts Folder and Zones in India.csv file

### 2. States_ADR.ipynb

This script plots stacked bar for multile states with their Active, Death and Recovered (ADR) cases over all this time. One could see how each state is tackling this Coronavirus outbreak and which states are flattening the curve.

### 3. States_ConfirmCases_&_MovingAverage.ipynb

This script plots for multiple states, showing their daily confirmed cases and their behaviour based on a smoothening curve of 5-day moving average.

### 4. States_Positivity_Test_Rate.ipynb

This script also plots for multiple states, showing the test positivity percent for all this time. To calculate the ratio we have taken cumulative values. The positivity percent for any day is calculated as: <br>
Positivity percent = (total positive/ total tests conducted) x 100

### 5. States_Tests_perMillion.ipynb

This script plots horizontal lines graph for multiple states showing their Tests per Million(TPM) data. The graph also shows 3 markers for last day and last 5th, 10th day TPM data. The script uses
#### India States Population.csv file
