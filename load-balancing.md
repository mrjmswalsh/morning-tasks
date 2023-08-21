# Load Balancing
​
Can you decide what type of load balancing from the notes might work best for the following situations;
​
- A chat service where users maintain active connections for a while.
Round Robin. Least response times could be prioritised if it's an important metric. Session persistence config may be a consideration
​
- An AI image generation API with paid tiers.
Weighted Round Robin - so premium users have more resources allocated to them
​
- A social media website that has users all over the world.
Distribute requests based on geographical location, i.e. to the nearest data centre.
​
- An authorisation service that takes the same amount of time for each request.
Round Robin as all requests will be the same.
​
- A gaming server that requires low latency.
Least response time, as this will prioritise servers with the lowest response time and latency.