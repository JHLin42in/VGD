<p align="center">
  <h1 align="center">VGD: Visual Geometry Gaussian Splatting for Feed-Forward Surround-view Driving Reconstruction</h1>
  <p align="center">
    Junhong Lin</a><sup>1</sup>
    &nbsp;·&nbsp;
    Kangli Wang</a><sup>1</sup>
    &nbsp;·&nbsp;
    Shunzhou Wang</a><sup>1</sup>
    &nbsp;·&nbsp;
    Songlin Fan</a><sup>1</sup>
    &nbsp;·&nbsp;
    Ge Li</a><sup>1</sup>
    &nbsp;·&nbsp;
    Wei Gao</a><sup>*1, 2</sup>
    &nbsp;·&nbsp;
  </p>
  <p align="center">
    <sup>1</sup>School of Electronic and Computer Engineering, Peking University
    <br>
    <sup>2</sup>Peng Cheng Laboratory
  </p>
  <h3 align="center"><a href="https://arxiv.org/pdf/2510.19578">Paper</a> </h3>
</p>


# VGD: Visual Geometry Gaussian Splatting for Feed-Forward Surround-view Driving Reconstruction

Code will be released soon. TBD.


## Introduction
Feed-forward surround-view autonomous driving scene reconstruction offers fast, generalizable inference ability, which faces the core challenge of ensuring generalization while elevating novel view quality. Due to the surround-view with minimal overlap regions, existing methods typically fail to ensure geometric consistency and reconstruction quality for novel views. To tackle this tension, we claim that geometric information must be learned explicitly, and the resulting features should be leveraged to guide the elevating of semantic quality in novel views. In this paper, we introduce Visual Gaussian Driving (VGD), a novel feed-forward end-to-end learning framework designed to address this challenge. To achieve generalizable geometric estimation, we design a lightweight variant of the VGGT architecture to efficiently distill its geometric priors from the pre-trained VGGT to the geometry branch. Furthermore, we design a Gaussian Head that fuses multi-scale geometry tokens to predict Gaussian parameters for novel view rendering, which shares the same patch backbone as the geometry branch. Finally, we integrate multi-scale features from both geometry and Gaussian head branches to jointly supervise a semantic refinement model, optimizing rendering quality through feature-consistent learning. Experiments on nuScenes demonstrate that our approach significantly outperforms state-of-the-art methods in both objective metrics and subjective quality under various settings, which validates VGD's scalability and high-fidelity surround-view reconstruction.


## BibTeX
```
@article{lin2025vgd,
  title={VGD: Visual Geometry Gaussian Splatting for Feed-Forward Surround-view Driving Reconstruction},
  author={Lin, Junhong and Wang, Kangli and Wang, Shunzhou and Fan, Songlin and Li, Ge and Gao, Wei},
  journal={arXiv preprint arXiv:2510.19578},
  year={2025}
}
```

## Acknowledgements

This project is partially based on some awesome projects: [MVSplat](https://github.com/donydchen/mvsplat), and [DrivingForward](https://github.com/fangzhou2000/DrivingForward). 
Thanks to their excellent works!
