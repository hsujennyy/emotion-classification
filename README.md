# NLP Emotion Classification

這是一個使用 RNN 進行情感分類的專案，基於社群媒體（Dcard/PTT）文本數據，對文本情緒進行標註與分類。

## 專案內容
- **資料來源**：Dcard/PTT 貼文，手動標註核心情緒
- **NLP 預處理**：
  - 斷詞
  - 停用詞過濾
  - 標註情感類別（核心情緒、抑制情緒、防禦情緒）
- **模型**：
  - 使用 RNN（遞歸神經網路）建模
  - 訓練文本情感分類器
  - 評估與測試模型效能

## 主要技術
- **Python**：處理數據與建模
- **自然語言處理（NLP）**：分詞、標註、數據清理
- **深度學習（Deep Learning）**：使用 Pytorch 訓練 RNN 模型


