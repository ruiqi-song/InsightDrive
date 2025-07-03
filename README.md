# InsightDrive: Insight Scene Representation for End-to-End Autonomous Driving
### [Paper](https://arxiv.org/abs/2503.13047)

> InsightDrive: Insight Scene Representation for End-to-End Autonomous Driving

> [Ruiqi Song](https://scholar.google.com/citations?hl=en&user=hMSOTPoAAAAJ&view_op=list_works&sortby=pubdate)\*, 
> [Xianda Guo](https://scholar.google.com/citations?user=jPvOqgYAAAAJ)\*,
> [Hangbin Wu](https://ieeexplore.ieee.org/author/37068941300)$\dagger$, 
> [Qinggong Wei](https://github.com/ruiqi-song), 
> [Long Chen](https://scholar.google.com/citations?user=jzvXnkcAAAAJ)$\dagger$

\* Equal contribution  $\dagger$ Corresponding author


## News
- **[2025/5/07]** README.md Release



## Overview
![overview]

<img src=./assets/overview.png> 

- In this paper, a novel end-to-end autonomous driving method called InsightDrive is proposed, which organizes perception by attention-centric scene representation inspired by human drivers. 
- This approach imitates the attention allocation behavior of human drivers by constructing chain-of-thought-based instructions, and fine-tunes a large language model (LLM) to generate knowledge aligned with human attention patterns. 
- A lightweight vision-language adapter is employed to inject human driver knowledge into the conventional scene representation, which allows the model to achieve attention-centric scene modeling with negligible increase in model parameters. 
- The method establishes a knowledge distillation pipeline from human drivers to LLMs and finally to onboard models. 
- Furthermore, we employ self-attention and cross-attention mechanisms to model the ego-agents and agents-map relationships to comprehensively build the topological relationships of the scene.
- Comprehensive evaluations on the widely adopted nuScenes benchmark demonstrate that InsightDrive achieves considerable improvements over conventional scene representation approaches.
## FrameWork
<img src=./assets/framework.png>

## Result
<p align="center">
<img src=./assets/result_nus.jpg alt="Description" width="780"/>
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
