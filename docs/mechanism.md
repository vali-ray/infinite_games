## Incentive compatibility

The properness of the scoring rule ensures that the best outcome for the miner is to submit what they truly believe to be the probability distribution of the predicted event. The sequentially shared aspect ensures we only reward miners that bring new information. We want to implement a commit-reveal step as well for the miner prediction. This is however not crucial since the problem of copy-pasting is already handled by the scoring rule. It only makes the system more robust.

In this setting where miners do not risk a negative return for making bad predictions, we are faced with a sybil exploit which consists in deploying two miners with each predicting one outcome of the binary event with maximal confidence. This is mitigated by the registration cost a miner has to pay to enter a subnet, as well as by the upper bound on the number of miners that can participate in the subnet ($192$). 
