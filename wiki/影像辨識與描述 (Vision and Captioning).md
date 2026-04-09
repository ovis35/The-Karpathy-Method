---
tags: [電腦視覺, 影像描述, 學術研究]
type: topic
created: 2026-04-09
updated: 2026-04-09
source_type: raw
source_files:
  - raw/karpathy-publications.md
  - raw/karpathy-projects.md
  - raw/karpathy-blog-posts.md
confidence: high
status: active
---

# 影像辨識與描述 (Vision and Captioning)

[[Andrej Karpathy]] 在電腦視覺與影像描述生成領域的學術貢獻。

## 概述

Karpathy 的博士研究聚焦於影像與自然語言的連結——如何讓機器「看懂」影像並用自然語言描述。這項工作橫跨電腦視覺與自然語言處理，是多模態 AI 的早期重要推動力。

## 博士論文

- **Connecting Images and Natural Language**（2016）
- Stanford University，指導教授：Fei-Fei Li
- [全文](https://cs.stanford.edu/people/karpathy/main.pdf)

## 核心研究成果

### 影像描述生成 (Image Captioning)

- **Deep Visual-Semantic Alignments for Generating Image Descriptions**（CVPR 2015, Oral）
  - 將影像區域與句子片段對齊，生成自然語言描述
  - 這項工作受到廣泛關注，被紐約時報報導
  - [專案頁](http://cs.stanford.edu/people/karpathy/deepimagesent/)

- **Deep Fragment Embeddings for Bidirectional Image-Sentence Mapping**（NIPS 2014）
  - 雙向影像-句子映射
  - [PDF](https://cs.stanford.edu/people/karpathy/nips2014.pdf)

- **Grounded Compositional Semantics**（TACL 2013, 與 Richard Socher 等合作）
  - 基於組合語義的影像搜尋與描述

### 密集描述 (Dense Captioning)

- **DenseCap: Fully Convolutional Localization Networks for Dense Captioning**（CVPR 2016, Oral）
  - 不僅描述整張影像，而是對影像中每個區域生成描述
  - 與 Justin Johnson 合作
  - [專案頁](https://cs.stanford.edu/people/karpathy/densecap/)

### 影片分類

- **Large-Scale Video Classification with Convolutional Neural Networks**（CVPR 2014, Oral）
  - 大規模影片分類的早期重要工作
  - [專案頁](https://cs.stanford.edu/people/karpathy/deepvideo/)

### ImageNet 挑戰

- **ImageNet Large Scale Visual Recognition Challenge**（IJCV 2015）
  - Karpathy 曾親自與 ConvNet 在 ImageNet 分類上對決
  - 部落格記錄：[What I learned from competing against a ConvNet on ImageNet](https://karpathy.github.io/2014/09/02/what-i-learned-from-competing-against-a-convnet-on-imagenet/)

### RNN 分析

- **Visualizing and Understanding Recurrent Networks**（ICLR 2016 Workshop）
  - 分析 RNN 內部機制的視覺化研究

## 開源實作

- **neuraltalk2**：Torch 影像描述生成系統
- **densecap**：密集描述生成系統

見 [[開源專案目錄 (Open Source Projects)]]。

## 與後續工作的連結

Karpathy 在影像描述生成上的研究，為後來的多模態大型模型（如 GPT-4V、Claude Vision）奠定了概念基礎——將視覺與語言在同一個表示空間中對齊。

> 注：此段為 Claude Code 基於研究脈絡的推論整理，Karpathy 的直接貢獻止於其發表的論文。

## 相關頁面

- [[Andrej Karpathy]]
- [[學術論文目錄 (Publications)]]
- [[開源專案目錄 (Open Source Projects)]]
- [[自動駕駛與 Tesla AI]]
- [[職涯時間線 (Career Timeline)]]

## 來源

- [[raw/karpathy-publications.md]]
- [[raw/karpathy-projects.md]]
- [[raw/karpathy-blog-posts.md]]
