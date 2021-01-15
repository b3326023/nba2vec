nba2vec

**任務: 找某些數據/問題，通過修改後的 Word2vec 學習 OOO Embedding，並進行一些評估**

### 構想

NBA2Vec，將 NBA 球員變成向量

1. 收集 NBA 球員資料
2. 將每個球員視為 word，每個球隊視為 sentence
3. 將同一個球隊中的球員，互相視為 context
4. 將不同球隊的球員視為 negative sample
5. 使用 word2vec 學習每個球員的 embedding