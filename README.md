# DiffST: Spatiotemporal-Aware Diffusion for Real-World Space-Time Video Super-Resolution

[Zheng Chen](https://zhengchen1999.github.io/), [Ruofan Yang](https://github.com/RENLEILEI-Y), [Jin Han](), [Dehua Song](), [Zichen Zou](), [Chunming He](), [Yong Guo](), [Yulun Zhang](http://yulunzhang.com/), "DiffST: Spatiotemporal-Aware Diffusion for Real-World Space-Time Video Super-Resolution"

<div>
<a href="https://github.com/zhengchen1999/DiffST/releases" target='_blank' style="text-decoration: none;"><img src="https://img.shields.io/github/downloads/zhengchen1999/DiffST/total?color=green&style=flat"></a>
<a href="https://github.com/zhengchen1999/DiffST" target='_blank' style="text-decoration: none;"><img src="https://visitor-badge.laobi.icu/badge?page_id=zhengchen1999/DiffST"></a>
<a href="https://github.com/zhengchen1999/DiffST/stargazers" target='_blank' style="text-decoration: none;"><img src="https://img.shields.io/github/stars/zhengchen1999/DiffST?style=social"></a>
</div>

[[project](https://zhengchen1999.github.io/DiffST/)] [[arXiv]()] [[supplementary material](https://github.com/zhengchen1999/DiffST/releases/download/v1/Supplementary_Material.pdf)]

#### 🔥🔥🔥 News

- **2026-XX-XX:** This repo is released.

---

> **Abstract:** Diffusion-based models have achieved remarkable results in tackling video super-resolution (VSR) and video frame interpolation (VFI). However, their exploration in the combined setting of the two, namely space-time video super-resolution (STVSR), remains limited. Existing diffusion-based STVSR approaches suffer from two issues: (1) low inference efficiency and (2) insufficient utilization of spatiotemporal information. These limitations hinder their applicability in real-world scenarios. To address these issues, we propose DiffST, an efficient spatiotemporal-aware video diffusion model for real-world STVSR. To ensure efficiency, we utilize the pre-trained diffusion model in a one-step sampling manner. Meanwhile, we process the entire video directly rather than operating on individual frames. On the other hand, to enhance spatiotemporal information utilization, we introduce cross-frame context aggregation (CFCA) and video representation guidance (VRG). The CFCA module aggregates information across multiple keyframes to produce intermediate frames, expanding the scope of spatiotemporal context. The VRG module extracts a global video representation to guide the diffusion process with explicit spatiotemporal cues. Extensive experiments show that our DiffST achieves state-of-the-art performance on real-world STVSR tasks in terms of fidelity, perceptual quality, and temporal consistency. It also maintains high efficiency, achieving approximately 17× speed-up over existing diffusion-based STVSR methods.

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
TBD
```


## <a name="acknowledgements"></a>💡 Acknowledgements