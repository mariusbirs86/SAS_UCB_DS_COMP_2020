# SAS_UCB_DS_COMP_2020
Who are the Unhappy Buddies

Competition Goal:
Forecast the churn_dummy field

Train Data Set
•
50 K train customers data, with churn_dummy variable
•
Transactional table related to 50 K train customers data
2.
Live Data Set  may be used as additional Train Data Set
•
50 K application customers data, where churn dummy variable may be derived
•
Transactional table related to 50 K application customers data
3.
Application Data Set
•
50 K application customers data, without churn_dummy variable
•
Transactional table related to 50 K application customers data

About Datasets:

Some fields related to customers characteristics, that are
•
id : randomly generated
•
gender
•
tenure_days : number of days since the subject is a buddy
•
age
•
primary _address_city : the city (with * we do refer to «other», the cities with only a few of
•
some dummy variables: respectively being or not an italian citizen, a student, a worker, have a promotion,
own the love profile, have closed the acount (churn)
•
estinction_date : account closing date, evaluated only for churn=1

For each customer, we do have a number of transactions (can be also zero)
•
ids_id : the foreign key for linking to the customers table
•
tp_mov_gk : transaction tipe
•
co_naz_iso : country where the transaction took place
•
dv_mov : currency
•
im_mov : transaction amount
•
tipo_carta : card type
•
new_dt_ope : day and hour of the transaction
