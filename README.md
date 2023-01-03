# Case Study_DSLS 2023 Selection

# Case : Yellow Taxi
# Backround 
The majority of New Yorkers depend on public transportation or taxi services. Only 22% of Manhattan residents own a car compared to an average of 91% of households across the United States owning at least one car. Taxi service in New York is the fourth largest transportation network in the United States. The system is regulated by the New York City Taxi and Limousine Commission (TLC), which oversees yellow taxis, charter taxis, commuter cars, transit vehicles, and certain limousines. Despite its large network, the current system does not serve the boroughs equally. Because of this, residents prefer illegal taxi services that have inconsistent access and fares.

Additional Details :
- Borough : A certain area/region in New York. There are five boroughs in New York, namely the Bronx; Brooklyn; Manhattan; queens; and the Staten Islands.
- Information regarding the boroughs in the dataset can be seen in the 'PULocationID' and 'DOLocationID' columns. The borough details can also be seen on the map of each borough that has been provided.

# Problem case
1. What __causes__ yellow taxi services to __only be concentrated in certain boroughs__, causing an imbalance in demand and supply in other boroughs?
2. TLC wants their yellow taxi service to be spread evenly throughout the city of New York so that it can answer the existing demand. __What should TLC do in the short term (6 months) to overcome this challenge?__

# Result 
Based on my analysis, besides the use of __taxi services depending on rush hours__, the issue of __trip duration also affects the distribution of taxi services__. What I can recommend based on this analysis is to try to __create a Machine Learning algorithm to predict trip duration based on the pickup location ID and drop-off location ID__. This algorithm will later be __used to help prospective passengers find out the estimated time to their destination__. This can be tested for use in the next six months, then to see the impact or impact of this recommendation can be re-analyzed using the Causal Impact method to see a comparison of the distribution of taxi services before implementing what is recommended with the distribution of taxi services when after implementing what is has been recommended.
