# Gossiping-Chinese-Positive-Corpus
PTT 八卦版問答-正面-中文語料

在zake7749的Gossiping-Chinese-Corpus資料上，抽出其中所有正面情緒的對話語料 [https://github.com/zake7749/Gossiping-Chinese-Corpus](https://github.com/zake7749/Gossiping-Chinese-Corpus)

## 資料說明

### Gossiping-QA-pos-Dataset-2_0.csv

來自 Gossiping-QA-Dataset-2_0.csv 資料集，從其中 774,114 筆問答配對中做情緒分析，抽取所有預測正面情緒的句子(正面機率>50%)，最終整理出 197926 筆資料。   
其中 最低正面機率：0.50，最高正面機率：0.94，平均正面機率：0.64。   
資料格式調整為 csv，包含了三個 columns: `question` ， `answer` 和 `positive probability`    

```csv
20 世 紀 還 有 媲 美 或 超 越 鋼 鍊 的 神 作 嗎,鋼 鍊 神 在 劇 情 從 一 開 始 就 編 排 好 了 不 是 邊 走 邊 想,0.789045512676239
紅 色 代 表 喜 氣 嗎,跟 用 過 的 衛 生 棉 一 樣 嶄 新 的 開 始,0.7111006379127502
新 年 快 樂 姆 咪 姆 咪,姆 咪 姆 咪 學 金 雞 咕 咕 咕 咕 咕 咕 咕,0.7134743332862854
現 在 在 超 商 值 班 的 店 員 在 想 什 麼,便 利 商 店 店 員 很 辛 苦 好 ㄇ,0.8957672715187073
本 金 城 武 感 謝 一 年 來 八 卦 版 肥 宅 的 支 持,這 種 萬 年 爛 梗 是 還 要 用 多 久,0.7482118010520935
新 年 感 恩 送 紅 包,新 年 快 樂 收 到 感 謝,0.8411140441894531
```
