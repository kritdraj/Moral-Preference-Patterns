# Moral-Preference-Patterns

This project is an implementation of the Moral Machine Experiment [1], a study conducted by MIT to understand societal expectations about how autonomous vehicles should solve moral dilemmas. It estimates people’s preferences by collecting survey responses. Participants are shown two scenarios that mimic the trolley problem and are asked to choose what they think the self-driving car should do. An example of the two alternatives presented is- an autonomous car with three passengers will kill the two pedestrians crossing the road ahead if it stays on course, and alternatively the car can swerve to avoid the two pedestrians but would hit a barrier and kill the passengers instead. Conjoint analysis is used to calculate the Average Causal Marginal Effects (AMCE) of each attribute. AMCE is a causal quantity that represents the increase in probability of sparing a character when the attribute value changes from a baseline value to another value of the attribute. This quantity represents the population’s moral preference to save a character with this attribute level over the other. For example, for the attribute- gender, it gives us the difference in the probability that a male character is spared and the probability that the female character is saved. 

The result of this project shows 3 cultural clusters. Cultural clusters are the formed by computing country-wise AMCE estimates- where all the responses from a country are used to compute a single AMCE value that represents its moral values. These AMCE values are then clustered using hierarchical methods. The paper reports three distinct cultural clusters with different moral preferences.

References:

[1]	Awad, E., Dsouza, S., Kim, R. et al. The Moral Machine Experiment. Nature, 2018. https://doi.org/10.1038/s41586-018-0637-6 

[2]	Awad, E., Dsouza, S., Kim, R. et al. The Moral Machine Experiment – Supplementary Material. Nature, 2018.
