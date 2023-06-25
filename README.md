# Evaluation-of-the-probability-of-vehicle-collisions-using-advanced-Machine-Learning-algorithms
Master´s Thesis
This repository corresponds to Jokin Cuesta's Master's Thesis for the Master's Degree in Data Science at the UOC.

As the autonomous driving field continues to grow, it is crucial to prioritize road safety. While the technology has the potential to reduce human error and prevent accidents, there are still many challenges to overcome. Ensuring the safety of both passengers and pedestrians must remain a top priority. The development of autonomous driving technology should be accompanied by strong regulatory frameworks and standards to ensure that safety is not compromised. This thesis focuses on this latter aspect.

With the aim of developing an Artificial Intelligence system that prevents accidents, advanced Machine Learning models have been trained and evaluated (thirteen ML models and twenty-six Stacking Regression models) with collision detection using historical coordinates for vehicles and pedestrians. Therefore, a trajectory prediction algorithm has been designed and, from its output, collisions have been detected and the probability of collision has been calculated. Once the best model has been selected, it has been used to estimate the collision probability of the vehicles with a Monte Carlo Method.

The results obtained were not the expected ones, due to the fact that the distance error between the predicted and real coordinates were around 18 meters. The model with the best results was used to calculate the probability of collision and trigger an alarm.

Keywords: Collision detection, trajectory prediction, Machine Learning, Stacking Regression

Note: There are some references to work of Rafael Corvillo and Raúl Parada Medina.
