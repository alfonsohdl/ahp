----------------------------------------------- PROJECT #6 ---------------------------------------------

Margin Call Recovery Probability Model:

· The project goal is to estimate the probability that an outstanding exposure (outstanding Margin Calls, pending to be paid/collected) will be collected within a given horizon, conditional on its current age and features.

*“Given how long an account has had a margin call open, what is the probability that it will finish paying (i.e., settle its outstanding obligation) within the next X days?”*

· The Margin Call Recovery Probability Model predicts how likely each outstanding margin call is to be collected in the future. It focuses on the remaining amount owed (GBP Outstanding) rather than the total initially issued. Every record in the model represents a specific MC’s situation at a given observation date, allowing the model to simulate real-world monitoring.

A Jupyter notebook that contains all of the code ---> [HERE](cox_survival_margincall_model.ipynb)
A paper which explains how the model was built in a more detailed way ---> [HERE](MarginCall_RecoveryProbability_Model_v7.pdf)

------------------------------------------------------------------------------------------------------------
 **DISCLAIMER**: My content is educational - It is not financial advise
