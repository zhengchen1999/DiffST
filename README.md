# DiffST: Spatiotemporal-Aware Diffusion for Real-World Space-Time Video Super-Resolution

[Zheng Chen](https://zhengchen1999.github.io/), [Ruofan Yang](https://github.com/RENLEILEI-Y), [Jin Han](), [Dehua Song](), [Zichen Zou](), [Chunming He](), [Yong Guo](), [Yulun Zhang](http://yulunzhang.com/), "DiffST: Spatiotemporal-Aware Diffusion for Real-World Space-Time Video Super-Resolution"

<div>
<a href="https://arxiv.org/abs/2605.13182" target="_blank" style="text-decoration: none;"><img src="https://img.shields.io/badge/arXiv-2605.13182-b31b1b.svg"></a>
<a href="https://github.com/zhengchen1999/DiffST" target='_blank' style="text-decoration: none;"><img src="https://visitor-badge.laobi.icu/badge?page_id=zhengchen1999/DiffST"></a>
<a href="https://github.com/zhengchen1999/DiffST/stargazers" target='_blank' style="text-decoration: none;"><img src="https://img.shields.io/github/stars/zhengchen1999/DiffST?style=social"></a>
</div>

[[project](https://zheng-chen.cn/DiffST)] [[arXiv](https://arxiv.org/abs/2605.13182)]

#### 🔥🔥🔥 News

- **2026-05-13:** This repo is released. DiffST is available on arXiv.

---

> **Abstract:** Diffusion-based models have shown strong performance in video super-resolution (VSR) and video frame interpolation (VFI). However, their role in the coupled space-time video super-resolution (STVSR) setting remains limited. Existing diffusion-based STVSR approaches suffer from two issues: (1) low inference efficiency and (2) insufficient utilization of spatiotemporal information. These limitations impede deployment. To address these issues, we introduce **DiffST**, an efficient spatiotemporal-aware video diffusion framework for real-world STVSR. To improve efficiency, we adapt a pre-trained diffusion model for one-step sampling and process the entire video directly rather than operating on individual frames. Furthermore, to enhance spatiotemporal information utilization, we introduce cross-frame context aggregation (CFCA) and video representation guidance (VRG). The CFCA module aggregates information across multiple keyframes to produce intermediate frames. The VRG module extracts video-level global features to guide the diffusion process. Extensive experiments show that DiffST obtains leading results on real-world STVSR tasks. It also maintains high inference efficiency, running about 17&times; faster than previous diffusion-based STVSR methods.

<img src="figs/compare.png" width="100%"/>

## ⚒️ TODO

* [ ] Release code and pretrained models

## 🔎 Method Overview

<img src="figs/method.png" width="100%"/>

## <a name="results"></a>🔎 Results

<details open>
<summary>Quantitative Results (click to expand)</summary>

- Results in Tab. 4 of the main paper

<p align="center">
  <img width="900" src="figs/quantitative.png">
</p>
<details>
<summary>More Quantitative Results</summary>

- More results in Tab. 6 of the supplementary mateiral

<p align="center">
  <img width="900" src="figs/quantitative-1.png">
</p>

- More results in Tab. 7 of the supplementary material

<p align="center">
  <img width="900" src="figs/quantitative-2.png">
</p>
</details>

<details open>
<summary>Qualitative Results (click to expand)</summary>

- Results in Fig. 7 of the main paper

<p align="center">
  <img width="900" src="figs/visual.png">
</p>
<details>
<summary>More Qualitative Results</summary>

- More results in Fig. 7 of the supplementary material

<p align="center">
  <img width="900" src="figs/visual-1.png">
</p>

- More results in Fig. 8 of the supplementary material

<p align="center">
  <img width="900" src="figs/visual-2.png">
</details>

## <a name="citation"></a>📎 Citation

If you find the code helpful in your research or work, please cite our work.

```
@article{chen2026diffst,
  title = {DiffST: Spatiotemporal-Aware Diffusion for Real-World Space-Time Video Super-Resolution},
  author = {Chen, Zheng and Yang, Ruofan and Han, Jin and Song, Dehua and Zou, Zichen and He, Chunming and Guo, Yong and Zhang, Yulun},
  journal = {arXiv preprint arXiv:2605.13182},
  year = {2026}
}
```


## <a name="acknowledgements"></a>💡 Acknowledgements

This project is based on [Wan2.1](https://github.com/Wan-Video/Wan2.1).
