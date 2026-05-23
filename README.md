# Fine-Grained Fashion Feature Embedding for Global, Local, and Contextual Analysis in Fashion Social Media Popularity Prediction
This repository provides the project page and dataset links for the paper "Fine-Grained Fashion Feature Embedding for Global, Local, and Contextual Analysis in Fashion Social Media Popularity Prediction" (IEEE Access 2026).

Paper link: https://ieeexplore.ieee.org/document/11522804

# WEAR-PD

WEAR-PD is a fashion social media popularity prediction dataset constructed from [WEAR](https://wear.jp/), a Japanese fashion coordination platform.

The dataset contains fashion posts with multimodal information, including image URLs, posting dates, hashtags, item tag counts, descriptions, comment status, popularity scores, anonymized user indices, official status, post counts, following counts, and follower counts. WEAR-PD covers 313,532 posts from 17,187 users, collected from December 2012 to May 2024. Additional details are listed in the supplementary material.

Hugging Face Dataset: https://huggingface.co/datasets/iampom/WEAR-PD

## Dataset Release Policy

We do not redistribute raw WEAR images. Instead, the released dataset provides image URLs for reproducibility.

Original user IDs are not included. They are replaced with internal anonymized user indices. 
The release includes metadata, textual contents, and generated captions.

Users are responsible for complying with the terms of the original platform. 
The dataset must not be used for re-identification, user profiling, commercial targeting, redistribution of raw images, or any use that may harm the privacy or rights of the original users.

## SMPD-Fashion

SMPD-Fashion is constructed from the [Social Media Popularity Dataset](https://smp-challenge.com/download_image.html).
We do not redistribute SMPD-Fashion because it is derived from the original SMPD dataset. 
To reproduce SMPD-Fashion, please download the original SMPD dataset from the official SMP Challenge website.

After downloading SMPD, extract the samples whose `Category == Fashion`. 
Additional details are listed in sec.IV.A. in the main paper.

## Citation

If you find this work useful, please consider citing the following paper:

```bibtex
@ARTICLE{FFGLC2026,
  author={Okamoto, Shun and Iizuka, Satoshi and Fukui, Kazuhiro},
  journal={IEEE Access}, 
  title={Fine-Grained Fashion Feature Embedding for Global, Local, and Contextual Analysis in Fashion Social Media Popularity Prediction}, 
  year={2026},
  volume={14},
  number={},
  pages={75674-75689},
  doi={10.1109/ACCESS.2026.3694039}
}


