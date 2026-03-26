<div align="center">

<h2>Reflection Separation from a Single Image via Joint Latent Diffusion</h2>

[![project page](https://img.shields.io/badge/Project-Page-2ea44f)](https://brian90709.github.io/diff-reflection-separation/)&nbsp;
[![arXiv](https://img.shields.io/badge/arXiv-coming%20soon-b31b1b.svg)](#)&nbsp;
[![CVPR 2026](https://img.shields.io/badge/CVPR-2026-blue.svg)](#)&nbsp;

</div>

> **Reflection Separation from a Single Image via Joint Latent Diffusion**
>
> Zheng-Hui Huang, Zhixiang Wang, Yung-Yu Chuang, Yu-Lun Liu
>
> Shanda AI Research Tokyo; National Taiwan University; National Yang Ming Chiao Tung University

## Abstract

Single-image reflection separation remains challenging due to its ill-posed nature, especially under extreme conditions with strong or subtle reflections. This paper presents the first diffusion model explicitly fine-tuned for this task, leveraging generative diffusion priors for robust separation. Our method simultaneously generates transmission and reflection layers through a unified diffusion model, incorporating a novel cross-layer self-attention mechanism for better feature disentanglement. We further introduce a disjoint sampling strategy to iteratively reduce interference between the layers during diffusion and a latent optimization step with a learned composition function for improved results in complex real-world scenarios.

## TODO

- [ ] Release code and pre-trained models.

## Citation

If you find this project helpful, please consider citing:

```bibtex
@inproceedings{huang2026reflection,
  title={Reflection Separation from a Single Image via Joint Latent Diffusion},
  author={Huang, Zheng-Hui and Wang, Zhixiang and Chuang, Yung-Yu and Liu, Yu-Lun},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2026}
}
```
