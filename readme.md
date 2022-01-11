# Predicting Airbnb New User Booking Destination
## by Aya Abulnasr
https://medium.com/@aya.abulnasr/predicting-your-next-destination-country-for-airbnb-3355ae90b8e4


## Dataset

> Airbnb  is an American company. It began in 2008 to help travelers to find a place to stay over 220 countries.

I will analyze some Airbnb data about its customers and users’ behavior over Airbnb platform and the main goal is to predict the new user’s booking destination.

Data: Following are the features present in training dataset:
id: user id
date_account_created: the date of account creation
timestamp_first_active: timestamp of the first activity, 
date_first_booking: date of first booking
gender
age
signup_method: whether user has signup from website or by using facebook, gmail etc.
signup_flow: the page a user came to signup up from
language: international language preference
affiliate_channel: what kind of paid marketing
affiliate_provider: where the marketing is e.g. google, craigslist, other
first_affiliate_tracked: whats the first marketing the user interacted with before the signing up
signup_app
first_device_type
first_browser
country_destination: this is the target variable. There are 12 possible outcomes of the destination country: 'US', 'FR', 'CA', 'GB', 'ES', 'IT', 'PT', 'NL','DE', 'AU', 'NDF' (no destination found), and 'other'.

Data preprossesing: 

Lots of missing and misleading data found in those columns:

Age: Filling with mean of normal age is 37 and limiting it from 16 to 110 years old.
Gender: Unknown
Country destination: NDF “No Destination Found” which means no booking happens.

