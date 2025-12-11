# Machine Learning in Education Research
學生生活習慣與學習成績的關聯分析

> 利用 Kaggle「Student Habits vs Academic Performance」資料集，從資料探索、監督式學習到分群分析，研究學生生活習慣與期末成績之間的關聯性。

---

## 1. 專案簡介

本專案以模擬的學生生活習慣與學業表現資料為基礎，探討以下問題：

- 哪些生活習慣（讀書時間、睡眠、運動、社群媒體使用等）與成績關聯最高？
- 能否利用生活習慣特徵，預測學生的期末考成績（exam_score）？
- 學生是否可以依照生活型態被分成不同族群？各族群的學習成績有何差異？
本專案的分析流程包含：

1. **資料探索 (EDA)**：基本統計、直方圖、盒鬚圖、相關係數熱圖。
2. **監督式學習**：以多元線性迴歸預測期末成績。
3. **非監督式學習**：以 K-means 與 PCA 發掘不同「生活型態群」，並比較群間成績差異。

---

## 2. 專案結構

專案主要檔案說明如下：
.
├── EDA.ipynb                  # 資料探索 (EDA)：統計量、分布圖、盒鬚圖、相關係數
├── supervised learning.ipynb  # 監督式學習：多元線性迴歸預測 exam_score
├── unsupervised learning.ipynb # 非監督式學習：標準化、K-means、PCA 視覺化與群體分析
├── White and Peach Cute Hand Drawn Playful Group Project Presentation.pdf # 簡報檔，整理研究背景、流程與結果

