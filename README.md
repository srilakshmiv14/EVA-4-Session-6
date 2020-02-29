# EVA-4-Session-6


Observation on L1 and L2 regularization techniques on model:
When we use L1:
The Model has the maximum training accuracy of 97.34% and test accuracy of 98.19% and there is considerable effect of Under fitting. Regularization helps to increase the capacity of the model and actually increases the testing accuracy. It is not able to train well on Complex Patterns. Hence, less training accuracy. L1 acts as a Sparse Solution.

When we use L2
The Model has the maximum training accuracy of 99.22% and test accuracy of 99.51%   Regularization helps to increase the capacity of the model and actually increases the testing accuracy. It is able to train well on Complex Patterns. Hence, better training accuracy. L2 acts as a Non-Sparse Solution.

with L1 and L2
The Model has the maximum training accuracy of 97.35 % and test accuracy of 98.44%   Regularization helps to increase the capacity of the model and actually increases the testing accuracy. Here when we use both the regularization models, it is balancing the gap between Training and Testing Accuracy (0.02 to 0.05 difference appears). Hence we are using Regularization to control model generalization.

Without L1 and L2

The Model has the maximum training accuracy of 99.17% and test accuracy of 99.48%. The testing accuracy is stable for last 15 epochs (model is run over 40 Epochs) as we are using LR Scheduler with learning rate of 0.05, step size 6 and gamma value of 0.5. But here it is not able to generalize well on the model, that is not able to learn complex patterns. 
