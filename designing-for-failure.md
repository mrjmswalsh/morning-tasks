# Designing for failure

​
Identify the kinds of failure readiness described below, giving your reasoning;
​

1. A system that switches to a new server when one fails

- Failover. A system that identifies the issue and fails over to another server is failure tolerant.
    ​
2. Adding replica databases with a master database

- Redundancy. Replica databases are avoiding a Single Point of Failure (SPOF)
    ​
3. Having a 2-3 colleagues who have access to the master password

- Redundancy. Again, avoding a SPOF if one colleague goes AWOL with the master password.
    ​
4. Performing health checks on a server

- Monitoring. Proactively looking for failures or performance degredation to allow for prompt action and building resilience.
    ​
5. Spreading out user requests over multiple machines rather than just one powerful one

- Load balancing. Avoiding overloading one server/machine and spreading the load across multiple at popular times etc
