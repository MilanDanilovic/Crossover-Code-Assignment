# Crossover-Code-Assignment
Code Assignment
CLOUD CHARGING ENGINE
Real Work Assignment

About this Assignment
In this assessment, you will be presented with a realistic task that closely resembles the challenges you may face on the job. 

Our primary focus is to evaluate your ability to analyze technical alternatives thoroughly, offer valuable insights, determine the optimal solution, make necessary code modifications to fulfill the requirements and ensure the effectiveness of your changes through testing.

Business Background
In telecommunications, billing is based on consumption (e.g., data transferred, text messages sent). Service providers rely on a charging engine to manage the funds (“balance”) of subscriber accounts.
Requirement: Accounts lacking funds must be prevented from accessing services (e.g., text messaging).
Requirement: Low latency must be maintained for a seamless user experience.

The charging engine performs two main operations before granting access to a service: (1) verify adequate account funds and (2) deduct the necessary amount from the account balance.
Requirement: Consistency is crucial to avoid unauthorized service usage, especially during high load.

Technical Background

<img width="767" alt="image" src="https://github.com/MilanDanilovic/Crossover-Code-Assignment/assets/33479438/36818e8d-4ef0-43bf-95df-d4eea6027f82">


AWS API Gateway: Exposes the REST API for charging operations.
AWS Lambda: Hosts the charging engine logic.
AWS MemoryDB (Redis): Stores the data consistently and with low latency.


