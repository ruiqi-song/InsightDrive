# InsightDrive: Insight Scene Representation for End-to-End Autonomous Driving
### [Paper](https://arxiv.org/abs/2503.13047)

> InsightDrive: Insight Scene Representation for End-to-End Autonomous Driving

> [Ruiqi Song](https://scholar.google.com/citations?hl=en&user=hMSOTPoAAAAJ&view_op=list_works&sortby=pubdate)\*, 
> [Xianda Guo](https://scholar.google.com/citations?user=jPvOqgYAAAAJ)\*,
> [Yanlun Peng](https://github.com/ruiqi-song),
> [Hangbin Wu](https://ieeexplore.ieee.org/author/37068941300)$\dagger$, 
> [Qinggong Wei](https://github.com/ruiqi-song), 
> [Long Chen](https://scholar.google.com/citations?user=jzvXnkcAAAAJ)$\dagger$

\* Equal contribution  $\dagger$ Corresponding author


## News
- **[2025/5/07]** README.md Release



## Overview
![overview]

<img src=./assets/overview.png> 

- We present InsightDrive, which leverages CoT instructions to fine-tune LLMs and establishes a human–LLM–vehicle distillation pipeline that transfers human driving cognition into onboard models for joint explicit and implicit scene representation. 
- We design a Task-level Mixture-of-Experts adapter that injects human driving cognitive processes into scene representations with minimal parameter overhead, which enhances scene understanding and reasoning. 
- We propose a diffusion-based generative planner that uses explicit attention and implicit reasoning as conditions for generating robust and adaptive trajectories. 
- We conduct comprehensive experiments on both the nuScenes and Navsim benchmarks, which demonstrate the effectiveness and robustness of InsightDrive and show that it achieves state-of-the-art performance.
## FrameWork
<img src=./assets/framework.png>

## Result
<p align="center">
<img src=./assets/result_nus.png alt="Description" width="780"/>
</p>
<p align="center">
<img src=./assets/result_nav.png alt="Description" width="780"/>
</p>

## Visualization

<img src=./assets/vis.png>

## Related Projects

Also thanks to these excellent open-sourced repos:
[GenAD](https://github.com/wzzheng/GenAD) 


## Citation

If you find this project helpful, please consider citing the following paper:
```
@article{insightdrive2025,
    title={InsightDrive: Insight Scene Representation for End-to-End Autonomous Driving},
    author={Ruiqi Song and Xianda Guo and Hangbin Wu and Qinggong Wei and Long Chen },
    journal={https://arxiv.org/abs/2503.13047},
    year={2025}
}
```
