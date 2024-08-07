# 機械学習（Machine Learning）

# 教師あり機械学習  
教師あり機械学習はデータセットに答えがある場合のこと。    
答えが何かの値か複数ある候補の分類かにより、回帰と分類に分けられる。  
機械学習によりデータセットに対するモデルのパラメータを評価基準を用いて最適化する。  
  
## 教師あり機械学習のフロー
・特徴量と答えのデータセットを準備する。  
（データセットが大きい場合は一度に計算できないので分割する。）  
・モデルを決める。モデルのパラメータの初期値を決める。  
・評価基準が良くなるパラメータの方向を計算する。  
・パラメータを更新する  

### Liner Regression
・データセットの特徴量が1つ  
・データセットの答えが１つ  
・モデルは特徴量に対する線形近似  

### Multi Liner Regression
・データセットの特徴量が複数  
・データセットの答えが１つ  
・モデルは特徴量に対する線形近似  

### Polynomical Liner Regression
・データセットの特徴量を組み合わせて学習に使用する特徴量を作成する  
・データセットの答えが１つ  
・モデルは特徴量に対する線形近似  

## Deep Learning
・行列の線形変換と非線形変換を組み合わせたニューラルネットを用いたモデルを使用する。

## CNN   
周囲の情報を重み付けして出力する畳み込み演算のあるモデルを用いたディープラーニング
主にComputre Visionの分野で用いられる

## RNN  
ある時刻の出力結果を次の時刻の隠れ層に入力するモデルを用いたディープラーニング
主に時系列データや自然言語処理の分野で用いられる

## Transformer  
注意箇所の重み付けを学習するAttension機構を用いたディープラーニング
最近のトレンド技術

## 強化学習
Agentと環境が相互に影響を与える状況において、  
Agentが得られる報酬を大きくなるような行動を学習する。  
ゲーム理論の分野で用いられる

### バンディット問題
環境が変化しない問題

### マルコフ過程
環境が変化する問題