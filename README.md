# BCG_PowerCo_Customer_Churn

<p>
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e8/BCG_Corporate_Logo.svg/800px-BCG_Corporate_Logo.svg.png" alt="BCG" width="400" style="margin-right: 40px;" />  
  <img src="https://batteryindustry.tech/wp-content/uploads/2024/07/B2024CW00065_web_1600.png" alt="PowerCo" width="400" />
</p>

# About PowerCo
PowerCo is a major gas and electricity utility that supplies to corporate, SME (Small & Medium Enterprise), and residential customers.

# Problem Statement
They have partnered with BCG to help diagnose the source of churning SME customers.

A fair hypothesis is that price changes affect customer churn. Therefore, it is helpful to know which customers are more (or less) likely to churn at their current price, for which a good predictive model could be useful.

Moreover, for those customers that are at risk of churning, a discount might incentivize them to stay with our client. The head of the SME division is considering a 20% discount that is considered large enough to dissuade almost anyone from churning (especially those for whom price is the primary concern).

The Associate Director (AD) held an initial team meeting to discuss various hypotheses, including churn due to price sensitivity. After discussion with the team, I have been asked to go deeper on the hypothesis that the churn is driven by the customers’ price sensitivities.

My AD wants an email with my thoughts on how the team should go about testing this hypothesis.

The client plans to use the predictive model on the 1st working day of every month to indicate to which customers the 20% discount should be offered.

# About Datasets

Powerco has shared two Comma separated Value(.CSV file) files, Historical customer data which is inclusive of customer data such as usage, sign up date, forecasted usage as well churn indicator to check whether each customer has churned or not and also Historical pricing data like variable and fixed pricing data etc.

## client_data.csv:
id = client company identifier
activity_new = category of the company’s activity
channel_sales = code of the sales channel
cons_12m = electricity consumption of the past 12 months
cons_gas_12m = gas consumption of the past 12 months
cons_last_month = electricity consumption of the last month
date_activ = date of activation of the contract
date_end = registered date of the end of the contract
date_modif_prod = date of the last modification of the product
date_renewal = date of the next contract renewal
forecast_cons_12m = forecasted electricity consumption for next 12 months
forecast_cons_year = forecasted electricity consumption for the next calendar year
forecast_discount_energy = forecasted value of current discount
forecast_meter_rent_12m = forecasted bill of meter rental for the next 2 months
forecast_price_energy_off_peak = forecasted energy price for 1st period (off peak)
forecast_price_energy_peak = forecasted energy price for 2nd period (peak)
forecast_price_pow_off_peak = forecasted power price for 1st period (off peak)
has_gas = indicated if client is also a gas client
imp_cons = current paid consumption
margin_gross_pow_ele = gross margin on power subscription
margin_net_pow_ele = net margin on power subscription
nb_prod_act = number of active products and services
net_margin = total net margin
num_years_antig = antiquity of the client (in number of years)
origin_up = code of the electricity campaign the customer first subscribed to
pow_max = subscribed power
churn = has the client churned over the next 3 months

## price_data.csv:
id = client company identifier
price_date = reference date
price_off_peak_var = price of energy for the 1st period (off peak)
price_peak_var = price of energy for the 2nd period (peak)
price_mid_peak_var = price of energy for the 3rd period (mid peak)
price_off_peak_fix = price of power for the 1st period (off peak)
price_peak_fix = price of power for the 2nd period (peak)
price_mid_peak_fix = price of power for the 3rd period (mid peak)

link: 
[client]("C:\Users\Anurag\OneDrive\Desktop\BCG Internship\client_data.csv")
[price]("C:\Users\Anurag\OneDrive\Desktop\BCG Internship\price_data.csv")
