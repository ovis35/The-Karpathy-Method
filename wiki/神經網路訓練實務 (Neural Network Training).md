---
tags: [神經網路, 訓練, 方法論, 除錯]
type: topic
created: 2026-04-09
updated: 2026-04-09
source_type: raw
source_files:
  - raw/karpathy-blog-posts.md
  - raw/karpathy-youtube.md
confidence: high
status: active
---

# 神經網路訓練實務 (Neural Network Training)

[[Andrej Karpathy]] 對神經網路訓練方法論的系統性整理。

## 核心文章：A Recipe for Training Neural Networks

- 發表：2019-04
- URL：https://karpathy.github.io/2019/04/25/recipe/

這篇文章是 Karpathy 最具實務價值的作品之一，系統性地整理了訓練神經網路的步驟與常見陷阱。其核心訊息是：**神經網路訓練不應該是隨機嘗試，而應該遵循一套有紀律的流程。**

### 訓練流程要點

Karpathy 提出的漸進式訓練策略（基於原文整理）：

1. **先理解資料**：在寫任何模型程式碼前，徹底檢視資料
2. **建立端到端骨架**：用最簡單的模型跑通整個 pipeline
3. **過擬合（overfit）一個小 batch**：確認模型有學習能力
4. **正規化（regularize）**：加入正規化手段對抗過擬合
5. **調參（tune）**：系統性地調整超參數
6. **擠壓（squeeze）**：榨取最後一點效能

### 除錯哲學

- 不要跳步驟
- 每一步都要有明確的預期結果
- 出現異常時回到上一個已確認正常的狀態
- 用視覺化而非直覺來判斷

## 相關教學內容

### Zero to Hero 系列

Neural Networks: Zero to Hero 系列影片將上述方法論融入教學，每集都示範如何從零建構、訓練並除錯模型。見 [[深度學習教育 (Deep Learning Education)]]。

### 開源實作

- **micrograd**：展示反向傳播的最小實作
- **char-rnn**：字元級語言模型訓練範例

見 [[開源專案目錄 (Open Source Projects)]]。

## 相關頁面

- [[Andrej Karpathy]]
- [[深度學習教育 (Deep Learning Education)]]
- [[軟體 2.0 (Software 2.0)]]
- [[部落格文章目錄 (Blog Posts)]]
- [[開源專案目錄 (Open Source Projects)]]

## 來源

- [[raw/karpathy-blog-posts.md]]
- [[raw/karpathy-youtube.md]]
