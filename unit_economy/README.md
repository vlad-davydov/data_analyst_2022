# Study project: business metric analysis

## Project task

In this project we need to analyse server logs containing information about user application visits. Using this data we need to perform an analyse how people are using our product, when they start making orders, how much profit each client brings in, when it pays off and what factors negatively affect user acquisition. We should also consider advertising costs data.

## Data
* Table `visits_log_short` - server log with website users visits data;
* Table `orders_log_short` - users orders information;
* Table `costs_short` - marketing costs information.

## Used libraries
*pandas*, *seaborn*, *plotly*.

## Project completion status - ✔️ Completed

In this project we have analysed visits, orders and marketing costs of our website from 2019-05-01 till 2019-10-27. Unfortunately, according to this analysis the overall app ROI does no reach "1" in two week after user acquisition. <br>

Base on the results, the following recommendations and points of growth can be identified:
1. It is necessary to reduce the costs of the TipTop acquisition channel, as investing money in it does not give a significant increase in users.
2. The reasons for the low retention of paying users for FaceBoom channels in the US and AdNonSense in Europe need to be further explored. Most likely, the reason is the promotion or discount that is offered to the user: they pay for the content only the first time, but do not make a purchase the second time.
3. We should study users from the USA, because they make up the main audience of our application.
