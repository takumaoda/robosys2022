# plusコマンド
![test](https://github.com/takumaoda/robosys2022/actions/workflows/test.yml/badge.svg)  
標準入力された数値の和を表示する。

## 必要なソフトウェア
* python
  * テスト済み: 3.7~3.10

## 使い方
### 連続した数字を足す場合
`$ seq 5 | ./plus`  
seqは連続番号を出力する。上記の場合1~5までの値を出力し、パイプを使って./plusに入力している。  
* `seq A`: 1~Aまでの連続番号を出力
* `seq A B`: A~Bまでの連続番号を出力
* `seq A B C`: AからBずつ増えるCまでの数字を出力

## テスト環境
Ubuntu18.04で動作確認済み

# ライセンス
* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
* © 2022 Takuma Oda
