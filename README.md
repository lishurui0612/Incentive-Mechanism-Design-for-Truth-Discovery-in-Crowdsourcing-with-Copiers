# Incentive-Mechanism-Design-for-Truth-Discovery-in-Crowdsourcing-with-Copiers
This project includes code for Incentive Mechanism Design for Truth Discovery in Crowdsourcing with Copiers, which is voting for TSC.

This paper includes three parts: BERT and KANN-DBSCAN, Truth Discovery, Reverse Auction and Payment.

BERT and KANN-DBSCAN convert textual data into vectors and cluster these data.

Truth Discovery uses these clustering data to find the truth. In this part, we compute the dependence of each two workers and the probability of each value in the task being the truth.

Reverse Auction and Payment computes the accuracy of each worker in each task, and use auction data to find winner to do each task. We reward every winner by calculating the irreplaceability of each winner
