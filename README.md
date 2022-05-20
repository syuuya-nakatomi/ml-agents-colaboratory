# ml-agents-colaboratory
Machine learning with ml-agents on colab
As an example, here is a notebook where you can try out the walker in ml-agents
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/syuuya-nakatomi/ml-agents-colaboratory/blob/main/run_example_walker.ipynb)<br>
To process on a free Tesla K80 GPU, switch the notebook settings to GPU and modify the last line as follows
```
!mlagents-learn ml-agents/config/ppo/Walker.yaml --run-id=$run_id --env=$env_name --no-graphics --torch-device=cuda:0
```
Current Goals:Building an environment for reinforcement learning using TPUs
