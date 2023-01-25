#### Discriminative Experience Replay (DER)

This codebase accompanies paper "Discriminative Experience Replay for Efficient Multi-agent Reinforcement Learning".

DER is written based on  [PyMARL](https://github.com/oxwhirl/pymarl) codebases which are open-sourced.

##### Installation instructions

1. Install the following environments from corresponding links:

- StarCraft Multi-Agent Challenge (SMAC): https://github.com/oxwhirl/smac

Note: you need to replay the SMAC_PATH/env/starcraft2/starcraft2.py with starcraft2.py in this repo

2. Install [PyMARL](https://github.com/oxwhirl/pymarl)  as instructed.

##### Run an experiment

```python
python3 src/main.py --config=qmix --env-config=sc2 with env_args.map_name=MMM2 learner=q_divide_learner selected=PER_weight warm_up=True selected_alpha=0.8
```
