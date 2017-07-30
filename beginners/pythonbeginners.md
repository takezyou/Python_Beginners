# 初心者環境構築＆Python基礎チーム

# jupyter notebook
- http://qiita.com/masafumi_miya/items/6524dbd227705351a00c
	- ショートカットキー

## Anacondaのインストール(Python2.7系)
Anacondaとは  
Continuum Analytics 社によって提供されている、Python 本体に加え、科学技術、数学、エンジニアリング、データ分析など、よく利用される Python パッケージを一括でインストール可能にしたパッケージです
- https://www.continuum.io
- 右上の方にDOWNLOADがあるのでそれをクリック
- 使っているOSを選択しPython 2.7 versionをダウンロードします
- Macの方は~/anacondaにイントールされるのでpathを通してあげないといけません
---
.bash_profile
```
export PATH="/Users/user_name/anaconda/bin:$PATH"
```
---

## Pythonの基礎
- http://bootcamp-text.readthedocs.io
- 2.Pythonをはじめよう
- 3.Pythonのデータ型(基本編)
- 4.Pythonのデータ型(コレクション)
- 5.ファイル操作とモジュール

## Pandasのチートシート
- http://qiita.com/tanemaki/items/2ed05e258ef4c9e6caac
- https://www.analyticsvidhya.com/blog/2015/07/11-steps-perform-data-analysis-pandas-python/

## TensorFlowとKerasのインストール
- https://www.tensorflow.org
- https://keras.io/ja/
```
pip install tensorflow
conda install tensorflow
```
```
pip install keras
```

## Kerasを使ったmnist画像認識


