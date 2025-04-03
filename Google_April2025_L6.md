# Interview 1:
A service calls a series of the backend systems

Interviewer Questions 
1. What are the thoughts you have in mind?
2. What is trade off of consistency and availability? Is there a middle ground of consistency?
3. What is the schema and the API structure looks like?
4. What is the protocol you will use for the communication?
5. What will you do if one service doesn't responsd in 10 seconds.
6. What will you do if one service result depends on the another service?

After interview thoughts:
1. Sync to all nodes, Sync to some of the nodes,
2. Real life systems: Load Balancers, orchestrators, Elastic Search (Scatter and Gatter), Leaderless replication 
