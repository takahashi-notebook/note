# Quantum Computing
量子アニーリングと量子ゲートの二種類ある

## 量子アニーリング
量子論の技術を用いたコンピュータ
以下のようなイジングモデルの最小エネルギーの組み合わせになるため、組み合わせ最適化問題に用いる。
E(x) = Σ Qij * xi * xj
3変数以上の場合も2変数の組み合わせに分解することで、対応できる。
十分な時間でアニーリングした場合、理想的には最適解は保証されるが、通常は最適解の近似解を使用する。  
各量子ビット間の相互作用は古典的でトンネル効果を生む出すパラメータを変えて、モデルの係数を変更する。
量子アニーリングの装置としてDwaveがある。

## 計算Flow
・計算に使用する量子ビット数を決める。  
・量子ビットの計数とバイアスを決める。 
・回路を実行して計算結果（最小のエネルギーになる組み合わせ）を得る。

##　量子ゲート
量子論を用いた汎用のコンピューター
各量子ビットがエンタングルメント状態になっている。
量子ゲートを用いた装置としてIBM Qがある

## 量子ゲートのアルゴリズム
### Deutsch-Jozsa Algorithm  
関数が定値型か分散型か判断するアルゴリスム  

## 計算Flow
・計算に使用する量子ビット数を決める。  
・量子ビットにゲートをかけて、量子回路を作る。  
・回路を実行して計算結果を得る。

### The Bernstein-Vazirani Algorithm  
n-bitのbinaryを見つける  
  
### Simon's Algorithm    
関数が1対1型か2対1型か判断する。

### ショアのアルゴリズム  
因数分解。古典コンピュータのO(e＾n^1/3)以上からO(n＾3)の計算量に減らす。

### Groverのアルゴリズム  
Nのデータを探索する複雑さを、古典コンピュータのO(N)からO(N^1/2)に減らす。  
この2次の速度の向上は、機械学習や最適化問題のような非構造化探索として表現できるタスクで役立つ可能性がある。  

## IBM Q System One  
超電導振動子を利用している量子コンピューター  
使用できるゲートは1つか2に限られる。  
組み合わせによりn-qbitの任意な状態を実現できる。  
右端のqビットを1番目とする:binary表記と同じ。