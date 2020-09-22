## SISL Enviroments

{% include bigtable.html group="sisl/" avg_rew=1 %}

`pip install pettingzoo[sisl]`

The SISL environments are a set of three cooperative multi-agent benchmark environments, created at SISL and released as part of "Cooperative multi-agent control using deep reinforcement learning." The code was originally released at: https://github.com/sisl/MADRL

Please note that we've made major bug fixes to waterworld and pursuit, and minor bug fixes to multiwalker. As such, we discourage directly comparing results on these environments to those in the original paper.

If you use these environments, please additionally cite:

```
@inproceedings{gupta2017cooperative,
  title={Cooperative multi-agent control using deep reinforcement learning},
  author={Gupta, Jayesh K and Egorov, Maxim and Kochenderfer, Mykel},
  booktitle={International Conference on Autonomous Agents and Multiagent Systems},
  pages={66--83},
  year={2017},
  organization={Springer}
}
```
