# I2C_RS232C_Converter
I2C-RS232C Converter with Grove Connector


## 概要 
  * マイコンのI2CポートをRS232C通信ポートに変換するアダプタです
  * マイコンからI2Cデバイスとして制御し、UARTのボーレート設定、送信、受信処理をすることができます
  * I2C/UARTプロトコルブリッジ[SC16IS750][1]とRS232C変換IC ADM3202を搭載しています
  * I2CはGroveコネクタとなっており、3.3V/５V電源に対応しています
  * I2C/UARTプロトコルブリッジSC16IS750は64bytesのバッファを内蔵しています
  * 7.3728MHzの水晶発振子を搭載しており、マイコンのメインクロックから独立してUARTのボーレート設定ができます  


<img src="https://raw.githubusercontent.com/meerstern/I2C_RS232C_Converter/master/IR.jpg" width="360">
   
<img src="https://raw.githubusercontent.com/meerstern/I2C_RS232C_Converter/master/IR_2.jpg" width="360">
    
    
[1]: https://www.nxp.com/products/peripherals-and-logic/signal-chain/bridges/single-uart-with-i2c-bus-spi-interface-64-bytes-of-transmit-and-receive-fifos-irda-sir-built-in-support:SC16IS740_750_760 "*1"

MIT Lisense