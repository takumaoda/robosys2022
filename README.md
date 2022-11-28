# plusコマンド
![test](https://github.com/takumaoda/robosys2022/actions/workflows/test.yml/badge.svg)  
標準入力された数値の和を表示する。

## 必要なソフトウェア
* python
  * テスト済み: 3.7~3.10
## インストール
リポジトリをクローン。  
```ubuntu
$ git clone https://github.com/TakumaOda/robosys2022  
$ cd ~/robosys2022
```	
## 使い方
### 連続した数字を足す場合
`$ seq 5 | ./plus`  
seqは連続番号を出力する。上記の場合1~5までの値を出力し、パイプを使って./plusに入力している。以下にseqの機能を示す。  
* `seq A`: 1~Aまでの連続番号を出力
* `seq A B`: A~Bまでの連続番号を出力
* `seq A B C`: AからBずつ増えるCまでの数字を出力

### ファイルから入力した数字を足す場合
`$ ./plus < nums`  
numsというファイルを./plusに入力している。numsファイルに入っている数字の総和を出力する。numsファイルは数字ごとに改行して記入すること。

## テスト環境
* OS : Windows
* Ubuntu : 18.04


# ライセンス
* このリポジトリは,ロボットシステム学で作った練習用リポジトリであり,[講義資料](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)を参考にしています.
* このソフトウェアパッケージは,3条項BSDライセンスの下,再頒布および使用が許可されます．
* © 2022 Takuma Oda
