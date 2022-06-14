# Ultimate Challenge - Experiment Design


### Scenario: 

The neighboring cities of Gotham and Metropolis have complementary circadian rhythms: on weekdays, Ultimate Gotham is most active at night, and Ultimate Metropolis is most active during the day. On weekends, there is reasonable activity in both cities.

However, a toll bridge, with a two-way toll, between the two cities causes driver partners to tend to be exclusive to each city. The Ultimate managers of city operations for the two cities have proposed an experiment to encourage driver partners to be available in both cities, by reimbursing all toll costs.


### Metrics to evaluate:

1. `Ratio of rides given outsite the city` - to measure partner participation in this experiment
Since partners tend to stay within their own cities, the number of rides given outside of the city is currently very low relative to all rides given by partners of that particular city. If partners are actually participating in this experiment, this ratio should see an increase.

2. `Profit or margin` - to measure the effectiveness of this initiative
If this experiment is successful, the increase in revenue from this change should be greater than the increase in cost from toll reimbursements and all other operational costs pertaining to the experiment.


### Data to collect:

- `Rides` - time, location, city, out-of-city ride indicator, partner, user, and ride cost
- `Reimbursements` - time, toll direction, partner, and cost
- `All other costs` - costs from the experiment are labeled
- `Revenue` - revenue from service provided out-of-city are labeled


### Experiment summary:

Each city will collect their own data. If any of the data above (except reimbursements) is not already available, then company operations will continue as they are for another quarter, in order to collect all of this data to serve as a historic baseline, and the experiment will be postponed. If this data is already available, the experiment can begin immediately.

In this experiment, toll reimbursements will be offered to both cities at the same time. I suspect it may not be very useful to deploy it in 1 city at a time as the 2 cities have complementary circadian rhythms, which means they cannot act as each other's control group. Partners will be notified ahead of time of this new offer and those who have not used it will be periodically reminded to ensure all partners are aware. The data mentioned above will be collected for a period of 1 quarter and evaluated against historic data, using the 2 metrics mentioned above. During the length of this experiment, no other major change is to be implemented.

A 1-proportion Z-test will be used to determine the significance of the change in the out-of-city rides ratio (metric 1) for each city and a 1-sample t-test will be used to determine the significance of the change in profit (metric 2) for each city, accounting for any growth the company might be experiencing at the time.


### Possible results:

1. No significant increase in metric 1 - not enough participation by partners.
This immediately invalidates the results of the change in metric 2, whether or not it was significant. If the company still wishes to pursue the initiative despite this result, the experiment needs to be redesigned to incentivize participation and carried out for another quarter.

2. Significant increase in metric 1, but no significant increase in metric 2 - initiative is not effective.
In this case, there was enough participation to validate the results of the change in metric 2, but that change was either a decrease or an insignificant increase in profits. This is a sign that this initiative is not worth pursuing. Further testing may prove otherwise, but costs would have to be streamlined.

3. Significant increase in both metrics 1 and 2 - initiative is effective.
Statistically, we would be able to say that this initiative was able to increase quarterly profits. Even though it was successful, there is still room for improvement. Introducing cost-effective incentives to drive participation may increase profits even more, so this is something that can be implemented in the next experiment.

Since each city collected their own data, they would have their own result to this experiment. We would know how effective the initiative was in each city and take measures accordingly.
