# main-ECU-board
- このブランチは作業記録を残すためだけに残してある

## Overview
- メインECUのハードウェア

## Requirement
### Development
- Kicad7.0
### Boards
- Arduino UNO R4
### Libraries
- Digi-Key Kicad Library
- Digi-Key Kicad Library にないもの
    - [ここ](https://componentsearchengine.com/) で検索してダウンロード
    - Library Loader を使用

## Usage
- Arduino UNO R4 互換(ブートローダのインストール必須)
    - 各種ヘッダーピン
    - R4 では使用できなかったピンも使用可能
- 車載対応
    - CANトランシーバ
    - ロードスイッチ(AIRなどへの12V供給)

## Features
- [ブートローダのインストール方法](./documents/install-boot-loader/)

## Reference
- [documents](./documents/) 内、使用ICの各種データシート

## Author
- [Takamura](https://github.com/ST04-tkmr)

## License
- Copyright (c) 2023 東京工科大学 ProjectEV [Released under the MIT license](./LICENSE)
