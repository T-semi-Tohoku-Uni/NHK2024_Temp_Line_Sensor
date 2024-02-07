# NHK2024_Temp_Line_Sensor

## 使ったセンサ
QTR-8A フォトリフレクタアレイ

## プログラムの概要
センサからの値を`ADC1`, `ADC2`を使ってディジタル化し, DMA(メモリにマップして高速化)を使いセンサの値を取得

## 諸々のパラメータ
- 制御周期（タイマの割り込み周期）: 1MHz

## 参考サイト
これで動いた
https://qiita.com/numeru55/items/88fefe28520c24abc06a