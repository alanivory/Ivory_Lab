---
title: "AdaptGrad: Adaptive Gradient Compression for Distributed ML"

summary: |
  An open-source library implementing adaptive gradient compression for distributed neural network training. Reduces communication overhead by up to 8× with negligible accuracy loss.

tags:
  - Machine Learning
  - Distributed Systems
  - Open Source
  - Python

date: "2022-01-01"

external_link: "https://github.com/alanivory/adaptgrad"

image:
  caption: ''
  focal_point: Smart

links:
  - icon: brands/github
    icon_pack: fab
    name: GitHub
    url: https://github.com/alanivory/adaptgrad

url_code: "https://github.com/alanivory/adaptgrad"
url_pdf: ""
url_slides: ""
url_video: ""
---

AdaptGrad is an open-source Python library that implements adaptive gradient compression for distributed neural network training. The key innovation is dynamically adjusting compression ratios based on gradient magnitude distributions, achieving the optimal trade-off between communication efficiency and model quality.

## Features

- **Dynamic compression ratio**: Automatically tunes compression per layer and iteration
- **Drop-in replacement**: Compatible with PyTorch's `DistributedDataParallel`
- **Benchmarked performance**: 3–5× wall-clock speedup on standard vision and language models
- **Multi-backend support**: Works with NCCL, Gloo, and MPI backends

## Status

Active development — contributions welcome!
