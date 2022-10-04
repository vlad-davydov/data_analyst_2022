# Study project: Moscow restaurants data analysis

## Project task
In this project, we need to analyse the market of public catering business in Moscow in order to decide in the future on opening a cafe (or a cafe chain) with an innovative idea - service by robots. We should give recommendations on the geographical location, type and possible other parameters of the cafe planned for opening. External open data on the restaurants of the Moscow city from the mos.ru portal can be used.

## Data
* Table `rest_data` - contains information about Moscow food service providers;
* External information about Moscow food service providers using website `mos.ru`.

## Used libraries
*pandas*, *seaborn*, *plotly*.

## Project completion status - ✔️ Completed

In this project we have analysed information about public catering business using provided and external data. <br>

We have showed what type of catering establishments is lacking in which Moscow district. Our recommendations will be:

* It is better to start with "fast food" type of establishments if we want to run with chain cafes: those type of establishments are lacking in central districts. On the other hand the average number of seats is low.
* In the central districts, there is also a lack of "canteen" type establishment. They have the largest average number of seats, but with little prevalence as a chain.
* The best option may be a chain "restaurant" in numerous residential areas - there is not enough of this establishment type. Also there will be less competitors.

In any case, this study will need to be supplemented by a study of the number of inhabitants in each district, as well as a study of the pedestrian street traffic in the central districts.
