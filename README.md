# Robotic Auxiliary Losses
This is a baselines DDPG implementation with added Robotic Auxiliary Losses

To install, first set up the baselines repository on your workstation (https://github.com/openai/baselines/)

Afterwards, go to baselines/baselines/ddpg and clone this repository (NOTE: this will overwrite the original ddpg implementation!)

Example training run:

> python -m baselines.ddpg.main --env-id Humanoid-v2 --aux-tasks 'repeat' 'caus' --log-dir /tmp/RobAuxLossTest
