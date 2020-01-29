Name
va_value_predictor

Overview

## Description
MP3ファイルから音楽特徴量を抽出し、Valence, Arousal valueを算出する。

## Demo

## Requirement
Python 3.7.3  

-Python Package-
librosa 0.7.1
xgboost 0.90  



## Usage
・　audioフォルダ配下に音楽ファイル（mp3ファイル）を配置してください  
・　音楽ファイルを配置したらcodeフォルダ配下のgenerate_test.pyを実行してください  
（generate_test.pyの実行が終わるとinputフォルダ配下にtest.csvが作成されます）  
・　その後、predict_va.pyを実行してください
（実行するとVA valueが画面出力され、outputフォルダ配下のsub.pyに保存されます）

## Author
Takato Matsumoto
