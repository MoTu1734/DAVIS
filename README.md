# DAVIS

**A Depth-Only End-to-End Active-Vision Framework for Humanoid Soccer Skills**

DAVIS is a depth-only framework for learning humanoid soccer contact skills. Its policy uses a head-mounted depth image, proprioceptive history, and an optional task command to produce 25-DoF joint targets. Training combines visibility-aware auxiliary geometry, a transition from ground-truth to predicted features, task curricula, and motion priors. The paper evaluates goal-directed shooting and directional dribbling in simulation and on the Noetix E1 robot.

## Links

- [Project website](https://thusi-lab.github.io/DAVIS/)
- [Paper on arXiv](https://arxiv.org/abs/2609.28175)
- [Video demonstration](https://thusi-lab.github.io/DAVIS/#video)
- [Personal website mirror](https://motu1734.github.io/DAVIS/)

## About this repository

This repository hosts the static project website, including its figures, demonstration video, and a copy of the paper. It does not contain the training or robot deployment code. The organization and personal repositories publish the same project page.

## Citation

```bibtex
@misc{jin2026davisdepthonlyendtoendactivevision,
  title={DAVIS: A Depth-Only End-to-End Active-Vision Framework for Humanoid Soccer Skills},
  author={Jiakang Jin and Yixiao Huo and Pengyuan Wang and Yinan Han and Tingxuan Zhang and Zhuobing Zhao and Xuanxin Zhou and Zhangchen Ye and Enxuan Ruan and Yifei Bao and Jiankun Yang and Chenghao Sun and Wenhao Cui and Xiaoyu Tian and Yiming Li},
  year={2026},
  eprint={2609.28175},
  archivePrefix={arXiv},
  primaryClass={cs.RO},
  url={https://arxiv.org/abs/2609.28175}
}
```

## Local preview

```powershell
python .\serve.py --host 127.0.0.1 --port 8000
```

Open <http://127.0.0.1:8000/index.html>.

The website layout is adapted from the [GALATEA project page](https://github.com/boyuan-an/GALATEA/tree/gh-pages).
