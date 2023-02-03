# I2C_RS232C_Converter
I2C-RS232C Converter with Grove Connector


## 概要 
  * マイコンのI2CポートをRS232C通信ポートに変換するアダプタです
  * マイコンからI2Cデバイスとして制御し、UARTのボーレート設定、送信、受信処理をすることができます
  * I2C/UARTプロトコルブリッジ[SC16IS750][1]とRS232C変換IC ADM3202を搭載しています
  * I2CはGrove互換コネクタとなっており、3.3V/5V電源に対応しています
  * RS232CポートはD-sub9ピンのオスコネクタを搭載しています
  * I2C/UARTプロトコルブリッジSC16IS750は64bytesのバッファを内蔵しています
  * 7.3728MHzの水晶発振子を搭載しており、マイコンのメインクロックから独立してUARTのボーレート設定ができます  
  * デフォルトI2Cアドレスは8bit:0x9A(7bit:0x4D)です  

## 注意 
  * RS232Cレベル変換している信号はD-sub9ピンの受信の2ピン、送信の3ピンのみです  
  * D-sub9ピンの受信の2ピン、送信の3ピン、GNDの5ピン以外はTTLレベルのため、未接続にしてください    
  * Arduino Uno以外の場合はサンプルコード内SC16IS750.cppの29行目付近のWire定義を必要に応じて変更してください  


## 販売サイト
  * [スイッチサイエンス][2]

<img src="https://raw.githubusercontent.com/meerstern/I2C_RS232C_Converter/master/IR.jpg" width="360">
   
<img src="https://raw.githubusercontent.com/meerstern/I2C_RS232C_Converter/master/IR_2.jpg" width="360">
    
<img src="https://raw.githubusercontent.com/meerstern/I2C_RS232C_Converter/master/img1.jpg" width="360">
<img src="https://raw.githubusercontent.com/meerstern/I2C_RS232C_Converter/master/img2.jpg" width="360">
<img src="https://raw.githubusercontent.com/meerstern/I2C_RS232C_Converter/master/img3.jpg" width="360">
    
[1]: https://www.nxp.com/products/peripherals-and-logic/signal-chain/bridges/single-uart-with-i2c-bus-spi-interface-64-bytes-of-transmit-and-receive-fifos-irda-sir-built-in-support:SC16IS740_750_760 "*1"

[2]: https://www.switch-science.com/products/6026

MIT Lisense
