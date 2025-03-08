# typec-serial

USB Type-C to serial UART変換基板のKiCadプロジェクト

## 仕様

- ホストPC接続インタフェース: USB Type-C レセプタクル
- UARTデバイス接続インタフェース: 2.54mmピッチ4pinピンヘッダ \
  (実際の通信は、GND, RX, TXだけ使用、残りは3.3V OUTPUT)
- 表示: RX, TXの通信状態をそれぞれLED表示する

## 参考文献

1. じがへるつ, 技術の泉シリーズ　はじめてのType-C電子工作 (株式会社インプレス, 東京, 2024).
2. じがへるつ, 最強FTDIの新定番 USB-シリアルIC大研究, トランジスタ技術 第62巻, 第3号, pp.63-67, (2025).
