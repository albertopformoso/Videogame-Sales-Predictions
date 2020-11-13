___
<img src="https://www.up.edu.mx/manualgrafico/HRfiles/imagen/escudo_CH001.jpg" width="300"/>

# Videogames Sales Predictions

<center><img src="https://i.pinimg.com/originals/58/d0/f4/58d0f4ffd1e023fc27c37c99ac77dc3b.gif" width="300"/></center>

### Team:
|Names|
|---|
|Alberto Piñón Formoso|
|Juan Pablo Zerón del Valle|
|Oscar Zuñiga Gutierrez|
|Samir Alejandro Ruiz Mafud|

### Project description
This project presents an analysis on a dataset that shows the annual sales of video games around the world, in order to create a prediction model. In it we can also find information about the name of the video game, platform, year, gender, and many others, which allows us to carry out a deeper analysis.

On the first section, *Exploratory Analysis*, as the name says an exploratory analysis of the information detailed of the dataset is made such as sales per platform and genre, top genres, global sales vs released games and much more.

On the second section, data cleaning and preprocessing was made before modeling regressors.

And in the third part *Supervised ML Modeling* 3 Linear regressors from the sklearn package were used, LinearRegressor, DecisionTreeRegressor, and SVR (Support Vector Regressor).

### Objective
The objective is to create a prediction model of the annual global sales of video games, through the use of machine learning tools. For this, it will be necessary to make a comparison between different regressor models in order to obtain the most accurate one.

### Description of the variables
|Rank|Ranking of overall sales|
|---|---|
|Name|The games name|
|Platform|Platform of the games release (i.e. PC, PS4, etc.)|
|Year|Year of the game's release|
|Genre|Genre of the game|
|Publisher|Publisher of the game|
|NA_Sales|Sales in North America (in millions)|
|EU_Sales|Sales in Europe (in millions)|
|JP_Sales|Sales in Japan (in millions)|
|Other_sales|Sales in the rest of the world (in millions)|
|**Global_Sales**|Total worldwide sales|

<br> The objective variable to predict is the *Global_Sales* column. </br>
