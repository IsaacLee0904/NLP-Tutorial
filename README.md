# NLP-Tutorial
## Bag-of-Words
### 基本概念
詞袋的概念就是將文字所包含的所有字詞都整理出來後，丟進一個袋子裡裝起來。而其排列的順序關係是不具意義的，重要的是出現過哪些字。
可以做成像右邊的表，顯示每個字在文章中出現幾次，這就是詞袋模型的主要概念。
### 缺點
* 容易造成維度災難(curse of dimensionality)
* 向量表達過於鬆散(sparse)
* 無法表達詞和詞之間的語意關係

## Word to Vectors
Word2Vec 是一種 Word Embedding 的方法，而所謂鑲嵌(embedding)指的是鑲嵌入一個空間的概念，並且在其中有可以表達自己的一個形式。空間概念可能有很多種不同的概念，例如(x,y,z)的座標空間。而 Word Embedding就是要怎麼表示一個字，讓他可以鑲嵌入語言模型中。

開發者希望每個詞彙可以表達出在語義上面的意義，而想出了一個想法，而基於這個想法建立了兩個模型去實作，分別是 CBoW(連續詞袋模型) 和 Skip-gram。
## Regexes
## Stemming & Lemmatization
## Stopwords
## Spell correction
## Sentiment
## POS tagging
