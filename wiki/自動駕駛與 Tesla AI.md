---
tags: [自動駕駛, Tesla, 電腦視覺, 工業應用]
type: topic
created: 2026-04-09
updated: 2026-04-09
source_type: raw
source_files:
  - raw/karpathy-bio.md
  - raw/karpathy-talks.md
confidence: high
status: active
---

# 自動駕駛與 Tesla AI

[[Andrej Karpathy]] 在 Tesla 擔任 AI 總監期間（2017–2022）的工作與貢獻。

## 概述

Karpathy 在 Tesla 期間領導 Autopilot 視覺團隊，負責自動駕駛系統的神經網路開發。他推動了從多感測器融合到純視覺（vision-only）方案的策略轉變，是 Tesla AI 技術路線的核心推手。

## 技術方向

### 純視覺方案 (Vision-only Approach)

Tesla 在 Karpathy 的領導下逐步移除雷達與超音波感測器的依賴，改為完全依靠攝影機與神經網路進行環境感知。這一決策具有爭議性，但體現了 [[軟體 2.0 (Software 2.0)]] 的核心理念——用學習取代手寫規則。

### 大規模資料與訓練

Tesla 擁有全球最大的駕駛資料集（車隊收集），Karpathy 團隊利用這些資料訓練大規模神經網路，處理：
- 物體偵測與追蹤
- 車道與道路結構辨識
- 3D 空間重建（從 2D 影像到 3D 場景）
- 行為預測

### AI 基礎設施

Tesla 在 Karpathy 任期內建立了自有的 AI 訓練基礎設施，包括 Dojo 超級電腦專案。

## 重要演講

| 年份 | 活動 | 主題 | URL |
|------|------|------|-----|
| 2021 | Tesla AI Day | 完整介紹 Tesla AI 架構 | https://youtu.be/j0z4FweCy4M?t=2900 |
| 2021 | CVPR | AI for Full Self-Driving | https://www.youtube.com/watch?v=g6bOwQdCJrc |
| 2020 | ScaledML | AI for Full Self-Driving | https://www.youtube.com/watch?v=hx7BXih7zx8 |
| 2019 | Tesla Autonomy Day | 自駕願景展示 | https://www.youtube.com/watch?v=Ucp0TTmvqOE&t=6678 |
| 2019 | PyTorch DevCon | PyTorch at Tesla | https://www.youtube.com/watch?v=oBklltKXtDE |
| 2019 | ICML | Multi-Task Learning in the Wilderness | https://slideslive.com/38917690/multitask-learning-in-the-wilderness |

詳見 [[演講與訪談目錄 (Talks and Interviews)]]。

## 與學術研究的延續

Karpathy 在 Tesla 的工作是其 Stanford 電腦視覺研究的工業延伸。博士期間的影像理解研究（見 [[影像辨識與描述 (Vision and Captioning)]]）為他在 Tesla 領導大規模視覺 AI 系統提供了深厚的技術基礎。

## 離開 Tesla

Karpathy 於 2022 年離開 Tesla，隨後投入深度學習教育內容創作（見 [[深度學習教育 (Deep Learning Education)]]），並於 2024 年創辦 [[Eureka Labs]]。

## 相關頁面

- [[Andrej Karpathy]]
- [[軟體 2.0 (Software 2.0)]]
- [[影像辨識與描述 (Vision and Captioning)]]
- [[演講與訪談目錄 (Talks and Interviews)]]
- [[職涯時間線 (Career Timeline)]]

## 來源

- [[raw/karpathy-bio.md]]
- [[raw/karpathy-talks.md]]
