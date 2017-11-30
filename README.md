# lyrics_application
## 完整說明連結
* [以 jieba 與 gensim 探索文本主題：五月天人生無限公司歌詞分析 (I)](https://medium.com/pyladies-taiwan/%E4%BB%A5-jieba-%E8%88%87-gensim-%E6%8E%A2%E7%B4%A2%E6%96%87%E6%9C%AC%E4%B8%BB%E9%A1%8C-%E4%BA%94%E6%9C%88%E5%A4%A9%E4%BA%BA%E7%94%9F%E7%84%A1%E9%99%90%E5%85%AC%E5%8F%B8%E6%AD%8C%E8%A9%9E%E5%88%86%E6%9E%90-i-cd2147b89083)


## 歌詞數據集

1. 蒐集了在 2017/9 ~ 2017/10 之間，五月天人生無限公司巡迴演唱會的歌單(於深圳、洛陽、南京、福州這 4 場)，共 33 首歌詞。 (取自：[Moji 魔鏡歌詞網](https://mojim.com/))
2. 歌詞資料格式整理：特殊字元、統一英文大小寫、排除歌詞雜訊。

### part1：歌詞分析

- 初級任務，利用 jieba.analyse 取出文章中的關鍵詞，透過文字雲做視覺化呈現 。

### part2：主題建模

- 引用 gensim 當中 corpora 、 models、 similarities 模組，分別做語料庫建立、主題模型、與相似度比較。

