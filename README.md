# Thompson-Sampling-for-Ad-Selection
This project implements Thompson Sampling, a popular algorithm for solving the Multi-Armed Bandit problem. The goal is to maximize the total reward by selecting the most optimal ads based on their click-through rates (CTR).

KEY FEATURES

Data Import: The dataset used contains the click-through data of 10 different ads. Each row represents a user interaction with one of the ads, and the reward indicates whether the user clicked the ad (1 for clicked, 0 for not).

Thompson Sampling Algorithm: This implementation simulates the ad selection process over 10,000 trials. For each trial, the algorithm uses Beta distribution (a probability distribution) to model the success rate of each ad and selects the one with the highest probability of being the best option. The algorithm continuously updates the success/failure counts of each ad based on whether the user clicked it.

Visualization: The project includes a histogram to visualize the number of times each ad was selected, helping you understand the algorithm's behavior and how it converges toward selecting the most successful ad.

HOW TO USE

1.Clone the repository.
2.Place the Ads_CTR_Optimisation.csv dataset file in the same directory as the Python script.
3.Run the script to see the algorithm in action and the histogram displaying ad selections.
