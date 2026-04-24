# Wiki 操作紀錄

## [2026-04-09] ingest | karpathy.ai 全站初始建置

### 來源
- karpathy.ai 首頁完整擷取
- Karpathy LLM Wiki 方法論 gist (442a6bf555914893e9891c11519de94f)

### 建立的 Raw 檔案（7 個）
- `raw/karpathy-bio.md`
- `raw/karpathy-blog-posts.md`
- `raw/karpathy-talks.md`
- `raw/karpathy-youtube.md`
- `raw/karpathy-courses.md`
- `raw/karpathy-projects.md`
- `raw/karpathy-publications.md`

### 建立的 Wiki 頁面（13 個）

**Entity（2）：**
- `wiki/Andrej Karpathy.md` — hub 頁面
- `wiki/Eureka Labs.md`

**Topic（6）：**
- `wiki/深度學習教育 (Deep Learning Education).md`
- `wiki/軟體 2.0 (Software 2.0).md`
- `wiki/神經網路訓練實務 (Neural Network Training).md`
- `wiki/影像辨識與描述 (Vision and Captioning).md`
- `wiki/大型語言模型 (Large Language Models).md`
- `wiki/自動駕駛與 Tesla AI.md`

**Directory（4）：**
- `wiki/部落格文章目錄 (Blog Posts).md`
- `wiki/演講與訪談目錄 (Talks and Interviews).md`
- `wiki/開源專案目錄 (Open Source Projects).md`
- `wiki/學術論文目錄 (Publications).md`

**Timeline（1）：**
- `wiki/職涯時間線 (Career Timeline).md`

### 更新的頁面
- `wiki/index.md` — 完整導覽入口

### 交叉連結
- 所有頁面雙向連結至 `[[Andrej Karpathy]]` hub
- Topic 頁面連結相關 Directory 與其他 Topic
- Timeline 頁面連結所有相關頁面
- Directory 項目連結至討論它的 Topic 頁面

### 備註
- 此為初始建置，raw/ 檔案為一次性寫入，後續視為不可修改
- 推論性內容已在各頁面中明確標示
- Eureka Labs 頁面 confidence 標記為 medium（公開資訊有限）

## [2026-04-09] query | 卡帕西寶典書籍設計

### 任務
根據 vault 全部內容，分析設計「卡帕西寶典：AI 時代的人類工作方法」書籍架構。

### 建立的頁面
- `wiki/卡帕西寶典 — 書籍設計.md`（type: synthesis）

### 核心產出
- 全書 4 部 11 章 + 楔子 + 尾聲
- 核心命題：人的工作 = 理解 + 判斷 + 傳遞
- 三部曲結構：理解（ch1-3）→ 判斷（ch4-6）→ 傳遞（ch7-9）→ 整合（ch10-11）
- 每章對應 vault 中的具體素材與頁面

### 更新的頁面
- `wiki/index.md` — 新增 Synthesis 分類

## [2026-04-24] query | 卡帕西寶典 27 條原則補案例

### 任務
為「卡帕西寶典 — 書籍設計」中每章「可提煉的原則」區塊，各補一個「原則 × 案例」小節，共 9 章 27 條。

### 修改的頁面
- `wiki/卡帕西寶典 — 書籍設計.md` — 在第一至第九章各插入「原則 × 案例」小節；更新 frontmatter updated 為 2026-04-24

### 案例來源依據
- 所有案例均基於 vault 中可查的公開事件或作品（micrograd、nanoGPT、ImageNet 人機對決、A Recipe for Training Neural Networks、Software 2.0、Tesla AI Day、State of GPT、CS 231n、Zero to Hero、Eureka Labs 創辦論述）
- 部分詮釋（如 Karpathy 的準備過程細節）屬 Claude Code 推論，已於頁面格式中標示為 *斜體案例*，非直接引文
