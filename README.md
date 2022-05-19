# Data Analysis Challenge - Ultimate Technologies, Inc.

This is a 3-part data analysis challenge using simulated data from a fictional company - Ultimate Technologies, Inc. The data and parts of the challenge are described below.


## Data

1. `logins.json` - contains timestamps of user logins in a particular geographic location
2. `ultimate_data_challenge.json` - a sample dataset of a cohort of users who signed up for an Ultimate account in January 2014
    - `city` - city this user signed up in
    - `phone` - primary device for this user
    - `signup_date` - date of account registration (in the form "YYYYMMDD")
    - `last_trip_date` - the last time this user completed a trip (in the form "YYYYMMDD")
    - `avg_dist` - the average distance in miles per trip taken in the first 30 days after signup
    - `avg_rating_by_driver` - the rider’s average rating over all of their trips
    - `avg_rating_of_driver` - the rider’s average rating of their drivers over all of their trips
    - `surge_pct` - the percent of trips taken with surge multiplier greater than 1
    - `avg_surge` - the average surge multiplier over all of this user’s trips
    - `trips_in_first_30_days` - the number of trips this user took in the first 30 days after signing up
    - `ultimate_black_user` - whether the user took an Ultimate Black in their first 30 days
    - `weekday_pct` - the percent of the user’s trips occurring during a weekday


## 1. Exploratory Data Analysis

User login counts are aggregated based on 15-minute time intervals to understand underlying patterns of the demand.


## 2. Experiment and Metrics Design

The neighboring cities of Gotham and Metropolis has complementary circadian rhythms:
- On weekdays, Ultimate Gotham is most active at night and Ultimate Metropolis is most active during the day
- On weekends, there is reasonable activity in both cities

However, a toll bridge, with a 2-way toll, between the 2 cities causes driver partners to tend to be exclusive to each city. The ultimate managers of city operations for the two cities have proposed an experiment to encourage driver partners to be available in both cities, by reimbursing all toll costs.
1. What would be a key measure of success of this experiment in encouraging driver partners to serve both cities, and why?
2. Design a practical experiment to compare the effectiveness of the proposed change in relation to the key measure of success.
    - How would the experiment be implemented?
    - What statistical test(s) would be conducted to verify the significance of the observation?
    - How would the results be interpreted and recommendations be provided to the city operations team (along with any caveats)?


## 3. Predictive Modeling

Ultimate is interested in predicting rider retention. The user cohort data was pulled several months later and a user is considered retained if they were "active" (i.e. took a trip) in the last 30 days. This part focuses on understanding what factors are the best predictors for retention and offering suggestions to operationalize those insights to help Ultimate.