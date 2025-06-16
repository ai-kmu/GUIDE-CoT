# GUIDE-CoT
The official implementation code for "GUIDE-CoT: Goal-driven and User-Informed Dynamic Estimation for Pedestrian Trajectory using Chain-of-Thought" [AAMAS 2025]

## Acknowledgements
This project significantly builds upon the work of others. We extend our sincere gratitude to the authors and developers of the following projects:

* The `goal_module` is largely based on the implementation of [Goal-SAR](https://github.com/luigifilippochiara/Goal-SAR). We express our sincere gratitude for their work and for making their code publicly available.

* The `llm_module` incorporates and adapts significant portions of code from [LMTraj-SUP](https://github.com/InhwanBae/LMTrajectory). We deeply appreciate their contributions and the accessibility of their resources.

## Installation
* All experiments were performed in an Ubuntu 20.04, Python 3.9, RTX 3090Ti environment.
* Install the following conda environment.
    ```bash
    $ conda env create -f guide-cot.yaml
    $ conda activate GUIDE-CoT
    ```

* Install OpenAI CLIP Library following this [[link]](https://github.com/openai/CLIP)

## Preprocess
```bash
$ bash scripts/preprocess_all.sh
```

## Training
```bash
$ bash scripts/train_all.sh
```

## Evaluation
```bash
$ bash scripts/test_all.sh
```

## Citation
```
@inproceedings{kim2025guide,
  title={GUIDE-CoT: Goal-driven and User-Informed Dynamic Estimation for Pedestrian Trajectory using Chain-of-Thought},
  author={Kim, Sungsik and Baek, Janghyun and Kim, Jinkyu and Lee, Jaekoo},
  booktitle={Proc. of the 24th International Conference on Autonomous Agents and Multiagent Systems},
  pages={1107--1116},
  year={2025}
}
```


