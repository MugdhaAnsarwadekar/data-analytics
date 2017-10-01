# data-analytics </br>
This project is based on crime related dataset in USA. This dataset is our primary
dataset. It has multiple parameters associated with crime which help us better determine the
crime rate. Also the dataset is spread over many years and has information for every state
and city in the USA. The other secondary sources of dataset that were used along with this
primary dataset include education based dataset and motor insurance dataset. These
secondary sources helped us do a better forecast and prediction related to primary data.
Education related dataset along with primary dataset is used in visualization of variation in
crime rate according to education rate for different levels of education in various states. </br>

Link for the project:
https://public.tableau.com/shared/3C5Q9Y54S?:display_count=yes </br>
</br>
### 1. Crime rate in USA </br>
This model shows the variation of crime rate across all states in USA.Dark colored
states indicate higher crime rate and light colored state indicate lower crime rate. You can
hover over every state to check the percentage of crime in that state. </br>
### 2. Correlation between crime types</br>
This model uses a calculated field “Correlation” for determining the correlation
between various crime types. It provides visualization of actual crime rates across all states
in USA and correlation between these crime types. The correlation between crime types
gives better understanding about how different crimes are related and will help in taking
preventive measures for a particular crime if another crime with high correlation is reported
in the area.</br>
Selection of variables:</br>
Select two crime types of interest from the dropdown menu on right hand side and
the graph displays the correlation between these two crimes across all states in USA.</br>
### 3.1 Relation between normalized crime rate and education</br>
This model helps in visualizing the relation between number of criminal incidences
normalized with respect to population and level of education across all states which are
grouped as per region in USA. This information is helpful in understanding how education is
affecting the crime rate in a state.</br>
Selection of variables:</br>
This visualization can be filtered to view the relation between crime and education by
region and states by selecting state/region of interest from the top left filter option for the
same.</br>
### 3.2 Clustering of states based on motor theft incidences and motor insurance value</br>
This model displays the relation between number of motor theft incidences and value
of motor insurance in each state. This analysis will help in estimating the value of motor
insurance in a state based on the crime record of the state across years.</br>
Selection of variables:</br>
The relationship between motor theft and insurance value can be viewed for various
years by selecting the year of interest from the right hand filter.
### 4. Prediction of crime based on population :</br>
This chart represents the crime rate for all the cities of selected states (from check box)
based on the population of that city. The trend line shows in general in which direction the
graph seems to be heading. This is used for prediction of crime rate given the value of
population.</br>
Selection of variables :
Select the states using check boxes and observe how trend line adapts to newly
incorporated data values based on your selection. You can enter the value of population in
the “Enter population value” field and slope and intercept of trend line generated to get the
predicted crime rate value (this one is for any given city) seen in “Predicted crime rate”.</br>
### 5. Forecast of year wise crime rate</br>
This model predicts the property and violent crime rate for future 3 years based on
observed data of past 20 years. This forecast will enable administration in taking preventive
and precautionary measures</br>
