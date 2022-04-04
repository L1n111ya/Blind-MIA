# Blind-MIA
This is  code,  for "Practical Blind Membership Inference Attack via Differential Comparison" , which is I learnt yet.
******
## Preliminary Works
First, we should run `TargetModel.py` to train a target model. Then, we run `ShadowModel.py` to train a shadow model for unexpected needs. After do like this, we have done the preliminary works which can let us do BlindMIA.

## BlindMI Attack
We have nine membership inference attack to use. Let's tell you how to use it and what about its utility:

**BlindMI_Diff_W:** It's a membership inference attack with non-memership-set. And it use MMD to estimate a data which is in train-set or not.
